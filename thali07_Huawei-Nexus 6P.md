#### Test 9103315287a8d91_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-26 18:05:44.082  3968  4217 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
10-26 18:05:44.161  3968  4217 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,10-26 18:05:44.622  5650  5650 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-26 18:05:44.628  5650  5650 D AndroidRuntime: CheckJNI is OFF
10-26 18:05:44.660  5650  5650 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-26 18:05:44.695  5650  5650 I Radio-JNI: register_android_hardware_Radio DONE
10-26 18:05:44.711  5650  5650 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-26 18:05:44.714   929  3790 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-26 18:05:44.731  5650  5650 D AndroidRuntime: Shutting down VM
10-26 18:05:44.739  3936  3962 W SearchService: Abort, client detached.
10-26 18:05:44.751  3936  3936 I HotwordDetector: Closing mic
10-26 18:05:44.752  3936  4204 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@59cf529
10-26 18:05:44.752  3936  4215 E AudioRecord-JNI: Error -4 during AudioRecord native read
10-26 18:05:44.762   929  3800 I ActivityManager: Start proc 5659:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-26 18:05:44.830   515  4221 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
10-26 18:05:44.832   515  4221 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
10-26 18:05:44.835   515  4221 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
10-26 18:05:44.835   515  4221 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
10-26 18:05:44.836   515  2988 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
10-26 18:05:44.838  3936  4206 I MicroRecognitionRnrImpl: Stopping hotword detection.
10-26 18:05:44.838  3936  4214 I MicroRecognitionRnrImpl: Detection finished
10-26 18:05:44.860  5659  5659 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
10-26 18:05:44.879  5659  5659 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
10-26 18:05:44.932  5659  5659 I LibraryLoader: Time to load native libraries: 49 ms (timestamps 8698-8747)
10-26 18:05:44.932  5659  5659 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 18:05:44.959  5659  5659 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d03c0fe}
,10-26 18:05:44.959  5659  5659 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-26 18:05:44.960  5659  5659 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 18:05:44.966  5659  5659 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 18:05:44.967  5659  5659 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 18:05:45.040  5659  5659 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 18:05:45.055  5659  5659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-26 18:05:45.055  5659  5659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 18:05:45.055  5659  5659 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 18:05:45.055  5659  5659 I Adreno  : Build Date                       : 12/06/15
10-26 18:05:45.055  5659  5659 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 18:05:45.055  5659  5659 I Adreno  : Local Branch                     : mybranch17112971
10-26 18:05:45.055  5659  5659 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 18:05:45.055  5659  5659 I Adreno  : Remote Branch                    : NONE
10-26 18:05:45.055  5659  5659 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 18:05:45.087   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a26d66:true
,10-26 18:05:45.110   402   402 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[25309]" dev="sockfs" ino=25309 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 18:05:45.110   402   402 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25309]" dev="sockfs" ino=25309 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 18:05:45.120  5659  5659 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 18:05:45.129  5659  5659 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 18:05:45.150   504   504 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33301]" dev="sockfs" ino=33301 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 18:05:45.150   504   504 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33301]" dev="sockfs" ino=33301 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-26 18:05:45.152  5659  5696 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-26 18:05:45.153  3802  3802 W Binder_A: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30828]" dev="sockfs" ino=30828 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:05:45.153  3802  3802 W Binder_A: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30828]" dev="sockfs" ino=30828 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 18:05:45.155  5659  5683 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-26 18:05:45.180  5659  5696 I OpenGLRenderer: Initialized EGL, version 1.4
,10-26 18:05:45.250  3800  3800 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33306]" dev="sockfs" ino=33306 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:05:45.254   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +513ms
,10-26 18:05:45.250  3800  3800 W Binder_9: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33306]" dev="sockfs" ino=33306 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 18:05:45.253  3183  3183 W Binder_4: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33305]" dev="sockfs" ino=33305 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 18:05:45.253  3183  3183 W Binder_4: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33305]" dev="sockfs" ino=33305 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:05:45.258  3636  3636 I Keyboard.Facilitator: onFinishInput()
,10-26 18:05:45.303  5659  5659 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5659
,10-26 18:05:45.389  5659  5659 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-26 18:05:45.516  5659  5698 D jxcore_app_log: JniHelper::setJavaVM(0xf547c000), pthread_self() = -579339984
,10-26 18:05:45.522  5659  5698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-26 18:05:45.522  5659  5698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-26 18:05:45.522  5659  5698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-26 18:05:45.522  5659  5698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-26 18:05:45.522  5659  5698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-26 18:05:45.522  5659  5698 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5666ded added. We now have 1 listener(s)
,10-26 18:05:45.524  5659  5698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,10-26 18:05:45.525  5659  5698 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:05:45.525  5659  5698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:05:45.525  5659  5698 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-26 18:05:45.527  5659  5698 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de2ec70 added. We now have 1 listener(s)
10-26 18:05:45.527  5659  5698 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 18:05:45.532   929  2982 D WifiService: New client listening to asynchronous messages
10-26 18:05:45.533  5659  5698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 18:05:45.533  5659  5698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-26 18:05:45.533  5659  5698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-26 18:05:45.533  5659  5698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-26 18:05:45.533  5659  5698 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-26 18:05:45.541  5659  5698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 18:05:45.542  5659  5698 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,10-26 18:05:45.545  5659  5698 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-26 18:05:45.545  5659  5698 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:05:45.545  5659  5698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:05:45.545  5659  5698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:05:45.545  5659  5698 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:05:45.545  5659  5698 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:05:45.545  5659  5698 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:05:45.545  5659  5698 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:05:45.545  5659  5698 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:05:45.545  5659  5698 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-26 18:05:45.545  5659  5698 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:05:45.546  5659  5698 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-26 18:05:45.637  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:05:45.640  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:05:45.644  5659  5659 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-26 18:05:46.086  5659  5706 W jxcore-log: Initializing JXcore engine
,10-26 18:05:46.086  5659  5706 W jxcore-log: JXcore engine is ready
,10-26 18:05:46.110  5706  5706 W Thread-58: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11798 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-26 18:05:46.110  5706  5706 W Thread-58: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13770]" dev="sockfs" ino=13770 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-26 18:05:46.110  5706  5706 W Thread-58: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1257 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-26 18:05:46.110  5706  5706 W Thread-58: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31982]" dev="sockfs" ino=31982 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-26 18:05:46.118  5659  5706 W jxcore-log: Starting JXcore engine
,10-26 18:05:46.169  5659  5706 W jxcore-log: Platform android
10-26 18:05:46.169  5659  5706 W jxcore-log: 
,10-26 18:05:46.169  5659  5706 W jxcore-log: Process ARCH arm
10-26 18:05:46.169  5659  5706 W jxcore-log: 
,10-26 18:05:46.351  5659  5706 I jxcore-log: JXcore Cordova bridge is ready!
10-26 18:05:46.351  5659  5706 I jxcore-log: 
,10-26 18:05:46.352  5659  5706 W jxcore-log: JXcore engine is started
,10-26 18:05:46.360  5659  5698 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-26 18:05:46.367  5659  5659 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-26 18:05:48.878  3577  3577 I ConfigService: onDestroy
,10-26 18:05:49.754   929  3594 I ActivityManager: Killing 5227:org.codeaurora.ims/1001 (adj 15): empty #17
,10-26 18:05:54.842  3936  5708 W CronetSyncConnectionRcs: Upload content type not set.
,10-26 18:05:55.355   929  2981 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 18:05:55.931  5659  5706 I jxcore-log: 2016-10-26 16:05:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-26 18:05:55.931  5659  5706 I jxcore-log: 
,10-26 18:05:55.932  5659  5706 I jxcore-log: 2016-10-26 16:05:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-26 18:05:55.932  5659  5706 I jxcore-log: 
,10-26 18:05:55.937  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:05:55.937  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:05:55.937  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:05:55.937  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:05:55.937  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:05:55.937  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:05:55.937  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:05:55.937  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:05:55.939  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 18:05:55.940  5659  5706 I jxcore-log: 2016-10-26 16:05:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-26 18:05:55.940  5659  5706 I jxcore-log: 
,10-26 18:05:55.942  5659  5706 I jxcore-log: 2016-10-26 16:05:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-26 18:05:55.942  5659  5706 I jxcore-log: 
,10-26 18:05:56.192  5659  5706 I jxcore-log: 2016-10-26 16:05:56 - DEBUG UnitTest_app: 'Running unit tests'
10-26 18:05:56.192  5659  5706 I jxcore-log: 
,10-26 18:05:56.192  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:05:56.192  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@687b82d added. We now have 2 listener(s)
10-26 18:05:56.193  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:05:56.193  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:05:56.193  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 18:05:56.193  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:05:56.193  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b55162 added. We now have 2 listener(s)
10-26 18:05:56.193  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:05:56.194  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 18:05:56.196  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 18:05:56.199  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:05:56.199  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:05:56.199  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:05:56.199  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:05:56.199  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:05:56.199  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:05:56.199  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:05:56.199  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:05:56.200  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 18:05:56.200  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:05:56.201  5659  5706 D executeNativeTests: Running unit tests
,10-26 18:05:56.207  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:05:56.213  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:05:56.236  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 18:05:56.236  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 added. We now have 3 listener(s)
10-26 18:05:56.236  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 18:05:56.236  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:05:56.236  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:05:56.236  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:05:56.236  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 added. We now have 3 listener(s)
,10-26 18:05:56.236  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 18:05:56.237  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 18:05:56.238  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:05:56.240  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:05:56.240  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:05:56.240  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:05:56.240  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:05:56.240  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:05:56.240  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:05:56.240  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:05:56.240  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:05:56.241  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:05:56.241  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-26 18:05:56.243  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 18:05:56.243  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-26 18:05:56.243  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-26 18:05:56.243  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 18:05:56.243  5659  5706 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-26 18:05:56.244  5659  5706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-26 18:05:56.244  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 18:05:56.244  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 18:05:56.244  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 18:05:56.244  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 18:05:56.244  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:05:56.244  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:05:56.244  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:05:56.244  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:05:56.244  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:05:56.244  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:05:56.245  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:05:56.245  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:05:56.245  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 removed from the list
10-26 18:05:56.245  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:05:56.245  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 removed from the list
10-26 18:05:56.246  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:05:56.255  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:05:56.256  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:05:56.256  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:05:56.256  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:05:56.256  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:05:56.257  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:05:56.257  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:05:56.257  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:05:56.257  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:05:56.257  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:05:56.257  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:05:56.257  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:05:56.257  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:05:56.258  5659  5706 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-26 18:05:56.259  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:05:56.259  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:05:56.259  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:05:56.259  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:05:56.259  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:05:56.259  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:05:56.259  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:05:56.259  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:05:56.259  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:05:56.259  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:05:56.259  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:05:56.259  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:05:56.259  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:05:56.259  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:05:56.259  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:05:56.259  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.260  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.260  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.260  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.260  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:05:56.260  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:05:56.260  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:05:56.260  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the l,ist
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-26 18:05:56.262  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-26 18:05:56.263  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:05:56.263  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:05:56.263  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:05:56.263  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:05:56.263  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:05:56.263  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:05:56.263  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:05:56.263  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:05:56.263  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:05:56.263  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:05:56.263  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:05:56.263  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:05:56.263  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:05:56.264  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:05:56.264  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:05:56.264  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.264  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.264  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.264  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.264  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:05:56.264  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:05:56.264  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:05:56.264  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:05:56.265  5659  5706 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-26 18:05:56.266  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:05:56.268  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:05:56.268  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:05:56.268  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:05:56.268  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:05:56.268  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:05:56.268  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:05:56.268  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:05:56.268  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:05:56.268  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:05:56.269  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:05:56.269  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 18:05:56.269  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 18:05:56.269  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 18:05:56.269  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:05:56.269  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 18:05:56.271  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:05:56.273  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 18:05:56.273  5659  5706 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 18:05:56.273  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 18:05:56.273  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:05:56.275  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 18:05:56.276  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 18:05:56.276  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 18:05:56.277  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-26 18:05:56.278  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-26 18:05:56.279  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.279  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 18:05:56.279  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 18:05:56.279  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 18:05:56.279  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 18:05:56.279  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.279  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:05:56.281  4572  4770 D BtGatt.GattService: registerClient() - UUID=a9e59e2c-d484-48d5-807c-1409aeef7dd5
10-26 18:05:56.282  4572  4635 D BtGatt.GattService: onClientRegistered() - UUID=a9e59e2c-d484-48d5-807c-1409aeef7dd5, clientIf=5
10-26 18:05:56.283  5659  5669 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 18:05:56.283  4572  4780 D BtGatt.GattService: start scan with filters
10-26 18:05:56.287  4572  4640 D BtGatt.ScanManager: handling starting scan
10-26 18:05:56.288  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 18:05:56.288  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.288  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 18:05:56.288  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.288  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.288  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 18:05:56.288  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 18:05:56.288  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.288  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.288  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 18:05:56.288  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.289  4572  4640 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
10-26 18:05:56.290  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.290  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:05:56.290  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.290  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.290  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:05:56.290  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.290  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 18:05:56.291  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 18:05:56.291  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.292  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.292  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.292  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:05:56.292  5659  5706 I io.jxcore.node.ConnectionHelper: start: OK
10-26 18:05:56.295  4572  4635 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 18:05:56.295  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:05:56.296  4572  4640 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 18:05:56.301  4572  4635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 18:05:56.301  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:05:56.302  4572  4640 D BtGatt.ScanManager: Starting BLE batch scan
10-26 18:05:56.302  4572  4640 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 18:05:56.312  4572  4635 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 18:05:56.312  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:05:56.317  4572  4635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 18:05:56.317  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 18:05:56.792  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-26 18:05:56.792  5659  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 18:05:56.792  5659  5659 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 18:05:59.706   929   929 I ActivityManager: Killing 5264:com.android.settings/1000 (adj 15): empty #17
,10-26 18:06:00.030   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:01.031   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:01.296  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 18:06:01.297  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:01.297  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 18:06:01.297  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:01.297  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 18:06:01.297  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:01.297  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-26 18:06:01.297  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 18:06:01.297  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-26 18:06:01.298  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 18:06:01.298  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.299  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.299  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-26 18:06:01.301  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:06:01.302  4572  4584 D BtGatt.GattService: stopScan() - queue size =1
,10-26 18:06:01.304  4572  4779 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 18:06:01.305  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-26 18:06:01.305  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.306  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 18:06:01.307  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:01.307  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.307  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-26 18:06:01.307  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 18:06:01.308  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:01.308  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.308  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-26 18:06:01.308  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.309  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.309  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:06:01.309  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.310  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.310  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.310  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.310  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.310  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 18:06:01.310  4572  4572 D BtGatt.ScanManager: awakened up at time 85126
10-26 18:06:01.310  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.310  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.311  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.311  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 18:06:01.311  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-26 18:06:01.320  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-26 18:06:01.321  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:01.342  4572  4635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-26 18:06:01.342  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:01.343  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.343  4572  4640 D BtGatt.ScanManager: stopping BLe Batch
,10-26 18:06:01.343  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.343  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:01.343  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:01.343  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:01.343  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:06:01.343  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:01.343  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:01.343  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:01.343  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:01.343  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:01.343  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:01.344  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-26 18:06:01.345  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:06:01.345  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-26 18:06:01.350  4572  4635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-26 18:06:01.350  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:01.351  4572  4640 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 18:06:01.370  4572  4635 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,10-26 18:06:01.370  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:01.370  4572  4635 D BtGatt.GattService: current time is 85186088060
10-26 18:06:01.370  4572  4635 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -81, 95, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -76, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -82, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-26 18:06:01.372  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-26 18:06:01.372  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-26 18:06:01.372  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-26 18:06:01.373  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-26 18:06:01.423  4756  4802 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,10-26 18:06:01.424  4756  4756 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,10-26 18:06:01.846  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 18:06:02.032   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:03.033   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:04.034   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:05.035   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-26 18:06:06.345  5659  5706 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-26 18:06:06.350  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 18:06:06.361  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:06:06.361  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:06.361  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:06.361  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:06.361  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:06:06.361  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:06.361  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:06:06.361  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:06:06.366  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 18:06:06.366  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:06:06.366  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 18:06:06.366  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 18:06:06.367  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 18:06:06.367  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:06:06.367  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 18:06:06.373  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:06.375  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 18:06:06.375  5659  5706 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 18:06:06.375  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-26 18:06:06.381  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:06.384  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 18:06:06.386  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-26 18:06:06.386  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 18:06:06.392  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.392  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 18:06:06.392  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 18:06:06.392  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 18:06:06.392  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 18:06:06.392  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.393  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:06:06.395  4572  4770 D BtGatt.GattService: registerClient() - UUID=35467d22-8f47-43d3-91b1-ce783d8e7656
,10-26 18:06:06.396  4572  4635 D BtGatt.GattService: onClientRegistered() - UUID=35467d22-8f47-43d3-91b1-ce783d8e7656, clientIf=5
,10-26 18:06:06.396  5659  5670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-26 18:06:06.397  4572  4587 D BtGatt.GattService: start scan with filters
,10-26 18:06:06.400  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 18:06:06.400  4572  4640 D BtGatt.ScanManager: handling starting scan
10-26 18:06:06.401  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.401  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-26 18:06:06.401  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.401  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.401  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 18:06:06.401  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 18:06:06.401  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.401  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.401  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-26 18:06:06.401  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.405  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.405  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:06:06.405  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.405  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.405  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.405  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:06:06.405  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 18:06:06.407  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 18:06:06.407  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.409  4572  4635 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-26 18:06:06.409  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:06.410  4572  4640 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-26 18:06:06.410  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.411  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.411  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.411  5659  5706 I io.jxcore.node.ConnectionHelper: start: OK
10-26 18:06:06.413  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:06.413  5659  5706 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-26 18:06:06.413  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:06.413  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 18:06:06.413  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:06.413  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 18:06:06.413  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:06.414  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 18:06:06.414  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 18:06:06.414  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 18:06:06.414  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 18:06:06.414  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.414  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.414  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 18:06:06.415  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:06:06.415  4572  4779 D BtGatt.GattService: stopScan() - queue size =1
,10-26 18:06:06.417  4572  4780 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 18:06:06.417  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-26 18:06:06.418  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.418  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 18:06:06.418  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.418  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.418  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 18:06:06.418  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 18:06:06.418  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.418  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.419  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 18:06:06.419  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.419  4572  4635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 18:06:06.419  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:06.420  4572  4640 D BtGatt.ScanManager: Starting BLE batch scan
10-26 18:06:06.420  4572  4640 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 18:06:06.420  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.421  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:06:06.421  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.421  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.421  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.421  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.421  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.421  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 18:06:06.421  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.421  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.422  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.422  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 18:06:06.422  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 18:06:06.422  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:06:06.422  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.423  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.423  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.423  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.423  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:06.423  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:06.423  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:06:06.424  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:06.424  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
,10-26 18:06:06.424  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:06.424  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:06.424  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:06.424  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:06:06.424  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:06.424  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:06:06.424  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:06:06.424  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:06.425  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:06.425  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.426  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.426  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.426  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.426  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:06.426  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:06.426  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 18:06:06.427  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
,10-26 18:06:06.428  5659  5706 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-26 18:06:06.431  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 18:06:06.432  4572  4635 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 18:06:06.432  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 18:06:06.435  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:06:06.435  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:06.435  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:06.435  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:06.435  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:06:06.435  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:06.435  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:06:06.435  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:06:06.437  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:06.437  4572  4635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 18:06:06.437  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:06.438  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:06:06.438  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 18:06:06.438  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 18:06:06.438  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 18:06:06.438  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:06:06.438  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-26 18:06:06.441  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 18:06:06.441  5659  5706 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-26 18:06:06.441  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 18:06:06.441  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:06.444  4572  4635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 18:06:06.444  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:06.444  4572  4640 D BtGatt.ScanManager: stopping BLe Batch
,10-26 18:06:06.445  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:06.446  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 18:06:06.446  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 18:06:06.446  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 18:06:06.449  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.449  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 18:06:06.450  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 18:06:06.450  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 18:06:06.450  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 18:06:06.450  4572  4635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 18:06:06.450  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.450  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:06.450  4572  4640 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 18:06:06.450  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:06:06.452  4572  4779 D BtGatt.GattService: registerClient() - UUID=2fa97c5c-255e-481c-9ca9-e7584d5fc6c8
10-26 18:06:06.453  4572  4635 D BtGatt.GattService: onClientRegistered() - UUID=2fa97c5c-255e-481c-9ca9-e7584d5fc6c8, clientIf=5
,10-26 18:06:06.453  5659  5670 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 18:06:06.453  4572  4770 D BtGatt.GattService: start scan with filters
,10-26 18:06:06.455  4572  4635 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-26 18:06:06.456  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 18:06:06.459  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-26 18:06:06.459  4572  4640 D BtGatt.ScanManager: handling starting scan
10-26 18:06:06.459  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.459  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 18:06:06.459  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.459  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.459  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 18:06:06.459  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-26 18:06:06.459  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.459  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.459  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 18:06:06.459  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.462  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.462  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:06:06.462  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.462  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.462  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:06:06.462  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.462  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 18:06:06.464  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 18:06:06.464  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.464  4572  4635 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 18:06:06.464  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 18:06:06.464  4572  4640 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-26 18:06:06.466  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.466  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:06.466  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:06.466  5659  5706 I io.jxcore.node.ConnectionHelper: start: OK
,10-26 18:06:06.469  4572  4635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-26 18:06:06.469  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:06.469  4572  4640 D BtGatt.ScanManager: Starting BLE batch scan
10-26 18:06:06.469  4572  4640 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 18:06:06.478  4572  4635 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-26 18:06:06.478  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 18:06:06.483  4572  4635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 18:06:06.483  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 18:06:06.964  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-26 18:06:06.964  5659  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 18:06:06.965  5659  5659 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 18:06:06.987  4572  4572 D BtGatt.ScanManager: awakened up at time 90802
,10-26 18:06:06.989  4572  4640 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 18:06:06.991   929  3790 I ActivityManager: Killing 4948:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,10-26 18:06:07.036  4572  4635 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,10-26 18:06:07.036  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:07.037  4572  4635 D BtGatt.GattService: current time is 90852537739
,10-26 18:06:07.037  4572  4635 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -90, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-26 18:06:07.037  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-26 18:06:07.037  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-26 18:06:07.037  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,10-26 18:06:07.042  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
10-26 18:06:07.043  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-26 18:06:07.043  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-90, mTimestampNanos=90702789302}
10-26 18:06:07.043  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-26 18:06:07.044  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=90452789302}
10-26 18:06:07.044  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-26 18:06:07.044  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=90402789302}
,10-26 18:06:11.467  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 18:06:11.467  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-26 18:06:11.467  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-26 18:06:11.468  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:11.468  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 18:06:11.468  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:11.468  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 18:06:11.468  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 18:06:11.468  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 18:06:11.468  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 18:06:11.469  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.469  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.469  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-26 18:06:11.472  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:06:11.474  4572  4770 D BtGatt.GattService: stopScan() - queue size =1
10-26 18:06:11.475  4572  4584 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 18:06:11.476  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 18:06:11.477  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:11.477  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 18:06:11.477  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.477  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.477  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-26 18:06:11.478  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 18:06:11.478  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.478  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.478  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 18:06:11.478  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.481  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:11.482  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:06:11.482  4572  4572 D BtGatt.ScanManager: awakened up at time 95297
10-26 18:06:11.482  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.482  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.482  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.483  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.483  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.483  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-26 18:06:11.483  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.483  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.484  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.484  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 18:06:11.484  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 18:06:11.486  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:06:11.486  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.488  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.488  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.488  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:11.488  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:06:11.488  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:06:11.488  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:06:11.489  4572  4635 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 18:06:11.489  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:11.489  4572  4640 D BtGatt.ScanManager: stopping BLe Batch
,10-26 18:06:11.496  4572  4635 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-26 18:06:11.496  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:11.496  4572  4640 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 18:06:11.508  4572  4635 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,10-26 18:06:11.508  4572  4635 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:06:11.508  4572  4635 D BtGatt.GattService: current time is 95323765254
10-26 18:06:11.508  4572  4635 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -76, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-26 18:06:11.508  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-26 18:06:11.509  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-26 18:06:11.509  4572  4635 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-26 18:06:11.989  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
10-26 18:06:11.989  5659  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 18:06:11.990  5659  5659 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 18:06:15.593   929  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-26 18:06:16.489  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 18:06:16.490  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:16.490  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:06:16.490  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.490  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:16.490  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:06:16.491  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.491  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:16.491  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.491  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
,10-26 18:06:16.491  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:16.492  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:16.493  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:16.494  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:16.494  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.499  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.499  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.499  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.499  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:16.499  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:16.499  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.500  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.501  5659  5706 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-26 18:06:16.503  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 18:06:16.503  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:16.503  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:06:16.503  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.503  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:16.504  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.504  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.504  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:16.504  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.504  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.504  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:06:16.505  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.505  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.505  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.505  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:16.505  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.508  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.508  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.508  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.508  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:16.508  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 18:06:16.509  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.509  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.511  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-26 18:06:16.511  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:16.511  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 18:06:16.512  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:06:16.512  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.512  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.512  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.512  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 18:06:16.512  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:16.512  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.512  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.513  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:16.513  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:16.513  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.513  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.513  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.513  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.517  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.517  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.517  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.517  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 18:06:16.518  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:16.518  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 18:06:16.518  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.520  5659  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-26 18:06:16.521  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:16.521  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:16.521  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 18:06:16.522  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.522  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.522  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.522  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.522  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
,10-26 18:06:16.522  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.522  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.522  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:16.523  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:16.523  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.523  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.523  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.523  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.527  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.527  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.528  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.528  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:16.528  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:16.528  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.529  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
,10-26 18:06:16.530  5659  5706 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-26 18:06:16.531  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 18:06:16.532  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:16.532  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 18:06:16.532  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.532  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.532  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.532  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.532  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
,10-26 18:06:16.533  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.533  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.533  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:16.533  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:16.533  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.533  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.533  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.534  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.536  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.536  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.536  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.536  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:16.536  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:16.537  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.537  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
,10-26 18:06:16.539  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 18:06:16.539  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 18:06:16.539  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 18:06:16.539  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 18:06:16.539  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 18:06:16.540  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-26 18:06:16.540  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 18:06:16.540  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 18:06:16.540  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 18:06:16.540  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:16.540  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:16.540  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 18:06:16.540  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.540  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.541  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.541  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.541  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:16.541  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.541  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.541  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:16.541  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.541  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.543  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.543  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.543  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.547  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.547  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.547  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.547  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:16.547  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 18:06:16.547  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.548  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
,10-26 18:06:16.549  5659  5706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 18:06:16.549  5659  5706 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 18:06:16.549  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-26 18:06:16.554  5659  5706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 18:06:16.554  5659  5706 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-26 18:06:16.554  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-26 18:06:16.554  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-26 18:06:16.554  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-26 18:06:16.554  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 18:06:16.555  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 18:06:16.556  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-26 18:06:16.556  5659  5706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-26 18:06:16.557  5659  5706 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 18:06:16.557  5659  5706 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-26 18:06:16.557  5659  5706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 18:06:16.557  5659  5706 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 18:06:16.557  5659  5706 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-26 18:06:16.557  5659  5706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 18:06:16.557  5659  5706 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 18:06:16.557  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-26 18:06:16.560  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-26 18:06:16.561  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-26 18:06:16.561  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-26 18:06:16.562  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-26 18:06:16.562  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-26 18:06:16.562  5659  5706 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-26 18:06:16.562  5659  5706 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-26 18:06:16.563  5659  5706 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,10-26 18:06:16.563  5659  5716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 122)
10-26 18:06:16.563  5659  5716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-26 18:06:16.563  5659  5716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-26 18:06:16.563  5659  5716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-26 18:06:16.564  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:16.564  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:16.564  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:06:16.564  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.564  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.564  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:16.564  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.564  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-26 18:06:16.566  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:16.566  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.566  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.566  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:16.566  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.566  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.566  5659  5716 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-26 18:06:16.566  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.566  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.566  5659  5716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 18:06:16.566  5659  5717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 122
10-26 18:06:16.566  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.566  5659  5717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 122)
10-26 18:06:16.567  5659  5717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 122)
,10-26 18:06:16.568  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.567  4587  4587 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34877]" dev="sockfs" ino=34877 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 18:06:16.567  4587  4587 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[34877]" dev="sockfs" ino=34877 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 18:06:16.568  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.569  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.569  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:16.569  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:16.569  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.569  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.569  5659  5716 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
10-26 18:06:16.570  5659  5706 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-26 18:06:16.569  5659  5716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-26 18:06:16.570  5659  5716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 122)
10-26 18:06:16.571  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:16.571  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 18:06:16.571  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:06:16.571  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.571  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.571  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.572  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.572  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:16.572  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.572  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.572  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:06:16.572  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.572  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.572  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.572  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.572  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.574  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.574  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.574  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.574  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:16.574  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:16.574  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.574  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.575  5659  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-26 18:06:16.575  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:16.575  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:16.575  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 18:06:16.575  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.575  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.575  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.575  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.576  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:16.576  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.576  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.576  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:06:16.576  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.576  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.576  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.576  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.576  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.577  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.577  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.577  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.577  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:16.577  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:16.577  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.577  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.578  5659  5706 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-26 18:06:16.578  5659  5706 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-26 18:06:16.578  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 18:06:16.578  5659  5706 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,10-26 18:06:16.578  5659  5706 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-26 18:06:16.578  5659  5706 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-26 18:06:16.578  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 18:06:16.578  5659  5706 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-26 18:06:16.578  5659  5706 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-26 18:06:16.579  5659  5706 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 18:06:16.579  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 18:06:16.579  5659  5706 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-26 18:06:16.579  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:16.579  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:16.579  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 18:06:16.579  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.579  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.579  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.579  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.579  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:16.579  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.579  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.579  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:16.579  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.579  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.579  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.579  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:16.580  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:16.581  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.581  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.581  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:16.581  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 18:06:16.581  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:16.581  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.581  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.582  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:16.582  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.582  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:16.582  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:16.582  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:16.582  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:16.582  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:16.582  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:16.582  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:16.583  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:18.620   929  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-26 18:06:21.583  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 18:06:21.584  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:21.584  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:21.584  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.584  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.584  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 18:06:21.585  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
,10-26 18:06:21.585  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 18:06:21.585  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:21.585  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 18:06:21.585  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:21.586  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.586  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.586  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 18:06:21.586  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:21.586  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.586  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
,10-26 18:06:21.587  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:21.587  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:21.587  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.587  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.587  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:21.587  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.592  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.593  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:21.593  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.594  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:21.594  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:21.594  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 18:06:21.594  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
,10-26 18:06:21.600  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-26 18:06:21.602  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 18:06:21.604  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-26 18:06:21.607  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-26 18:06:21.607  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-26 18:06:21.607  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-26 18:06:21.607  5659  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-26 18:06:21.608  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-26 18:06:21.608  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 18:06:21.608  5659  5659 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-26 18:06:21.608  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:21.609  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-26 18:06:21.609  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-26 18:06:21.610  4584  4584 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[35844]" dev="sockfs" ino=35844 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-26 18:06:21.610  4584  4584 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[35844]" dev="sockfs" ino=35844 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 18:06:21.609  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-26 18:06:21.609  5659  5718 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 18:06:21.609  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.609  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-26 18:06:21.609  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-26 18:06:21.609  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:21.609  5659  5659 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-26 18:06:21.609  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.610  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 18:06:21.610  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 18:06:21.610  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 18:06:21.610  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.610  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.610  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.612  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.612  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:06:21.613  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.613  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.613  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:21.613  5659  5718 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-26 18:06:21.613  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:06:21.613  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:21.613  5659  5718 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-26 18:06:21.613  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:06:21.613  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:21.613  5659  5718 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was ,explicitly stopped: true
10-26 18:06:21.613  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:06:21.613  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:06:21.613  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:21.614  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.614  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.614  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-26 18:06:21.614  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:21.614  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.614  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:21.614  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:21.614  5659  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-26 18:06:21.614  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.615  5659  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:21.615  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.615  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.615  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.615  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.617  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.617  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:21.618  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.618  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:21.618  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:21.618  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.618  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:21.622  5659  5706 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-26 18:06:21.622  5659  5706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-26 18:06:21.622  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-26 18:06:21.622  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 18:06:21.622  5659  5706 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 18:06:21.623  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:21.623  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:21.623  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:06:21.623  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:21.623  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.623  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.623  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 18:06:21.623  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:21.623  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.623  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:21.623  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:21.623  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.624  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.624  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:21.624  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.624  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.626  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.626  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.626  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.626  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:21.626  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:21.626  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.626  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
,10-26 18:06:21.631  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 18:06:21.631  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:21.631  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:06:21.632  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:21.632  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.632  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.632  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:06:21.632  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:21.632  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.632  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:21.632  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:06:21.632  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.632  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.632  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.632  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.632  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:06:21.634  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.634  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.635  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.635  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:21.635  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:21.635  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.635  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
,10-26 18:06:21.636  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:06:21.636  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:06:21.636  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:06:21.636  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:06:21.636  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.636  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.636  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 18:06:21.636  5659  5706 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@89120e0 not in the list
10-26 18:06:21.636  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.636  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:21.637  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:21.637  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:21.637  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.637  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:21.637  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:21.637  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.639  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.639  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.639  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:06:21.639  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:06:21.639  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:06:21.639  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:21.639  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f6f99 not in the list
10-26 18:06:21.640  5659  5706 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-26 18:06:21.640  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 18:06:21.641  5659  5706 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-26 18:06:21.641  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-26 18:06:21.641  5659  5706 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-26 18:06:21.641  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-26 18:06:21.643  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-26 18:06:21.643  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-26 18:06:21.644  5659  5706 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-26 18:06:21.644  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-26 18:06:21.644  5659  5706 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-26 18:06:21.644  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-26 18:06:21.644  5659  5706 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-26 18:06:21.644  5659  5706 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-26 18:06:21.644  5659  5706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-26 18:06:21.644  5659  5706 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-26 18:06:21.645  5659  5706 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-26 18:06:21.645  5659  5706 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-26 18:06:21.645  5659  5706 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-26 18:06:21.645  5659  5706 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-26 18:06:21.646  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:06:21.646  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@975a6d3 added. We now have 3 listener(s)
10-26 18:06:21.646  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:06:21.647  5659  5706 D BluetoothAdapter: enable(): BT is already enabled..!
10-26 18:06:21.648   929   940 D WifiService: setWifiEnabled: true pid=5659, uid=10077
10-26 18:06:21.648   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 18:06:21.697  4572  4754 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
10-26 18:06:21.698  4572  4768 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,10-26 18:06:22.114  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 18:06:22.369   929  5357 D NetlinkSocketObserver: NeighborEvent{elapsedMs=106184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-26 18:06:26.653  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 18:06:26.654  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1e8210 added. We now have 4 listener(s)
,10-26 18:06:26.654  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 18:06:26.667  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 18:06:26.667  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1e8210 removed from the list
,10-26 18:06:26.667  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:06:26.667  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:06:26.668  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:26.669  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:06:26.670  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fe7109 added. We now have 4 listener(s)
10-26 18:06:26.670  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 18:06:26.673  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 18:06:26.674  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fe7109 removed from the list
,10-26 18:06:26.674  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:06:26.674  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:26.674  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:26.676  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:06:26.676  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2bd0f0e added. We now have 4 listener(s)
,10-26 18:06:26.676  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 18:06:26.681   929   939 D WifiService: setWifiEnabled: false pid=5659, uid=10077
,10-26 18:06:26.681   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 18:06:26.686   929  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-26 18:06:26.687   929  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-26 18:06:26.687   929  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 18:06:26.687   929  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 18:06:26.697  4572  4631 D BluetoothAdapterState: Current state: ON, message: 23
10-26 18:06:26.697  4572  4631 D BluetoothAdapterProperties: Setting state to 13
10-26 18:06:26.697  4572  4631 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-26 18:06:26.698  4572  4631 D BluetoothAdapterProperties: onBluetoothDisable()
10-26 18:06:26.700  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:06:26.700  4572  4631 I BluetoothAdapterState: Entering PendingCommandState
,10-26 18:06:26.704  4572  4635 D BluetoothAdapterProperties: Scan Mode:20
,10-26 18:06:26.707   929  5358 D DhcpClient: Clearing IP address
,10-26 18:06:26.707  4572  4631 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-26 18:06:26.708   510   924 D CommandListener: Clearing all IP addresses on wlan0
10-26 18:06:26.708  4572  4572 D BluetoothMapService: onReceive
,10-26 18:06:26.708  4572  4572 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 18:06:26.708  4572  4572 D BluetoothMapService: STATE_TURNING_OFF
10-26 18:06:26.709  4572  4572 D BluetoothMapService: MAP Service closeService in
10-26 18:06:26.709  4572  4572 D BluetoothMapMasInstance0: MAP Service shutdown
10-26 18:06:26.709  4572  4572 D ObexServerSockets0: shutdown(block = true)
10-26 18:06:26.710  4572  4572 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 18:06:26.710  4572  4572 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 18:06:26.710  4572  4783 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-26 18:06:26.710  4572  4768 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-26 18:06:26.710  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.711  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:06:26.711  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.711  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.711  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:26.711  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.711  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:26.711  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:06:26.711  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:06:26.712  4572  4784 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-26 18:06:26.712  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.712  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:26.712  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:06:26.714  4572  4572 I BtOppRfcommListener: stopping Accept Thread
,10-26 18:06:26.715  4572  5286 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 18:06:26.715  4572  5286 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-26 18:06:26.716   510   924 D CommandListener: Setting iface cfg
10-26 18:06:26.718  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:26.721  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:26.723   929  5359 D DhcpClient: Receive thread stopped
10-26 18:06:26.727  3577  5412 V NativeCrypto: Read error: ssl=0x7f6ca56000: I/O error during system call, Connection timed out
10-26 18:06:26.728  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.728  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.728  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.728  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.728  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:26.728  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.728  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:26.728  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:06:26.728  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:06:26.729  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.729  3577  5412 V NativeCrypto: SSL shutdown failed: ssl=0x7f6ca56000: I/O error during system call, Broken pipe
10-26 18:06:26.729  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:26.731   929  3183 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-26 18:06:26.731   929  5356 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-26 18:06:26.733  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.733  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.733  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.733  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.733  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:26.733  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.733  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:26.733  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:06:26.733  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:06:26.734  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.734  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:26.734   929  5356 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-26 18:06:26.735   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-26 18:06:26.735   929  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-26 18:06:26.736   929   942 I ActivityManager: Start proc 5722:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-26 18:06:26.737   929  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-26 18:06:26.738  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:26.739   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-26 18:06:26.739   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,10-26 18:06:26.742   536   536 E Parcel  : Reading a NULL string not supported here.
10-26 18:06:26.742  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.742  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.742  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.742  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.742  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:26.742  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.742  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:26.742  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:06:26.742  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:06:26.743  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 18:06:26.743  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:06:26.745   929   929 D RttService: SCAN_AVAILABLE : 1
10-26 18:06:26.745   929  3036 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-26 18:06:26.745  4572  4572 D HeadsetService: Received stop request...Stopping profile...
10-26 18:06:26.747  3122  3133 D BluetoothHeadset: Proxy object disconnected
10-26 18:06:26.747  4572  4572 D A2dpService: Received stop request...Stopping profile...
10-26 18:06:26.747  3754  3785 D BluetoothHeadset: Proxy object disconnected
,10-26 18:06:26.748  4572  4773 D A2dpStateMachine: Exit Disconnected: -1
10-26 18:06:26.748   929   929 D BluetoothHeadset: Proxy object disconnected
10-26 18:06:26.748   929   929 D BluetoothHeadset: Proxy object disconnected
,10-26 18:06:26.748   929   929 D BluetoothHeadset: Proxy object disconnected
10-26 18:06:26.748  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.749  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.749  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.749  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.749  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:26.749  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.749  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:26.749  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:26.749  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:06:26.749   929   929 D BluetoothA2dp: Proxy object disconnected
10-26 18:06:26.750  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.750  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:26.750  4572  4572 D HidService: Received stop request...Stopping profile...
,10-26 18:06:26.753  4572  4572 D HidService: Stopping Bluetooth HidService
10-26 18:06:26.754  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.754  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.754  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.754  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.754  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:26.754  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.754  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:26.754  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:26.754  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:06:26.754  3122  3122 D HeadsetProfile: Bluetooth service disconnected
10-26 18:06:26.754  3122  3122 D BluetoothA2dp: Proxy object disconnected
10-26 18:06:26.754  3122  3122 D BluetoothInputDevice: Proxy object disconnected
10-26 18:06:26.755  3122  3122 D HidProfile: Bluetooth service disconnected
,10-26 18:06:26.755  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 18:06:26.755  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:26.756   929  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-26 18:06:26.757  4572  4572 D HealthService: Received stop request...Stopping profile...
,10-26 18:06:26.757  3714  3839 W QCNEJ   : |CORE| network lost: 100
,10-26 18:06:26.758  3714  3839 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-26 18:06:26.761  4572  4572 V BluetoothAdapterState: isTurningOff()=true
,10-26 18:06:26.761  4572  4572 V BluetoothAdapterState: isTurningOn()=false
,10-26 18:06:26.761  4572  4572 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:26.761  4572  4572 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:26.764  4572  4572 D PanService: Received stop request...Stopping profile...
10-26 18:06:26.765  3122  3122 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-26 18:06:26.765  3122  3122 D PanProfile: Bluetooth service disconnected
,10-26 18:06:26.769  4572  4572 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-26 18:06:26.769  4572  4572 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 18:06:26.770  4572  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 18:06:26.770  4572  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 18:06:26.770  4572  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 18:06:26.770  4572  4635 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 18:06:26.770  4572  4635 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-26 18:06:26.770   929  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-26 18:06:26.771  4572  4572 D BluetoothMapService: Received stop request...Stopping profile...
10-26 18:06:26.771  4572  4572 D BluetoothMapService: stop()
10-26 18:06:26.773  4572  4572 D BluetoothMapAppObserver: deinitObservers()
10-26 18:06:26.773  4572  4572 D BluetoothMapAppObserver: removeReceiver()
,10-26 18:06:26.775  4572  4572 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:26.775  4572  4572 V BluetoothAdapterState: isTurningOn()=false
,10-26 18:06:26.775  4572  4572 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 18:06:26.775  4572  4572 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 18:06:26.776  4572  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 18:06:26.776  4572  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 18:06:26.776  4572  4635 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-26 18:06:26.776  4572  4754 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-26 18:06:26.776  3122  3122 D BluetoothMap: Proxy object disconnected
10-26 18:06:26.776  4572  4754 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 18:06:26.776  3122  3122 D MapProfile: Bluetooth service disconnected
10-26 18:06:26.776  4572  4754 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 18:06:26.777  4572  4754 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 18:06:26.777  4572  4572 D SapService: Received stop request...Stopping profile...
10-26 18:06:26.777  4572  4572 V SapService: stop()
10-26 18:06:26.778  4572  4572 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:26.778  4572  4572 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:26.778  4572  4572 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 18:06:26.778  4572  4572 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:26.778  4572  4572 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 18:06:26.778  4572  4572 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-26 18:06:26.778  4572  4572 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:26.778  4572  4635 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 18:06:26.779  4572  4572 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:26.779  4572  4572 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:26.779  4572  4572 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:26.779  4572  4572 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,10-26 18:06:26.779  4572  4635 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-26 18:06:26.781  4572  4572 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 18:06:26.781  4572  4572 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:26.781  4572  4572 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:26.781  4572  4572 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:26.781  4572  4572 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:26.781  4572  4572 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 18:06:26.781  4572  4572 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 18:06:26.782  4572  4572 D BluetoothMapService: MAP Service closeService in
,10-26 18:06:26.782  4572  4572 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:26.782  4572  4572 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:26.782  4572  4572 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:26.782  4572  4572 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:26.782  4572  4572 D BluetoothMapService: cleanup()
10-26 18:06:26.782  4572  4572 D BluetoothMapService: MAP Service closeService in
10-26 18:06:26.782  4572  4572 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:26.782  4572  4572 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:26.782  4572  4572 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 18:06:26.782  4572  4572 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:26.783  4572  4631 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 18:06:26.783  4572  4631 D BluetoothAdapterProperties: Setting state to 15
10-26 18:06:26.783  4572  4631 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-26 18:06:26.783  3122  3990 D BluetoothMap: onBluetoothStateChange: up=false
10-26 18:06:26.784  4572  4631 I BluetoothAdapterState: Entering BleOnState
10-26 18:06:26.784  3122  3133 D BluetoothPan: onBluetoothStateChange on: false
,10-26 18:06:26.785   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 18:06:26.785  3122  3135 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 18:06:26.786   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-26 18:06:26.786  3754  4021 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 18:06:26.787  3122  3990 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 18:06:26.787  3122  3133 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 18:06:26.788   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 18:06:26.788   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 18:06:26.788  3122  3135 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-26 18:06:26.789   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 18:06:26.789   929  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 18:06:26.789  4572  4631 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-26 18:06:26.789  4572  4631 D BluetoothAdapterProperties: Setting state to 16
10-26 18:06:26.789  4572  4631 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-26 18:06:26.790  4572  4631 D BluetoothAdapterProperties: onBleDisable
10-26 18:06:26.790  4572  4631 I BluetoothAdapterState: Entering PendingCommandState
10-26 18:06:26.790  4572  4632 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-26 18:06:26.791  4572  4754 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-26 18:06:26.791  4572  4754 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 18:06:26.791  4572  4635 D BluetoothAdapterProperties: Scan Mode:20
10-26 18:06:26.792  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.792  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.792  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.792  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.792  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:26.792  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.792  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:26.792  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:26.792  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:26.793  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.793  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.793  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.793  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.793  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:26.793  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.793  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:26.793  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:26.793  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:26.796  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.796  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.796  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.796  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.796  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:26.796  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.796  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:26.796  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:26.796  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:26.797  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:26.798  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:26.799  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:26.803  5722  5722 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-26 18:06:26.814   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-26 18:06:26.814   510   924 D CommandListener: Clearing all IP addresses on wlan0
,10-26 18:06:26.815   929  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-26 18:06:26.815   929  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 18:06:26.816   929   946 D Tethering: MasterInitialState.processMessage what=3
,10-26 18:06:26.818   929  2981 D DhcpClient: doQuit
,10-26 18:06:26.818   929  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-26 18:06:26.819  3442  3442 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-26 18:06:26.819   929  5358 D DhcpClient: onQuitting
,10-26 18:06:26.819  5241  5241 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@797b5ca and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-26 18:06:26.821  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.821  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.821  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.821  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.821  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:26.821  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.821  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:26.821  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:26.821  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:26.822  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.822  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:06:26.824  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.824  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.824  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.824  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.824  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:26.824  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.824  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:26.824  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:26.824  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 18:06:26.825  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.825  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:26.827  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.827  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:26.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:26.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:26.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:26.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:26.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:26.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:26.827  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:26.827  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:26.827  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:06:26.829  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:26.830  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:26.831  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:26.835  3936  3936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-26 18:06:26.837  4926  4947 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 18:06:26.837  4926  4947 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 18:06:26.837  4926  4947 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-26 18:06:26.837  4926  4947 E SarControlService: no key has been found,reset the power
10-26 18:06:26.837  4926  4972 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 18:06:26.837  4926  4972 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 18:06:26.837  4926  4972 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 18:06:26.838  4960  4960 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 18:06:26.838  4960  4960 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 18:06:26.839  4926  4972 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 18:06:26.839  4926  4972 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 18:06:26.839  4926  4972 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 18:06:26.839  4960  4960 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 18:06:26.839  4960  4960 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-26 18:06:26.845  4960  4974 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6dc0680 HexData = [00000000ea03000000000000ffffffff]
,10-26 18:06:26.845  4960  4974 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 18:06:26.845  4960  4974 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-26 18:06:26.845  4960  4960 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 18:06:26.845  4926  4936 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-26 18:06:26.849  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 18:06:26.852  4960  4974 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6dc0680 HexData = [00000000eb03000000000000ffffffff]
10-26 18:06:26.852  4960  4974 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 18:06:26.852  4960  4974 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-26 18:06:26.852  4960  4960 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 18:06:26.853  4926  4937 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 18:06:26.853  3442  3442 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-26 18:06:26.856  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 18:06:26.857   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d45dabd:true
10-26 18:06:26.859  3442  3442 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-26 18:06:26.873   929   940 I ActivityManager: Start proc 5743:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
10-26 18:06:26.873   510   924 E Netd    : netlink response contains error (No such file or directory)
10-26 18:06:26.874   929  2983 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-26 18:06:26.875   929  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-26 18:06:26.880  5722  5722 D LocalBluetoothProfileManager: Adding local MAP profile
10-26 18:06:26.885  5722  5722 D BluetoothMap: Create BluetoothMap proxy object
10-26 18:06:26.887  3442  3442 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-26 18:06:26.899  5722  5722 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-26 18:06:26.911  3442  3442 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-26 18:06:26.914  5722  5722 D DockEventReceiver: finishStartingService: stopping service
,10-26 18:06:26.916  5743  5743 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-26 18:06:26.922   929  3800 I ActivityManager: Killing 5384:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-26 18:06:26.998  4572  4635 I bt_hci  : shut_down
,10-26 18:06:27.002  4572  4642 D bt_hwcfg: hw_epilog_process
,10-26 18:06:27.002  4572  4642 I bt_vendor: low_power_mode_cb
,10-26 18:06:27.005  4572  4642 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-26 18:06:27.005  4572  4642 I bt_vendor: epilog_cb
10-26 18:06:27.005  4572  4642 I bt_hci  : epilog_finished_callback
,10-26 18:06:27.007  4572  4635 I bt_hci_h4: hal_close
10-26 18:06:27.007  4572  4635 I bt_userial_vendor: device fd = 54 close
,10-26 18:06:27.013   929  2981 D wifi    : In wifi stop Hal
,10-26 18:06:27.013  4414  4414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 18:06:27.013   929  2981 D wifi    : halHandle = 0x7f6b504080, mVM = 0x7f87acd140, mCls = 0x100a02
10-26 18:06:27.013   929  3441 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-26 18:06:27.013   929  3441 D WifiHAL : Got a signal to exit!!!
10-26 18:06:27.013   929  3441 I WifiHAL : Exit wifi_event_loop
10-26 18:06:27.014   929  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
10-26 18:06:27.014   929  2981 E WifiHAL : Event processing terminated
,10-26 18:06:27.014   929  2981 D wifi    : In wifi cleaned up handler
10-26 18:06:27.014   929  2981 I WifiHAL : Internal cleanup completed
10-26 18:06:27.015  3690  4172 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 18:06:27.016  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:27.018  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:27.019  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:27.038   929  3441 D wifi    : set interface wlan0 flags (DOWN)
,10-26 18:06:27.038   929  2981 D WifiNative-HAL: HAL event thread stopped successfully
,10-26 18:06:27.099   510   924 E Netd    : netlink response contains error (No such file or directory)
,10-26 18:06:27.110  5743  5743 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at java.io.File.exists(File.java:361)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 18:06:27.110  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-26 18:06:27.111  5743  5743 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 18:06:27.112  4572  4632 D bt_stack_manager: event_shut_down_stack finished.
10-26 18:06:27.113  4572  4631 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-26 18:06:27.114  4572  4631 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-26 18:06:27.114  4572  4572 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 18:06:27.115  4572  4572 D BtGatt.GattService: Received stop request...Stopping profile...
,10-26 18:06:27.115  4572  4572 D BtGatt.GattService: stop()
10-26 18:06:27.115  4572  4572 D BtGatt.AdvertiseManager: advertise clients cleared
10-26 18:06:27.116  4572  4572 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:27.116  4572  4572 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:27.116  4572  4572 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:27.116  4572  4572 V BluetoothAdapterState: isBleTurningOff()=true
10-26 18:06:27.116  4572  4631 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-26 18:06:27.116  4572  4631 D BluetoothAdapterProperties: Setting state to 10
,10-26 18:06:27.116  4572  4631 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-26 18:06:27.117  4572  4631 I BluetoothAdapterState: Entering OffState
10-26 18:06:27.117   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-26 18:06:27.123  4572  4572 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-26 18:06:27.123  4572  4572 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-26 18:06:27.123  4572  4572 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-26 18:06:27.125  4572  4632 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-26 18:06:27.133  4572  4572 I art     : System.exit called, status: 0
,10-26 18:06:27.134  4572  4572 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-26 18:06:27.111  5743  5743 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 18:06:27.111  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-26 18:06:27.151  5743  5743 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.e.b(PG:170)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-26 18:06:27.151  5743  5743 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.k.d(PG:583)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.e.b(PG:170)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 18:06:27.151  5743  5743 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.File.exists(File.java:361)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at and,roid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 18:06:27.151  5743  5743 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.File.exists(File.java:361)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 18:06:27.151  5743  5743 D StrictMod,e: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 18:06:27.151  5743  5743 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 18:06:27.151  5743  5743 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 18:06:27.156  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 18:06:27.165  5722  5722 D DockEventReceiver: finishStartingService: stopping service
10-26 18:06:27.166   929   939 I ActivityManager: Killing 5397:com.android.chrome/u0a39 (adj 15): empty #17
,10-26 18:06:27.206   929  3816 I ActivityManager: Process com.android.bluetooth (pid 4572) has died
,10-26 18:06:27.208  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 18:06:27.220   929  3802 I ActivityManager: Start proc 5781:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,10-26 18:06:27.241   929   946 D Tethering: InitialState.processMessage what=4
,10-26 18:06:27.244   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 18:06:27.285  5781  5781 D AdapterServiceConfig: Adding HeadsetService
,10-26 18:06:27.286  5781  5781 D AdapterServiceConfig: Adding A2dpService
10-26 18:06:27.286  5781  5781 D AdapterServiceConfig: Adding HidService
10-26 18:06:27.286  5781  5781 D AdapterServiceConfig: Adding HealthService
10-26 18:06:27.286  5781  5781 D AdapterServiceConfig: Adding PanService
10-26 18:06:27.286  5781  5781 D AdapterServiceConfig: Adding GattService
,10-26 18:06:27.286  5781  5781 D AdapterServiceConfig: Adding BluetoothMapService
10-26 18:06:27.286  5781  5781 D AdapterServiceConfig: Adding SapService
,10-26 18:06:27.290   929  3816 I ActivityManager: Killing 5241:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-26 18:06:27.325  3968  3968 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 18:06:27.337  3968  3968 D SystemUpdateService: onCreate
,10-26 18:06:27.341  3968  3968 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 18:06:27.348  3968  3968 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-26 18:06:27.353  3968  5381 I iu.UploadsManager: num queued entries: 0
,10-26 18:06:27.354  3968  5381 I iu.UploadsManager: num updated entries: 0
,10-26 18:06:27.354  3968  5793 I SystemUpdateService: active receiver: enabled
,10-26 18:06:27.359  3968  3968 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 18:06:27.362  3968  3968 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 18:06:27.365  3968  5793 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 18:06:27.366  3968  5381 I iu.SyncManager: NEXT; no task
,10-26 18:06:27.375   929  3150 I ActivityManager: Start proc 5795:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-26 18:06:27.378  3968  5793 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-26 18:06:27.378  3968  5793 I SystemUpdateService: now status is 0 (complete)
10-26 18:06:27.378  3968  5793 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 18:06:27.378  3968  5793 I SystemUpdateService: file has been verified
,10-26 18:06:27.378  3968  5793 I SystemUpdateService: OTA package size = 21989297
,10-26 18:06:27.388  3968  5793 I SystemUpdateService: showing system update notification
,10-26 18:06:27.417  5795  5795 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-26 18:06:27.420  5795  5795 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 18:06:27.426  5795  5795 D SprintDMHelper: simOperator: 
,10-26 18:06:27.426  5795  5795 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 18:06:27.433   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 18:06:27.438   929  3150 I ActivityManager: Start proc 5807:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-26 18:06:27.440  3968  3968 D SystemUpdateService: onDestroy
,10-26 18:06:27.442   929  3578 I ActivityManager: Killing 5417:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-26 18:06:27.541  4414  5821 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-26 18:06:27.550   929  3150 I ActivityManager: Start proc 5822:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-26 18:06:27.552   929  3150 I ActivityManager: Killing 5432:com.google.android.configupdater/u0a5 (adj 15): empty #17
,10-26 18:06:27.587  5743  5769 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-26 18:06:27.603  5822  5822 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-26 18:06:27.748   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1893499:true
,10-26 18:06:27.795   929  3150 I ActivityManager: Killing 3848:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-26 18:06:27.849   929  3594 I ActivityManager: Start proc 5836:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-26 18:06:27.880  5836  5836 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-26 18:06:27.888   929  3183 I ActivityManager: Killing 5496:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-26 18:06:30.035   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-26 18:06:30.036   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-26 18:06:31.715   929   939 D WifiService: setWifiEnabled: true pid=5659, uid=10077
,10-26 18:06:31.715   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 18:06:31.722   510   924 D SoftapController: Softap fwReload - Ok
10-26 18:06:31.726   510   924 D CommandListener: Setting iface cfg
10-26 18:06:31.727   510   924 D CommandListener: Trying to bring down wlan0
10-26 18:06:31.728   510   924 D CommandListener: Clearing all IP addresses on wlan0
,10-26 18:06:31.733   929  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 18:06:32.304   929  2981 D wifi    : set interface wlan0 flags (UP)
10-26 18:06:32.304   929  2981 I WifiHAL : Initializing wifi
10-26 18:06:32.304   929  2981 I WifiHAL : Creating socket
,10-26 18:06:32.306   929  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-26 18:06:32.306   929  2981 D wifi    : Did set static halHandle = 0x7f6b504080
,10-26 18:06:32.307   929  2981 D wifi    : halHandle = 0x7f6b504080, mVM = 0x7f87acd140, mCls = 0x1916
10-26 18:06:32.307   929  2981 D wifi    : array field set
10-26 18:06:32.307   929  2981 I WifiNative-HAL: interface[0] = wlan0
10-26 18:06:32.309   929  5854 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547261268096
10-26 18:06:32.309   929  5854 D wifi    : waitForHalEvents called, vm = 0x7f87acd140, obj = 0x1916, env = 0x7f68c99500
,10-26 18:06:32.313   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-26 18:06:32.371  5856  5856 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 18:06:32.413   929  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 18:06:32.416  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:32.417  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:32.418  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:32.420  5856  5856 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 18:06:32.463  5856  5856 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 18:06:32.463  5856  5856 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 18:06:32.485   929  2981 D WifiConfigStore: Loading config and enabling all networks 
,10-26 18:06:32.488  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:32.488  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:32.488  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:32.488  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:32.488  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:32.488  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:32.488  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:32.488  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:32.488  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:32.488  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 18:06:32.488  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:32.490  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:32.491  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:32.491  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:32.491  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:32.491  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:32.491  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:32.491  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:32.491  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:32.491  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:32.491  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:32.491  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:06:32.493  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:32.494  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:32.494  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:32.494  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:32.494  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:32.494  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:32.494  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:32.494  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:32.494  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:32.494  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:32.494  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:06:32.510   929  2981 D WifiConfigStore: loaded 0 passpoint configs
,10-26 18:06:32.511   929  2981 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-26 18:06:32.511   929  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-26 18:06:32.512   929  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-26 18:06:32.512   929  2981 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,10-26 18:06:32.512   929  2981 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,10-26 18:06:32.513   929  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-26 18:06:32.513   929  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-26 18:06:32.513   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-26 18:06:32.513   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,10-26 18:06:32.513   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-26 18:06:32.513   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
10-26 18:06:32.513   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-26 18:06:32.516   929  2981 D WifiNative-HAL: Setting external_sim to 1
,10-26 18:06:32.516   929  2981 D wifi    : setting dfs flag to true, 0x7f6d66fce0
10-26 18:06:32.516  4414  4414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 18:06:32.516   929  2981 D WifiStateMachine: Setting OUI to DA-A1-19
10-26 18:06:32.516   929  2981 D wifi    : setting scan oui 0x7f6d66fce0
10-26 18:06:32.516   929  2981 D WifiHAL : Sending mac address OUI
,10-26 18:06:32.519   929  2981 E native  : do suspend false
,10-26 18:06:32.526   929  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-26 18:06:32.527   510   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-26 18:06:32.527   929   929 D RttService: SCAN_AVAILABLE : 3
10-26 18:06:32.527   929  3036 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 18:06:32.528   510   924 D CommandListener: Setting iface cfg
,10-26 18:06:32.532   929  2969 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '122 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 122 Failed to set address (No such device)'
10-26 18:06:32.532   929  2969 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-26 18:06:32.540   929  2969 D WifiNative-HAL: p2pGetDeviceAddress
,10-26 18:06:32.541   929  2969 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-26 18:06:32.559   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=116375 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=28 mControllerEnergyUsed=106 }
,10-26 18:06:35.037   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:35.360   929  2981 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 8 -> obsolete
,10-26 18:06:35.609  5856  5856 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 18:06:35.613  5856  5856 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 18:06:35.617  5856  5856 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 18:06:35.624  5856  5856 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 18:06:35.678   929  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-26 18:06:35.679   929  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-26 18:06:35.680   929  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 18:06:35.690   929  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-26 18:06:35.725   929  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-26 18:06:35.733  5856  5856 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-26 18:06:36.038   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:36.162  5856  5856 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-26 18:06:36.199  5856  5856 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-26 18:06:36.200  5856  5856 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-26 18:06:36.210   929  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-26 18:06:36.211   929  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-26 18:06:36.211   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-26 18:06:36.228   929  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 18:06:36.240   510   924 D CommandListener: Setting iface cfg
,10-26 18:06:36.246   929  2981 D WifiStateMachine: Start Dhcp Watchdog 2
,10-26 18:06:36.253   929  5871 D DhcpClient: Receive thread started
,10-26 18:06:36.256   929  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 18:06:36.256   929  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-26 18:06:36.256   929  2983 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-26 18:06:36.339   929  2981 E native  : do suspend false
,10-26 18:06:36.353   929  5870 D DhcpClient: Broadcasting DHCPDISCOVER
,10-26 18:06:36.367   929  5871 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172719, domain null
,10-26 18:06:36.368   929  5870 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172719 seconds
,10-26 18:06:36.370   929  5870 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-26 18:06:36.381   929  5871 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-26 18:06:36.382   929  5870 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-26 18:06:36.384   510   924 D CommandListener: Setting iface cfg
,10-26 18:06:36.390   929  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-26 18:06:36.393   929  5870 D DhcpClient: Scheduling renewal in 86399s
,10-26 18:06:36.403   929  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-26 18:06:36.405   929  2981 D WifiConfigStore: No blacklist allowed without epno enabled
,10-26 18:06:36.408   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-26 18:06:36.410   929  2983 D ConnectivityService: Adding iface wlan0 to network 101
10-26 18:06:36.420   929  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-26 18:06:36.458   929  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-26 18:06:36.458   929  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-26 18:06:36.460   929  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-26 18:06:36.462   929  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-26 18:06:36.463   929  2983 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-26 18:06:36.471   929  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 18:06:36.476   929  2983 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-26 18:06:36.476   929  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-26 18:06:36.476   929  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-26 18:06:36.476   929  2983 D ConnectivityService:    accepting network in place of null
,10-26 18:06:36.476   929  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-26 18:06:36.476   929  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 18:06:36.477   929  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 18:06:36.499   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 18:06:36.516   929  5869 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-26 18:06:36.523   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 18:06:36.526   929  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-26 18:06:36.526  3714  3839 W QCNEJ   : |CORE| network available: 101
10-26 18:06:36.526   929  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-26 18:06:36.527   929  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-26 18:06:36.529  3714  3839 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-26 18:06:36.530  3714  3839 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-26 18:06:36.531  3714  3839 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-26 18:06:36.532   929   946 D Tethering: MasterInitialState.processMessage what=3
10-26 18:06:36.533   929  3183 D ConnectivityService: Returning blocked NetworkInfo to uid=10043
10-26 18:06:36.533  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.534  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:36.534  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:36.534  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:36.534  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:36.534  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:36.534  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:36.534  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:06:36.534  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:06:36.534  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.534  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:36.536   929  3594 D ConnectivityService: Returning blocked NetworkInfo to uid=10062
,10-26 18:06:36.537  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.537  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:36.537  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:36.537  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:36.537  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:36.537  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:36.537  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:36.537  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:06:36.537  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:06:36.538  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.538  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 18:06:36.540  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 18:06:36.540  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:36.540  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:36.540  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:36.540  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:36.540  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:36.540  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:06:36.540  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:06:36.540  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:06:36.540  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.540  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 18:06:36.543  3936  3936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-26 18:06:36.545  3968  3968 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-26 18:06:36.547  3968  3968 D SystemUpdateService: onCreate
10-26 18:06:36.551  3968  3968 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 18:06:36.559  3968  3968 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-26 18:06:36.565  3968  5381 I iu.UploadsManager: num queued entries: 0
10-26 18:06:36.565  3968  5381 I iu.UploadsManager: num updated entries: 0
10-26 18:06:36.566  3968  5381 I iu.SyncManager: NEXT; no task
,10-26 18:06:36.566  3968  5882 I SystemUpdateService: active receiver: enabled
,10-26 18:06:36.571  3968  3968 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-26 18:06:36.572  3968  3968 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 18:06:36.574  5795  5795 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-26 18:06:36.577  5795  5795 D SprintDMHelper: simOperator: 
10-26 18:06:36.577  5795  5795 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 18:06:36.589   929  5868 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:813::200e
,10-26 18:06:36.592   929  3183 D ConnectivityService: Returning blocked NetworkInfo to uid=10053
,10-26 18:06:36.602  3968  5882 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 18:06:36.607  3968  5882 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-26 18:06:36.607  3968  5882 I SystemUpdateService: now status is 0 (complete)
10-26 18:06:36.607  3968  5882 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 18:06:36.607  3968  5882 I SystemUpdateService: file has been verified
10-26 18:06:36.608  3968  5882 I SystemUpdateService: OTA package size = 21989297
,10-26 18:06:36.613  3968  5882 I SystemUpdateService: showing system update notification
,10-26 18:06:36.621   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 18:06:36.622  3968  3968 D SystemUpdateService: onDestroy
,10-26 18:06:36.668   929  5868 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 26 Oct 2016 16:06:36 GMT], X-Android-Received-Millis=[1477497996667], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477497996617]}
,10-26 18:06:36.668   929  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-26 18:06:36.669   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,10-26 18:06:36.669   929  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 18:06:36.670   929  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-26 18:06:36.723   929  3578 D WifiService: setWifiEnabled: false pid=5659, uid=10077
,10-26 18:06:36.723   929  3578 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 18:06:36.726   929  2981 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-26 18:06:36.726   929  2981 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-26 18:06:36.726   929  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-26 18:06:36.727   929  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 18:06:36.742   929  5870 D DhcpClient: Clearing IP address
,10-26 18:06:36.743   510   924 D CommandListener: Setting iface cfg
10-26 18:06:36.746   510   924 D CommandListener: Clearing all IP addresses on wlan0
,10-26 18:06:36.750   929  5871 D DhcpClient: Receive thread stopped
,10-26 18:06:36.768   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-26 18:06:36.768   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,10-26 18:06:36.775   536   536 E Parcel  : Reading a NULL string not supported here.
,10-26 18:06:36.775   929   929 D RttService: SCAN_AVAILABLE : 1
,10-26 18:06:36.776   929  3036 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-26 18:06:36.779   929  2983 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-26 18:06:36.779   929  2981 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-26 18:06:36.782  3714  3839 W QCNEJ   : |CORE| network lost: 101
10-26 18:06:36.783  3714  3839 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-26 18:06:36.787   929  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-26 18:06:36.809   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 18:06:36.829   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 18:06:36.829   929  2983 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-26 18:06:36.829   510   924 D CommandListener: Clearing all IP addresses on wlan0
10-26 18:06:36.829   929  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 18:06:36.833  3936  3936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-26 18:06:36.834   929   946 D Tethering: MasterInitialState.processMessage what=3
,10-26 18:06:36.848  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 18:06:36.848  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:36.848  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:36.848  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:36.848  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:36.848  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:36.848  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:36.848  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:36.848  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:36.848  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.849  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:36.850  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.850  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:36.850  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:36.850  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:36.850  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:36.850  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:36.850  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:36.850  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:36.850  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:36.850  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.850  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:36.851  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.851  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:36.851  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:36.851  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:36.851  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:06:36.851  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:36.851  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:36.851  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:36.851  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:36.851  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetoot,h is disabled - will return stored value
10-26 18:06:36.851  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:36.854  3968  3968 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-26 18:06:36.857  3968  3968 D SystemUpdateService: onCreate
10-26 18:06:36.861  3968  3968 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-26 18:06:36.865  3968  5897 I SystemUpdateService: active receiver: enabled
10-26 18:06:36.870  3968  3968 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-26 18:06:36.876  3968  5381 I iu.UploadsManager: num queued entries: 0
10-26 18:06:36.877  3968  5381 I iu.UploadsManager: num updated entries: 0
10-26 18:06:36.879  3968  3968 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-26 18:06:36.881  3968  3968 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-26 18:06:36.882  5795  5795 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 18:06:36.884   510   924 E Netd    : netlink response contains error (No such file or directory)
,10-26 18:06:36.886   929  2983 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-26 18:06:36.886   929  2981 D DhcpClient: doQuit
10-26 18:06:36.886   929  2981 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-26 18:06:36.886   929  5870 D DhcpClient: onQuitting
10-26 18:06:36.887  5856  5856 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-26 18:06:36.888  5795  5795 D SprintDMHelper: simOperator: 
,10-26 18:06:36.888  5795  5795 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 18:06:36.888  3968  5897 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 18:06:36.890  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.890  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:36.890  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:36.890  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:36.890  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:36.890  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:36.890  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:36.890  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:36.890  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:36.890  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.890  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:36.891  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.891  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:36.891  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:36.891  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:36.891  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:36.891  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:36.891  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:36.891  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:36.891  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:36.891  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 18:06:36.891  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:36.893  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.893  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:36.893  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:36.893  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:36.893  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:36.893  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:36.893  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:36.893  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:36.893  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:36.893  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:36.893  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:06:36.900  3968  5897 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-26 18:06:36.900  3968  5897 I SystemUpdateService: now status is 0 (complete)
10-26 18:06:36.900  3968  5897 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 18:06:36.900  3968  5897 I SystemUpdateService: file has been verified
10-26 18:06:36.900  3968  5897 I SystemUpdateService: OTA package size = 21989297
10-26 18:06:36.901  5856  5856 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-26 18:06:36.904  5856  5856 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-26 18:06:36.905  3968  5381 I iu.SyncManager: NEXT; no task
,10-26 18:06:36.917  3968  5897 I SystemUpdateService: showing system update notification
,10-26 18:06:36.927   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,10-26 18:06:36.930  3968  3968 D SystemUpdateService: onDestroy
,10-26 18:06:36.935  5856  5856 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-26 18:06:36.945  5856  5856 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-26 18:06:37.038   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:37.046   929  2981 D wifi    : In wifi stop Hal
,10-26 18:06:37.046   929  2981 D wifi    : halHandle = 0x7f6b504080, mVM = 0x7f87acd140, mCls = 0x1916
10-26 18:06:37.047   929  5854 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-26 18:06:37.047   929  5854 D WifiHAL : Got a signal to exit!!!
10-26 18:06:37.047   929  5854 I WifiHAL : Exit wifi_event_loop
10-26 18:06:37.047  4414  4414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 18:06:37.048  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:37.049  3690  4172 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 18:06:37.050  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:37.050   929  2981 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-26 18:06:37.050   929  2981 E WifiHAL : Event processing terminated
10-26 18:06:37.050  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:37.050   929  2981 D wifi    : In wifi cleaned up handler
10-26 18:06:37.050   929  2981 I WifiHAL : Internal cleanup completed
,10-26 18:06:37.071   929  5854 D wifi    : set interface wlan0 flags (DOWN)
,10-26 18:06:37.072   929  2981 D WifiNative-HAL: HAL event thread stopped successfully
,10-26 18:06:37.144   510   924 E Netd    : netlink response contains error (No such file or directory)
,10-26 18:06:37.278   929   946 D Tethering: InitialState.processMessage what=4
,10-26 18:06:37.285   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 18:06:37.527   929  2983 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-26 18:06:38.039   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:39.040   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:40.040   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-26 18:06:41.760   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8e44391:true
,10-26 18:06:41.761  5781  5781 D BluetoothAdapterState: make() - Creating AdapterState
,10-26 18:06:41.765  5781  5781 I bt_bluedroid: init
10-26 18:06:41.765  5781  5908 I BluetoothAdapterState: Entering OffState
,10-26 18:06:41.768  5781  5909 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-26 18:06:41.768  5781  5909 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-26 18:06:41.769  5781  5909 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-26 18:06:41.769  5781  5909 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-26 18:06:41.769  5781  5781 I bt_bluedroid: get_profile_interface socket
,10-26 18:06:41.772  5781  5912 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 18:06:41.773  5781  5781 I bt_bluedroid: get_profile_interface sdp
10-26 18:06:41.775  5781  5912 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 18:06:41.780  5781  5792 I bt_bluedroid: config_hci_snoop_log
,10-26 18:06:41.781   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 18:06:41.787  5781  5908 D BluetoothAdapterState: Current state: OFF, message: 0
,10-26 18:06:41.787  5781  5908 D BluetoothAdapterProperties: Setting state to 14
10-26 18:06:41.788  5781  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-26 18:06:41.790  5781  5908 D BluetoothBondStateMachine: make
,10-26 18:06:41.792  5781  5913 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 18:06:41.796  5781  5908 I BluetoothAdapterState: Entering PendingCommandState
,10-26 18:06:41.797  5781  5781 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-26 18:06:41.800  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
10-26 18:06:41.801  5781  5781 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-26 18:06:41.801  5781  5781 D BtGatt.GattService: Received start request. Starting profile...
,10-26 18:06:41.802  5781  5781 D BtGatt.GattService: start()
10-26 18:06:41.802  5781  5781 I bt_bluedroid: get_profile_interface gatt
,10-26 18:06:41.803  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:41.804  5781  5781 D BtGatt.AdvertiseManager: advertise manager created
,10-26 18:06:41.810  5781  5781 V BluetoothAdapterState: isTurningOff()=false
,10-26 18:06:41.811  5781  5781 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:41.811  5781  5781 V BluetoothAdapterState: isBleTurningOn()=true
10-26 18:06:41.812  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:41.812  5781  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-26 18:06:41.813  5781  5908 I bt_bluedroid: bt_bluedroid
,10-26 18:06:41.813  5781  5909 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-26 18:06:41.814  5781  5909 I bt_hci  : start_up
,10-26 18:06:41.819  5781  5909 I bt_vendor: alloc value 0xf40b8871
,10-26 18:06:41.820  5781  5909 I bt_vendor: init
10-26 18:06:41.820  5781  5909 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 18:06:41.820  5781  5909 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 18:06:41.931  5781  5909 D bt_hci  : start_up starting async portion
,10-26 18:06:41.932  5781  5916 I bt_hci  : event_finish_startup
10-26 18:06:41.932  5781  5916 I bt_hci_h4: hal_open
,10-26 18:06:41.932  5781  5916 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-26 18:06:41.933  5917  5917 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-26 18:06:41.935  5781  5916 I bt_userial_vendor: device fd = 54 open
,10-26 18:06:41.953  5781  5916 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 18:06:41.956  5781  5916 D bt_hwcfg: Chipset BCM4358A3
,10-26 18:06:41.956  5781  5916 D bt_hwcfg: Target name = [BCM4358A3]
10-26 18:06:41.956  5781  5916 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 18:06:42.338  5781  5916 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-26 18:06:42.339  5781  5916 D bt_hwcfg: Settlement delay -- 100 ms
,10-26 18:06:42.339  5781  5916 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 18:06:42.472  5781  5916 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 18:06:42.472  5781  5916 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,10-26 18:06:42.474  5781  5916 I bt_hwcfg: vendor lib fwcfg completed
,10-26 18:06:42.474  5781  5916 I bt_vendor: firmware callback
,10-26 18:06:42.474  5781  5916 I bt_hci  : firmware_config_callback
,10-26 18:06:42.482  5781  5919 I bt_btu  : btu_task pending for preload complete event
10-26 18:06:42.482  5781  5919 I bt_btu_task: Bluetooth chip preload is complete
10-26 18:06:42.482  5781  5919 I bt_btu  : btu_task received preload complete event
,10-26 18:06:42.489  5781  5919 I         : BTE_InitTraceLevels -- TRC_HCI
,10-26 18:06:42.489  5781  5919 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-26 18:06:42.489  5781  5919 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-26 18:06:42.489  5781  5919 I         : BTE_InitTraceLevels -- TRC_AVDT
10-26 18:06:42.489  5781  5919 I         : BTE_InitTraceLevels -- TRC_AVRC
10-26 18:06:42.489  5781  5919 I         : BTE_InitTraceLevels -- TRC_A2D
,10-26 18:06:42.489  5781  5919 I         : BTE_InitTraceLevels -- TRC_BNEP
10-26 18:06:42.490  5781  5919 I         : BTE_InitTraceLevels -- TRC_BTM
10-26 18:06:42.490  5781  5919 I         : BTE_InitTraceLevels -- TRC_GAP
10-26 18:06:42.490  5781  5919 I         : BTE_InitTraceLevels -- TRC_PAN
10-26 18:06:42.490  5781  5919 I         : BTE_InitTraceLevels -- TRC_SDP
,10-26 18:06:42.490  5781  5919 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 18:06:42.490  5781  5919 I         : BTE_InitTraceLevels -- TRC_SMP
10-26 18:06:42.490  5781  5919 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-26 18:06:42.490  5781  5919 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 18:06:42.574  5781  5919 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4036549
,10-26 18:06:42.574  5781  5919 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4036549 
,10-26 18:06:42.587  5781  5912 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-26 18:06:42.588  5781  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 18:06:42.589  5781  5912 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 18:06:42.591  5781  5912 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 18:06:42.594  5781  5912 D BluetoothAdapterProperties: Scan Mode:20
10-26 18:06:42.595  5781  5912 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 18:06:42.595  5781  5912 D bt_hci  : do_postload posting postload work item
10-26 18:06:42.595  5781  5916 I bt_hci  : event_postload
,10-26 18:06:42.595  5781  5916 I bt_vendor: sco_config_cb
10-26 18:06:42.595  5781  5916 I bt_hci  : sco_config_callback postload finished.
,10-26 18:06:42.602  5781  5912 D bt_bte_conf: Device ID record 1 : primary
,10-26 18:06:42.602  5781  5912 D bt_bte_conf:   vendorId            = 000f
10-26 18:06:42.602  5781  5912 D bt_bte_conf:   vendorIdSource      = 0001
10-26 18:06:42.602  5781  5912 D bt_bte_conf:   product             = 1200
10-26 18:06:42.602  5781  5912 D bt_bte_conf:   version             = 1436
10-26 18:06:42.602  5781  5912 D bt_bte_conf:   clientExecutableURL = 
10-26 18:06:42.602  5781  5912 D bt_bte_conf:   serviceDescription  = 
10-26 18:06:42.603  5781  5912 D bt_bte_conf:   documentationURL    = 
10-26 18:06:42.603  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:42.603  5781  5912 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-26 18:06:42.603  5781  5909 D bt_stack_manager: event_start_up_stack finished
,10-26 18:06:42.604  5781  5916 I bt_vendor: low_power_mode_cb
,10-26 18:06:42.607  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:42.610  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:42.612  5781  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-26 18:06:42.612  5781  5908 D BluetoothAdapterProperties: Setting state to 15
10-26 18:06:42.612  5781  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 18:06:42.613  5781  5908 I BluetoothAdapterState: Entering BleOnState
,10-26 18:06:42.616  5781  5908 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-26 18:06:42.617  5781  5908 D BluetoothAdapterProperties: Setting state to 11
,10-26 18:06:42.617  5781  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-26 18:06:42.623  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:42.625  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:42.626  5781  5781 D HeadsetService: Received start request. Starting profile...
,10-26 18:06:42.633  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:42.635  5781  5781 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-26 18:06:42.636  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:42.636  5781  5781 D HeadsetStateMachine: make
,10-26 18:06:42.641  5781  5908 I BluetoothAdapterState: Entering PendingCommandState
,10-26 18:06:42.645  5781  5781 D HeadsetStateMachine: max_hf_connections = 1
,10-26 18:06:42.646  5781  5781 I bt_bluedroid: get_profile_interface handsfree
10-26 18:06:42.646  5781  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-26 18:06:42.646  5781  5912 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,10-26 18:06:42.650  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:42.651  5781  5781 D A2dpService: Received start request. Starting profile...
10-26 18:06:42.652  5781  5781 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-26 18:06:42.652  5781  5781 I bt_bluedroid: get_profile_interface avrcp
,10-26 18:06:42.658  5781  5781 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-26 18:06:42.658  5781  5781 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-26 18:06:42.658  5781  5781 D A2dpStateMachine: make
,10-26 18:06:42.659  5781  5781 I bt_bluedroid: get_profile_interface a2dp
,10-26 18:06:42.660  5781  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-26 18:06:42.662  5781  5928 D A2dpStateMachine: Enter Disconnected: -2
10-26 18:06:42.662  5781  5781 I BluetoothHidServiceJni: classInitNative: succeeds
10-26 18:06:42.663  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:42.664  5781  5781 D HidService: Received start request. Starting profile...
10-26 18:06:42.664  5781  5781 I bt_bluedroid: get_profile_interface hidhost
10-26 18:06:42.665  5781  5781 D HidService: setHidService(): set to: null
10-26 18:06:42.665  5781  5912 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf401756d
10-26 18:06:42.665  5781  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-26 18:06:42.665  5722  5722 D BluetoothInputDevice: Proxy object connected
10-26 18:06:42.666  5781  5781 I BluetoothHealthServiceJni: classInitNative: succeeds
10-26 18:06:42.667  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:42.668  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 18:06:42.668  5722  5722 D HidProfile: Bluetooth service connected
10-26 18:06:42.668  5781  5781 D HealthService: Received start request. Starting profile...
,10-26 18:06:42.670  5781  5781 I bt_bluedroid: get_profile_interface health
10-26 18:06:42.670  5781  5781 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-26 18:06:42.671  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
10-26 18:06:42.673  5781  5781 D PanService: Received start request. Starting profile...
,10-26 18:06:42.673  5781  5781 D BluetoothPanServiceJni: initializeNative(L110): pan
,10-26 18:06:42.673  5722  5722 D BluetoothPan: BluetoothPAN Proxy object connected
,10-26 18:06:42.673  5781  5781 I bt_bluedroid: get_profile_interface pan
,10-26 18:06:42.673  5781  5912 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-26 18:06:42.674  5722  5722 D PanProfile: Bluetooth service connected
10-26 18:06:42.675  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:42.677  5781  5781 D BluetoothMapService: Received start request. Starting profile...
,10-26 18:06:42.676  5722  5722 D BluetoothMap: Proxy object connected
,10-26 18:06:42.677  5781  5781 D BluetoothMapService: start()
10-26 18:06:42.677  5722  5722 D MapProfile: Bluetooth service connected
10-26 18:06:42.677  5722  5722 D BluetoothMap: getConnectedDevices()
10-26 18:06:42.678  5722  5722 D BluetoothMap: Bluetooth is Not enabled
10-26 18:06:42.681  5781  5781 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-26 18:06:42.682  5781  5781 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-26 18:06:42.682  5781  5781 D BluetoothMapAppObserver: createReceiver()
10-26 18:06:42.683  5781  5781 D BluetoothMapAppObserver: initObservers()
10-26 18:06:42.683  5781  5781 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-26 18:06:42.689  5781  5781 V SapService: SapBinder()
10-26 18:06:42.689  5781  5781 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:42.690  5781  5781 D SapService: Received start request. Starting profile...
10-26 18:06:42.690  5781  5781 V SapService: start()
10-26 18:06:42.693  5781  5781 V BluetoothAdapterState: isTurningOff()=false
,10-26 18:06:42.693  5781  5781 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:42.693  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:42.693  5781  5926 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
10-26 18:06:42.693  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:42.693  5781  5781 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:42.693  5781  5781 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:42.693  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:42.693  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:42.693  5781  5781 V BluetoothAdapterState: isTurningOff()=false
,10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isTurningOn()=true
,10-26 18:06:42.694  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:42.695  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:42.696  5781  5781 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:42.696  5781  5781 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:42.696  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:42.696  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:42.697  5781  5781 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:42.697  5781  5781 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:42.697  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:42.697  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:42.697  5781  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-26 18:06:42.697  5781  5908 D BluetoothAdapterProperties: ScanMode =  20
10-26 18:06:42.697  5781  5908 D BluetoothAdapterProperties: State =  11
10-26 18:06:42.699  5781  5912 D BluetoothAdapterProperties: Scan Mode:21
10-26 18:06:42.699  5781  5912 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 18:06:42.699  5781  5908 D BluetoothAdapterProperties: Setting state to 12
10-26 18:06:42.699  5781  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-26 18:06:42.700  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 18:06:42.700  5781  5908 I BluetoothAdapterState: Entering OnState
10-26 18:06:42.700  3122  3990 D BluetoothMap: onBluetoothStateChange: up=true
10-26 18:06:42.701  3122  3133 D BluetoothPan: onBluetoothStateChange on: true
10-26 18:06:42.701  3122  3122 D BluetoothMap: Proxy object connected
10-26 18:06:42.702  3122  3122 D MapProfile: Bluetooth service connected
10-26 18:06:42.702  3122  3122 D BluetoothMap: getConnectedDevices()
,10-26 18:06:42.704  5722  5733 D BluetoothPan: onBluetoothStateChange on: true
,10-26 18:06:42.704   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:42.704  3122  3122 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 18:06:42.704  3122  3122 D PanProfile: Bluetooth service connected
10-26 18:06:42.705  3122  3135 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 18:06:42.705  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:42.705  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:42.705  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:42.705  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:42.705  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:06:42.705  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:42.705  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:42.705  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 18:06:42.706  5722  5735 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 18:06:42.706  3754  3789 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:42.707  3122  3990 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:42.707  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:42.707  5722  5733 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 18:06:42.708  5781  5781 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 18:06:42.709  3122  3133 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 18:06:42.709  5781  5781 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-26 18:06:42.710  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:42.710  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:42.710  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:42.710  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:42.710  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:06:42.710  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:42.710  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:42.710  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 18:06:42.710   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:42.710  5722  5735 D BluetoothMap: onBluetoothStateChange: up=true
10-26 18:06:42.710   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:42.710  3122  3135 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 18:06:42.711  5781  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 18:06:42.712  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:06:42.712  3122  3122 D BluetoothInputDevice: Proxy object connected
10-26 18:06:42.712   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 18:06:42.712  3122  3122 D HidProfile: Bluetooth service connected
10-26 18:06:42.713   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
10-26 18:06:42.715  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:42.715  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:42.715  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:42.715  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:42.715  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:06:42.715  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:42.715  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:42.715  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 18:06:42.716  5781  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 18:06:42.717  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:42.717  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 18:06:42.717  5781  5781 D ObexServerSockets: Succeed to create listening sockets 
10-26 18:06:42.717  5781  5781 D ObexServerSockets0: startAccept()
10-26 18:06:42.717  5781  5781 D ObexServerSockets0: prepareForNewConnect()
10-26 18:06:42.718  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:42.719  5722  5722 D LocalBluetoothProfileManager: Adding local A2DP profile
10-26 18:06:42.719  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:42.721  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:42.721  5781  5781 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 18:06:42.721  5781  5781 D BluetoothSdpJni: SDP Create record success - handle: 0
10-26 18:06:42.722  5781  5934 D ObexServerSockets0: Accepting socket connection...
10-26 18:06:42.722  5781  5933 D ObexServerSockets0: Accepting socket connection...
,10-26 18:06:42.723  5781  5781 D BluetoothMapService: onReceive
10-26 18:06:42.723  5722  5722 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-26 18:06:42.723  5781  5781 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 18:06:42.723  5781  5781 D BluetoothMapService: STATE_ON
10-26 18:06:42.724   929   929 D BluetoothA2dp: Proxy object connected
10-26 18:06:42.727  5781  5935 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 18:06:42.729  3122  3122 D BluetoothA2dp: Proxy object connected
,10-26 18:06:42.731  5781  5935 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-26 18:06:42.731  5781  5935 D BluetoothSdpJni: SDP Create record success - handle: 1
10-26 18:06:42.731  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 18:06:42.735  5722  5722 D BluetoothA2dp: Proxy object connected
,10-26 18:06:42.739  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 18:06:42.741  5722  5722 D DockEventReceiver: finishStartingService: stopping service
,10-26 18:06:42.746  3122  3122 D BluetoothPbap: Proxy object connected
,10-26 18:06:42.746  3122  3122 D PbapServerProfile: Bluetooth service connected
10-26 18:06:42.746  5722  5722 D BluetoothPbap: Proxy object connected
,10-26 18:06:42.746  5722  5722 D PbapServerProfile: Bluetooth service connected
,10-26 18:06:42.752  5781  5781 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-26 18:06:42.752  5781  5781 D ObexServerSockets0: prepareForNewConnect()
,10-26 18:06:42.755  5781  5939 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 18:06:42.768  5781  5943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 18:06:42.769  5781  5943 I BtOppRfcommListener: Accept thread started.
,10-26 18:06:42.806  3122  3990 D BluetoothHeadset: Proxy object connected
10-26 18:06:42.806  3122  3122 D HeadsetProfile: Bluetooth service connected
10-26 18:06:42.806  3754  3785 D BluetoothHeadset: Proxy object connected
10-26 18:06:42.807  3754  4021 D BluetoothHeadset: Proxy object connected
,10-26 18:06:42.807  3122  3133 D BluetoothHeadset: Proxy object connected
10-26 18:06:42.807   929   929 D BluetoothHeadset: Proxy object connected
10-26 18:06:42.807   929   929 D BluetoothHeadset: Proxy object connected
10-26 18:06:42.807   929   929 D BluetoothHeadset: Proxy object connected
,10-26 18:06:42.808  3122  3122 D HeadsetProfile: Bluetooth service connected
,10-26 18:06:42.809   929   946 D BluetoothHeadset: Proxy object connected
,10-26 18:06:42.811   929   946 D BluetoothHeadset: Proxy object connected
,10-26 18:06:42.826  5722  5733 D BluetoothHeadset: Proxy object connected
,10-26 18:06:42.827  5722  5722 D HeadsetProfile: Bluetooth service connected
,10-26 18:06:44.483   929  2983 D ConnectivityService: handlePromptUnvalidated 101
,10-26 18:06:45.041   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:45.259  3636  3719 I Keyboard.Facilitator.LanguageModelFlusher: run(),
10-26 18:06:45.259  3636  3719 I Keyboard.Facilitator: flushDynamicLanguageModels()
,10-26 18:06:45.289  3577  3577 I ConfigService: onCreate
,10-26 18:06:46.042   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:46.738  5781  5908 D BluetoothAdapterState: Current state: ON, message: 23
,10-26 18:06:46.739  5781  5908 D BluetoothAdapterProperties: Setting state to 13
,10-26 18:06:46.739  5781  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-26 18:06:46.740  5781  5908 D BluetoothAdapterProperties: onBluetoothDisable()
10-26 18:06:46.741  5781  5908 I BluetoothAdapterState: Entering PendingCommandState
10-26 18:06:46.744  5781  5781 D BluetoothMapService: onReceive
,10-26 18:06:46.746  5781  5781 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-26 18:06:46.746  5781  5781 D BluetoothMapService: STATE_TURNING_OFF
,10-26 18:06:46.747  5781  5781 D BluetoothMapService: MAP Service closeService in
10-26 18:06:46.748  5781  5781 D BluetoothMapMasInstance0: MAP Service shutdown
,10-26 18:06:46.748  5781  5781 D ObexServerSockets0: shutdown(block = true)
10-26 18:06:46.749  5781  5781 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-26 18:06:46.749  5781  5933 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,10-26 18:06:46.750  5781  5781 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-26 18:06:46.750  5781  5921 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-26 18:06:46.752  5781  5934 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-26 18:06:46.753  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:46.753  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:46.753  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:46.753  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:46.753  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:46.753  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:46.753  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:46.753  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:46.753  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 18:06:46.753  5781  5781 I BtOppRfcommListener: stopping Accept Thread
10-26 18:06:46.754  5781  5943 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 18:06:46.754  5781  5943 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-26 18:06:46.755  5781  5912 D BluetoothAdapterProperties: Scan Mode:20
10-26 18:06:46.756  5781  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-26 18:06:46.756  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:46.756  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:46.762  5781  5781 D HeadsetService: Received stop request...Stopping profile...
10-26 18:06:46.764  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:46.764  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:46.764  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:46.764  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:46.764  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:46.764  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:46.764  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:46.764  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:46.764  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 18:06:46.765  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 18:06:46.765  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:46.766  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:46.769  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 18:06:46.769  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:46.769  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:46.769  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:46.769  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:46.769  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 18:06:46.769  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:46.769  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:46.769  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:46.770  5659  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 18:06:46.770  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:46.774  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:46.774  3122  3990 D BluetoothHeadset: Proxy object disconnected
10-26 18:06:46.774  5781  5781 D A2dpService: Received stop request...Stopping profile...
10-26 18:06:46.775  3754  3785 D BluetoothHeadset: Proxy object disconnected
10-26 18:06:46.775  5781  5928 D A2dpStateMachine: Exit Disconnected: -1
10-26 18:06:46.776  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:46.776  5722  5735 D BluetoothHeadset: Proxy object disconnected
10-26 18:06:46.776   929   929 D BluetoothHeadset: Proxy object disconnected
10-26 18:06:46.777   929   929 D BluetoothHeadset: Proxy object disconnected
10-26 18:06:46.777   929   929 D BluetoothHeadset: Proxy object disconnected
10-26 18:06:46.777   929   929 D BluetoothA2dp: Proxy object disconnected
10-26 18:06:46.778  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:46.779  5781  5781 D HidService: Received stop request...Stopping profile...
10-26 18:06:46.779  5781  5781 D HidService: Stopping Bluetooth HidService
10-26 18:06:46.781  5781  5781 D HealthService: Received stop request...Stopping profile...
10-26 18:06:46.782  3122  3122 D HeadsetProfile: Bluetooth service disconnected
10-26 18:06:46.782  5781  5781 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:46.782  5781  5781 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:46.782  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:46.782  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:46.782  3122  3122 D BluetoothA2dp: Proxy object disconnected
10-26 18:06:46.782  3122  3122 D BluetoothInputDevice: Proxy object disconnected
10-26 18:06:46.783  3122  3122 D HidProfile: Bluetooth service disconnected
,10-26 18:06:46.786  5781  5781 D PanService: Received stop request...Stopping profile...
10-26 18:06:46.786  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 18:06:46.787  3122  3122 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 18:06:46.787  3122  3122 D PanProfile: Bluetooth service disconnected
,10-26 18:06:46.788  5781  5781 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:46.788  5781  5781 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:46.788  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 18:06:46.789  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 18:06:46.791  5781  5781 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-26 18:06:46.791  5781  5781 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 18:06:46.791  5781  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 18:06:46.791  5781  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 18:06:46.791  5781  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 18:06:46.792  5722  5722 D DockEventReceiver: finishStartingService: stopping service
10-26 18:06:46.792  5781  5781 D BluetoothMapService: Received stop request...Stopping profile...
10-26 18:06:46.792  5781  5781 D BluetoothMapService: stop()
10-26 18:06:46.793  5781  5781 D BluetoothMapAppObserver: deinitObservers()
10-26 18:06:46.793  5781  5781 D BluetoothMapAppObserver: removeReceiver()
10-26 18:06:46.793  5722  5722 D HeadsetProfile: Bluetooth service disconnected
10-26 18:06:46.793  5722  5722 D BluetoothA2dp: Proxy object disconnected
10-26 18:06:46.793  5722  5722 D BluetoothInputDevice: Proxy object disconnected
10-26 18:06:46.793  5722  5722 D HidProfile: Bluetooth service disconnected
,10-26 18:06:46.794  5781  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 18:06:46.794  5722  5722 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 18:06:46.794  5722  5722 D PanProfile: Bluetooth service disconnected
10-26 18:06:46.794  5781  5912 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-26 18:06:46.801  3122  3122 D BluetoothMap: Proxy object disconnected
,10-26 18:06:46.801  3122  3122 D MapProfile: Bluetooth service disconnected
10-26 18:06:46.801  5722  5722 D BluetoothMap: Proxy object disconnected
10-26 18:06:46.801  5722  5722 D MapProfile: Bluetooth service disconnected
,10-26 18:06:46.802  5781  5781 D SapService: Received stop request...Stopping profile...
,10-26 18:06:46.802  5781  5781 V SapService: stop()
10-26 18:06:46.804  5781  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-26 18:06:46.804  5781  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 18:06:46.804  5781  5781 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:46.804  5781  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 18:06:46.804  5781  5781 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:46.804  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 18:06:46.804  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 18:06:46.804  5781  5919 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 18:06:46.804  5781  5919 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 18:06:46.804  5781  5919 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 18:06:46.804  5781  5919 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 18:06:46.804  5781  5781 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 18:06:46.804  5781  5781 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-26 18:06:46.805  5781  5912 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 18:06:46.805  5781  5781 V BluetoothAdapterState: isTurningOff()=true
,10-26 18:06:46.805  5781  5781 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:46.805  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:46.805  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:46.805  5781  5781 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-26 18:06:46.805  5781  5912 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-26 18:06:46.805  5781  5781 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 18:06:46.807  3122  3122 D BluetoothPbap: Proxy object disconnected
10-26 18:06:46.807  3122  3122 D PbapServerProfile: Bluetooth service disconnected
,10-26 18:06:46.808  5781  5781 V BluetoothAdapterState: isTurningOff()=true
,10-26 18:06:46.808  5781  5781 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:46.808  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:46.809  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:46.809  5781  5781 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 18:06:46.809  5781  5781 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 18:06:46.810  5722  5722 D BluetoothPbap: Proxy object disconnected
10-26 18:06:46.810  5722  5722 D PbapServerProfile: Bluetooth service disconnected
10-26 18:06:46.810  5781  5781 D BluetoothMapService: MAP Service closeService in
,10-26 18:06:46.810  5781  5781 V BluetoothAdapterState: isTurningOff()=true
10-26 18:06:46.810  5781  5781 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:46.810  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:46.810  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:46.810  5781  5781 D BluetoothMapService: cleanup()
10-26 18:06:46.810  5781  5781 D BluetoothMapService: MAP Service closeService in
10-26 18:06:46.810  5781  5781 V BluetoothAdapterState: isTurningOff()=true
,10-26 18:06:46.810  5781  5781 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:46.810  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:46.811  5781  5781 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:46.812  5781  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 18:06:46.812  5781  5908 D BluetoothAdapterProperties: Setting state to 15
10-26 18:06:46.812  5781  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-26 18:06:46.812  5781  5908 I BluetoothAdapterState: Entering BleOnState
10-26 18:06:46.812  5722  5733 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 18:06:46.813  3122  3133 D BluetoothMap: onBluetoothStateChange: up=false
10-26 18:06:46.814  3122  3990 D BluetoothPan: onBluetoothStateChange on: false
10-26 18:06:46.816  5722  5735 D BluetoothPan: onBluetoothStateChange on: false
10-26 18:06:46.816   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 18:06:46.817  3122  3135 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 18:06:46.817  5722  5733 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 18:06:46.818  3754  4021 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 18:06:46.818  3122  3133 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 18:06:46.818  5722  5735 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 18:06:46.819  5722  5733 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 18:06:46.819  3122  3990 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 18:06:46.820   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 18:06:46.820  5722  5735 D BluetoothMap: onBluetoothStateChange: up=false
10-26 18:06:46.820   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 18:06:46.821  3122  3135 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 18:06:46.821   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 18:06:46.822  5781  5908 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-26 18:06:46.822  5781  5908 D BluetoothAdapterProperties: Setting state to 16
10-26 18:06:46.822  5781  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-26 18:06:46.822  5781  5908 D BluetoothAdapterProperties: onBleDisable
10-26 18:06:46.822  5781  5908 I BluetoothAdapterState: Entering PendingCommandState
10-26 18:06:46.823  5781  5909 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-26 18:06:46.826  5781  5919 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-26 18:06:46.826  5781  5919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 18:06:46.826  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 18:06:46.826  5781  5912 D BluetoothAdapterProperties: Scan Mode:20
,10-26 18:06:46.828  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:46.829  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:46.831  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:46.832  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 18:06:46.833  5722  5722 D DockEventReceiver: finishStartingService: stopping service
10-26 18:06:46.834  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:46.835  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:46.838  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:47.041  5781  5912 I bt_hci  : shut_down
,10-26 18:06:47.044   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:47.051  5781  5916 D bt_hwcfg: hw_epilog_process
,10-26 18:06:47.052  5781  5916 I bt_vendor: low_power_mode_cb
,10-26 18:06:47.055  5781  5916 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-26 18:06:47.055  5781  5916 I bt_vendor: epilog_cb
10-26 18:06:47.055  5781  5916 I bt_hci  : epilog_finished_callback
,10-26 18:06:47.057  5781  5912 I bt_hci_h4: hal_close
,10-26 18:06:47.058  5781  5912 I bt_userial_vendor: device fd = 54 close
,10-26 18:06:47.170  5781  5909 D bt_stack_manager: event_shut_down_stack finished.
,10-26 18:06:47.170  5781  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-26 18:06:47.174  5781  5908 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-26 18:06:47.175  5781  5781 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 18:06:47.176  5781  5781 D BtGatt.GattService: Received stop request...Stopping profile...
,10-26 18:06:47.176  5781  5781 D BtGatt.GattService: stop()
10-26 18:06:47.176  5781  5781 D BtGatt.AdvertiseManager: advertise clients cleared
10-26 18:06:47.179  5781  5781 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:47.179  5781  5781 V BluetoothAdapterState: isTurningOn()=false
,10-26 18:06:47.179  5781  5781 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:47.180  5781  5781 V BluetoothAdapterState: isBleTurningOff()=true
10-26 18:06:47.180  5781  5908 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,10-26 18:06:47.180  5781  5908 D BluetoothAdapterProperties: Setting state to 10
,10-26 18:06:47.181  5781  5908 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-26 18:06:47.182  5781  5908 I BluetoothAdapterState: Entering OffState
10-26 18:06:47.183   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-26 18:06:47.197  5781  5781 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-26 18:06:47.197  5781  5781 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-26 18:06:47.197  5781  5781 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-26 18:06:47.199  5781  5909 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-26 18:06:47.212  5781  5781 I art     : System.exit called, status: 0
,10-26 18:06:47.212  5781  5781 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-26 18:06:47.244   929  3802 I ActivityManager: Process com.android.bluetooth (pid 5781) has died
,10-26 18:06:48.045   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:49.046   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:06:50.047   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-26 18:06:50.320  3577  3577 I ConfigService: onDestroy
,10-26 18:06:51.736  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:06:51.737  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:06:51.742  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:51.742  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2bd0f0e removed from the list
10-26 18:06:51.742  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:06:51.742  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:51.743  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:51.750  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 18:06:51.750  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@151af3c added. We now have 4 listener(s)
10-26 18:06:51.750  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:06:51.752  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:06:51.752  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@151af3c removed from the list
10-26 18:06:51.752  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:06:51.752  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:06:51.753  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:06:51.756  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:06:51.756  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@79414c5 added. We now have 4 listener(s)
10-26 18:06:51.756  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 18:06:56.766  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:56.802   929   946 I ActivityManager: Start proc 5955:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-26 18:06:56.886  5955  5955 D AdapterServiceConfig: Adding HeadsetService
,10-26 18:06:56.887  5955  5955 D AdapterServiceConfig: Adding A2dpService
10-26 18:06:56.887  5955  5955 D AdapterServiceConfig: Adding HidService
10-26 18:06:56.887  5955  5955 D AdapterServiceConfig: Adding HealthService
10-26 18:06:56.887  5955  5955 D AdapterServiceConfig: Adding PanService
,10-26 18:06:56.887  5955  5955 D AdapterServiceConfig: Adding GattService
10-26 18:06:56.888  5955  5955 D AdapterServiceConfig: Adding BluetoothMapService
10-26 18:06:56.888  5955  5955 D AdapterServiceConfig: Adding SapService
,10-26 18:06:56.897   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee37742:true
,10-26 18:06:56.897  5955  5955 D BluetoothAdapterState: make() - Creating AdapterState
,10-26 18:06:56.900  5955  5955 I bt_bluedroid: init
,10-26 18:06:56.901  5955  5967 I BluetoothAdapterState: Entering OffState
,10-26 18:06:56.903  5955  5968 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-26 18:06:56.903  5955  5968 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-26 18:06:56.903  5955  5968 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-26 18:06:56.903  5955  5968 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-26 18:06:56.904  5955  5955 I bt_bluedroid: get_profile_interface socket
,10-26 18:06:56.905  5955  5971 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
10-26 18:06:56.905  5955  5955 I bt_bluedroid: get_profile_interface sdp
10-26 18:06:56.907  5955  5971 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 18:06:56.911  5955  5966 I bt_bluedroid: config_hci_snoop_log
,10-26 18:06:56.912   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 18:06:56.917  5955  5967 D BluetoothAdapterState: Current state: OFF, message: 0
,10-26 18:06:56.917  5955  5967 D BluetoothAdapterProperties: Setting state to 14
10-26 18:06:56.917  5955  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-26 18:06:56.918  5955  5967 D BluetoothBondStateMachine: make
,10-26 18:06:56.920  5955  5972 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 18:06:56.923  5955  5967 I BluetoothAdapterState: Entering PendingCommandState
,10-26 18:06:56.924  5955  5955 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-26 18:06:56.926  5955  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
10-26 18:06:56.927  5955  5955 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 18:06:56.927  5955  5955 D BtGatt.GattService: Received start request. Starting profile...
10-26 18:06:56.927  5955  5955 D BtGatt.GattService: start()
10-26 18:06:56.927  5955  5955 I bt_bluedroid: get_profile_interface gatt
,10-26 18:06:56.928  5955  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:56.929  5955  5955 D BtGatt.AdvertiseManager: advertise manager created
,10-26 18:06:56.934  5955  5955 V BluetoothAdapterState: isTurningOff()=false
,10-26 18:06:56.934  5955  5955 V BluetoothAdapterState: isTurningOn()=false
10-26 18:06:56.934  5955  5955 V BluetoothAdapterState: isBleTurningOn()=true
10-26 18:06:56.934  5955  5955 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 18:06:56.935  5955  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-26 18:06:56.936  5955  5967 I bt_bluedroid: bt_bluedroid
10-26 18:06:56.936  5955  5968 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-26 18:06:56.936  5955  5968 I bt_hci  : start_up
,10-26 18:06:56.942  5955  5968 I bt_vendor: alloc value 0xf412d871
,10-26 18:06:56.942  5955  5968 I bt_vendor: init
10-26 18:06:56.943  5955  5968 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 18:06:56.943  5955  5968 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 18:06:57.052  5955  5968 D bt_hci  : start_up starting async portion
10-26 18:06:57.053  5955  5975 I bt_hci  : event_finish_startup
10-26 18:06:57.053  5955  5975 I bt_hci_h4: hal_open
10-26 18:06:57.053  5955  5975 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-26 18:06:57.053  5976  5976 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 18:06:57.059  5955  5975 I bt_userial_vendor: device fd = 54 open
,10-26 18:06:57.075  5955  5975 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 18:06:57.078  5955  5975 D bt_hwcfg: Chipset BCM4358A3
,10-26 18:06:57.078  5955  5975 D bt_hwcfg: Target name = [BCM4358A3]
10-26 18:06:57.079  5955  5975 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 18:06:57.584  5955  5975 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-26 18:06:57.585  5955  5975 D bt_hwcfg: Settlement delay -- 100 ms
10-26 18:06:57.585  5955  5975 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 18:06:57.719  5955  5975 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 18:06:57.719  5955  5975 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,10-26 18:06:57.722  5955  5975 I bt_hwcfg: vendor lib fwcfg completed
10-26 18:06:57.722  5955  5975 I bt_vendor: firmware callback
10-26 18:06:57.722  5955  5975 I bt_hci  : firmware_config_callback
,10-26 18:06:57.731  5955  5978 I bt_btu  : btu_task pending for preload complete event
10-26 18:06:57.731  5955  5978 I bt_btu_task: Bluetooth chip preload is complete
10-26 18:06:57.731  5955  5978 I bt_btu  : btu_task received preload complete event
,10-26 18:06:57.737  5955  5978 I         : BTE_InitTraceLevels -- TRC_HCI
,10-26 18:06:57.738  5955  5978 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-26 18:06:57.738  5955  5978 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-26 18:06:57.738  5955  5978 I         : BTE_InitTraceLevels -- TRC_AVDT
10-26 18:06:57.738  5955  5978 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-26 18:06:57.738  5955  5978 I         : BTE_InitTraceLevels -- TRC_A2D
10-26 18:06:57.738  5955  5978 I         : BTE_InitTraceLevels -- TRC_BNEP
10-26 18:06:57.738  5955  5978 I         : BTE_InitTraceLevels -- TRC_BTM
10-26 18:06:57.739  5955  5978 I         : BTE_InitTraceLevels -- TRC_GAP
10-26 18:06:57.739  5955  5978 I         : BTE_InitTraceLevels -- TRC_PAN
,10-26 18:06:57.739  5955  5978 I         : BTE_InitTraceLevels -- TRC_SDP
10-26 18:06:57.739  5955  5978 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 18:06:57.739  5955  5978 I         : BTE_InitTraceLevels -- TRC_SMP
10-26 18:06:57.739  5955  5978 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-26 18:06:57.739  5955  5978 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 18:06:57.832  5955  5978 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40ab549
10-26 18:06:57.832  5955  5978 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40ab549 
,10-26 18:06:57.850  5955  5971 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-26 18:06:57.852  5955  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 18:06:57.853  5955  5971 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,10-26 18:06:57.855  5955  5971 D BluetoothAdapterProperties: Name is: Nexus 6P
10-26 18:06:57.858  5955  5971 D BluetoothAdapterProperties: Scan Mode:20
10-26 18:06:57.858  5955  5971 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 18:06:57.858  5955  5971 D bt_hci  : do_postload posting postload work item
10-26 18:06:57.859  5955  5975 I bt_hci  : event_postload
10-26 18:06:57.859  5955  5975 I bt_vendor: sco_config_cb
10-26 18:06:57.859  5955  5975 I bt_hci  : sco_config_callback postload finished.
,10-26 18:06:57.860  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:57.862  5955  5971 D bt_bte_conf: Device ID record 1 : primary
10-26 18:06:57.862  5955  5971 D bt_bte_conf:   vendorId            = 000f
10-26 18:06:57.862  5955  5971 D bt_bte_conf:   vendorIdSource      = 0001
10-26 18:06:57.862  5955  5971 D bt_bte_conf:   product             = 1200
10-26 18:06:57.862  5955  5971 D bt_bte_conf:   version             = 1436
10-26 18:06:57.862  5955  5971 D bt_bte_conf:   clientExecutableURL = 
10-26 18:06:57.862  5955  5971 D bt_bte_conf:   serviceDescription  = 
10-26 18:06:57.863  5955  5971 D bt_bte_conf:   documentationURL    = 
,10-26 18:06:57.863  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:57.863  5955  5971 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-26 18:06:57.863  5955  5968 D bt_stack_manager: event_start_up_stack finished
10-26 18:06:57.864  5955  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-26 18:06:57.864  5955  5967 D BluetoothAdapterProperties: Setting state to 15
10-26 18:06:57.864  5955  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 18:06:57.865  5955  5967 I BluetoothAdapterState: Entering BleOnState
,10-26 18:06:57.866  5955  5975 I bt_vendor: low_power_mode_cb
10-26 18:06:57.869  5955  5967 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-26 18:06:57.870  5955  5967 D BluetoothAdapterProperties: Setting state to 11
,10-26 18:06:57.889  5955  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-26 18:06:57.896  5955  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
10-26 18:06:57.897  5955  5955 D HeadsetService: Received start request. Starting profile...
,10-26 18:06:57.901  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:57.901  5955  5955 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-26 18:06:57.903  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:57.905  5955  5955 D HeadsetStateMachine: make
,10-26 18:06:57.908  5955  5967 I BluetoothAdapterState: Entering PendingCommandState
,10-26 18:06:57.912  5955  5955 D HeadsetStateMachine: max_hf_connections = 1
10-26 18:06:57.912  5955  5955 I bt_bluedroid: get_profile_interface handsfree
,10-26 18:06:57.912  5955  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-26 18:06:57.913  5955  5971 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-26 18:06:57.917  5955  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:57.918  5955  5955 D A2dpService: Received start request. Starting profile...
,10-26 18:06:57.918  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 18:06:57.918  5955  5955 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-26 18:06:57.918  5955  5955 I bt_bluedroid: get_profile_interface avrcp
,10-26 18:06:57.926  5955  5955 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-26 18:06:57.926  5955  5955 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-26 18:06:57.926  5955  5955 D A2dpStateMachine: make
,10-26 18:06:57.927  5955  5955 I bt_bluedroid: get_profile_interface a2dp
,10-26 18:06:57.928  5955  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-26 18:06:57.930  5955  5955 I BluetoothHidServiceJni: classInitNative: succeeds
10-26 18:06:57.930  5955  5986 D A2dpStateMachine: Enter Disconnected: -2
10-26 18:06:57.931  5955  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
10-26 18:06:57.932  5955  5955 D HidService: Received start request. Starting profile...
10-26 18:06:57.933  5955  5955 I bt_bluedroid: get_profile_interface hidhost
10-26 18:06:57.933  5955  5955 D HidService: setHidService(): set to: null
10-26 18:06:57.933  5955  5971 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf408c56d
,10-26 18:06:57.933  5955  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-26 18:06:57.933  5955  5955 I BluetoothHealthServiceJni: classInitNative: succeeds
10-26 18:06:57.934  5955  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
10-26 18:06:57.935  5955  5955 D HealthService: Received start request. Starting profile...
10-26 18:06:57.936  5955  5955 I bt_bluedroid: get_profile_interface health
10-26 18:06:57.937  5955  5955 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-26 18:06:57.939  5955  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:57.939  5955  5955 D PanService: Received start request. Starting profile...
10-26 18:06:57.940  5955  5955 D BluetoothPanServiceJni: initializeNative(L110): pan
10-26 18:06:57.940  5955  5955 I bt_bluedroid: get_profile_interface pan
,10-26 18:06:57.941  5955  5971 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-26 18:06:57.943  5955  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:06:57.943  5955  5955 D BluetoothMapService: Received start request. Starting profile...
10-26 18:06:57.943  5955  5955 D BluetoothMapService: start()
10-26 18:06:57.946  5955  5955 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-26 18:06:57.948  5955  5955 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-26 18:06:57.948  5955  5955 D BluetoothMapAppObserver: createReceiver()
10-26 18:06:57.949  5955  5955 D BluetoothMapAppObserver: initObservers()
,10-26 18:06:57.949  5955  5955 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-26 18:06:57.958  5955  5955 V SapService: SapBinder()
,10-26 18:06:57.958  5955  5955 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
10-26 18:06:57.958  5955  5955 D SapService: Received start request. Starting profile...
10-26 18:06:57.958  5955  5955 V SapService: start()
,10-26 18:06:57.960  5955  5955 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:57.960  5955  5955 V BluetoothAdapterState: isTurningOn()=true
,10-26 18:06:57.960  5955  5955 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:57.961  5955  5955 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:57.961  5955  5984 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=1
,10-26 18:06:57.961  5955  5955 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:57.961  5955  5955 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:57.961  5955  5955 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:57.961  5955  5955 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:57.961  5955  5955 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:57.961  5955  5955 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:57.961  5955  5955 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:57.961  5955  5955 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:57.962  5955  5955 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:57.963  5955  5955 V BluetoothAdapterState: isTurningOff()=false
10-26 18:06:57.963  5955  5955 V BluetoothAdapterState: isTurningOn()=true
10-26 18:06:57.963  5955  5955 V BluetoothAdapterState: isBleTurningOn()=false
10-26 18:06:57.963  5955  5955 V BluetoothAdapterState: isBleTurningOff()=false
10-26 18:06:57.964  5955  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-26 18:06:57.964  5955  5967 D BluetoothAdapterProperties: ScanMode =  20
10-26 18:06:57.964  5955  5967 D BluetoothAdapterProperties: State =  11
,10-26 18:06:57.964  5955  5967 D BluetoothAdapterProperties: Setting state to 12
,10-26 18:06:57.964  5955  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,10-26 18:06:57.965  5955  5967 I BluetoothAdapterState: Entering OnState
,10-26 18:06:57.965  5722  5733 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:57.965  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 18:06:57.965  5955  5971 D BluetoothAdapterProperties: Scan Mode:21
10-26 18:06:57.966  5955  5971 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 18:06:57.966  3122  3135 D BluetoothMap: onBluetoothStateChange: up=true
10-26 18:06:57.969  3122  3133 D BluetoothPan: onBluetoothStateChange on: true
10-26 18:06:57.970  3122  3122 D BluetoothMap: Proxy object connected
10-26 18:06:57.970  3122  3122 D MapProfile: Bluetooth service connected
10-26 18:06:57.970  3122  3122 D BluetoothMap: getConnectedDevices()
10-26 18:06:57.972  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:57.972  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:57.972  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:57.972  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:57.972  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:06:57.972  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:57.972  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:57.972  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:57.972  5722  5735 D BluetoothPan: onBluetoothStateChange on: true
10-26 18:06:57.975  3122  3122 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 18:06:57.975  3122  3122 D PanProfile: Bluetooth service connected
10-26 18:06:57.975  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:57.976   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:57.976  3122  3135 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 18:06:57.977  5955  5955 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 18:06:57.977  5955  5955 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-26 18:06:57.977  5722  5733 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 18:06:57.978  5955  5955 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 18:06:57.979  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:06:57.979  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:06:57.979  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:06:57.979  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:06:57.979  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:06:57.979  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:06:57.979  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:06:57.979  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 18:06:57.979  3754  3785 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 18:06:57.980  3122  3133 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:57.980  5722  5735 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 18:06:57.980  5955  5955 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 18:06:57.981  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 18:06:57.981  5955  5955 D ObexServerSockets: Succeed to create listening sockets 
10-26 18:06:57.982  5955  5955 D ObexServerSockets0: startAccept()
10-26 18:06:57.982  5955  5955 D ObexServerSockets0: prepareForNewConnect()
10-26 18:06:57.982  5722  5733 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 18:06:57.983  3122  3990 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 18:06:57.983  5955  5955 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 18:06:57.983  5955  5955 D BluetoothSdpJni: SDP Create record success - handle: 0
10-26 18:06:57.984  5955  5995 D ObexServerSockets0: Accepting socket connection...
,10-26 18:06:57.984  5955  5994 D ObexServerSockets0: Accepting socket connection...
10-26 18:06:57.984  5722  5722 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 18:06:57.985  5722  5722 D PanProfile: Bluetooth service connected
10-26 18:06:57.986  5722  5722 D BluetoothInputDevice: Proxy object connected
10-26 18:06:57.986  5722  5722 D HidProfile: Bluetooth service connected
10-26 18:06:57.986   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:57.986  5722  5733 D BluetoothMap: onBluetoothStateChange: up=true
10-26 18:06:57.987  3122  3122 D BluetoothA2dp: Proxy object connected
,10-26 18:06:57.989   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 18:06:57.989  3122  3133 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 18:06:57.992  5722  5722 D BluetoothA2dp: Proxy object connected
10-26 18:06:57.992  3122  3122 D BluetoothInputDevice: Proxy object connected
10-26 18:06:57.992  3122  3122 D HidProfile: Bluetooth service connected
10-26 18:06:57.993   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 18:06:57.993   929   929 D BluetoothA2dp: Proxy object connected
10-26 18:06:57.994  5659  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 18:06:57.995  5955  5955 D BluetoothMapService: onReceive
10-26 18:06:57.995  5955  5955 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 18:06:57.995  5955  5955 D BluetoothMapService: STATE_ON
,10-26 18:06:57.996  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:06:57.997  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:06:57.998   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
10-26 18:06:57.998  5955  5996 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 18:06:57.999  5722  5722 D BluetoothMap: Proxy object connected
,10-26 18:06:57.999  5722  5722 D MapProfile: Bluetooth service connected
10-26 18:06:57.999  5722  5722 D BluetoothMap: getConnectedDevices()
10-26 18:06:58.000  5955  5996 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-26 18:06:58.001  5955  5996 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-26 18:06:58.006  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 18:06:58.012  3577  3577 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 18:06:58.013  5722  5722 D DockEventReceiver: finishStartingService: stopping service
,10-26 18:06:58.020  5955  5955 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-26 18:06:58.020  5955  5955 D ObexServerSockets0: prepareForNewConnect()
10-26 18:06:58.021  5722  5722 D BluetoothPbap: Proxy object connected
10-26 18:06:58.021  5722  5722 D PbapServerProfile: Bluetooth service connected
10-26 18:06:58.021  3122  3122 D BluetoothPbap: Proxy object connected
10-26 18:06:58.021  3122  3122 D PbapServerProfile: Bluetooth service connected
,10-26 18:06:58.028  5955  6001 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 18:06:58.039  5955  6005 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 18:06:58.041  5955  6005 I BtOppRfcommListener: Accept thread started.
,10-26 18:06:58.068  3122  3990 D BluetoothHeadset: Proxy object connected
,10-26 18:06:58.068  3122  3122 D HeadsetProfile: Bluetooth service connected
,10-26 18:06:58.068  3754  4021 D BluetoothHeadset: Proxy object connected
10-26 18:06:58.069  5722  5735 D BluetoothHeadset: Proxy object connected
,10-26 18:06:58.069   929   929 D BluetoothHeadset: Proxy object connected
,10-26 18:06:58.069   929   929 D BluetoothHeadset: Proxy object connected
10-26 18:06:58.069   929   929 D BluetoothHeadset: Proxy object connected
10-26 18:06:58.071  5722  5722 D HeadsetProfile: Bluetooth service connected
,10-26 18:06:58.075   929   946 D BluetoothHeadset: Proxy object connected
,10-26 18:06:58.080  3754  3789 D BluetoothHeadset: Proxy object connected
,10-26 18:06:58.080  3122  3133 D BluetoothHeadset: Proxy object connected
10-26 18:06:58.081  3122  3122 D HeadsetProfile: Bluetooth service connected
,10-26 18:06:58.087   929   946 D BluetoothHeadset: Proxy object connected
,10-26 18:06:58.090   929   946 D BluetoothHeadset: Proxy object connected
,10-26 18:07:00.047   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:01.048   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:01.783  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:07:01.783  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:01.783  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:01.783  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 18:07:01.783  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:01.783  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:07:01.783  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:07:01.783  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 18:07:01.788  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:07:01.789  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 18:07:01.789  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@79414c5 removed from the list
,10-26 18:07:01.789  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 18:07:01.790  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:07:01.790  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:07:01.792  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 18:07:01.792  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dbf0e1a added. We now have 4 listener(s)
,10-26 18:07:01.792  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 18:07:01.795   929  3150 D WifiService: setWifiEnabled: false pid=5659, uid=10077
,10-26 18:07:01.795   929  3150 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 18:07:02.049   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:03.050   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:04.051   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:04.770   929   949 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,10-26 18:07:04.773  3790  3790 W Binder_8: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33305]" dev="sockfs" ino=33305 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:04.777  3790  3790 W Binder_8: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33305]" dev="sockfs" ino=33305 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:04.781  3636  3636 I Keyboard.Facilitator: onFinishInput()
,10-26 18:07:04.810   929   949 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
,10-26 18:07:04.810   929   949 I Adreno  : Build Date                       : 12/06/15
10-26 18:07:04.810   929   949 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 18:07:04.810   929   949 I Adreno  : Local Branch                     : mybranch17112971
10-26 18:07:04.810   929   949 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 18:07:04.810   929   949 I Adreno  : Remote Branch                    : NONE
10-26 18:07:04.810   929   949 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 18:07:04.854   381   504 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (186 us)
,10-26 18:07:05.052   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-26 18:07:05.536  5659  5659 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-26 18:07:05.536  5659  5659 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,10-26 18:07:05.576   929   949 I sensors : batch
,10-26 18:07:05.577   929   949 V KeyguardServiceDelegate: onScreenTurnedOff()
,10-26 18:07:05.581  5659  5659 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6820344 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2c11d4b, 16908290=android.view.AbsSavedState$1@2c11d4b}, android:focusedViewId=100}]}]
,10-26 18:07:05.581  5659  5659 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
10-26 18:07:05.582  5659  5659 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-26 18:07:05.582  5659  5659 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
10-26 18:07:05.583   929   949 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
10-26 18:07:05.583   929   949 I sensors : activate
10-26 18:07:05.584   929  2688 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,10-26 18:07:05.586   929   947 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,10-26 18:07:05.587   381   381 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fa5903c00
10-26 18:07:05.588   381   381 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
10-26 18:07:05.590   929  2688 I hubconnection: sensorhub said: 'activate 7 enable:0'
,10-26 18:07:05.895   381   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,10-26 18:07:05.899   381   381 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,10-26 18:07:05.900   929  3041 D SurfaceControl: Excessive delay in setPowerMode(): 314ms
,10-26 18:07:05.913   929   949 I DreamManagerService: Entering dreamland.
,10-26 18:07:05.914   929   949 I PowerManagerService: Dozing...
,10-26 18:07:05.915   929   944 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,10-26 18:07:05.950  3800  3800 W Binder_9: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[35205]" dev="sockfs" ino=35205 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 18:07:05.953  3800  3800 W Binder_9: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[35205]" dev="sockfs" ino=35205 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:05.955   929  3750 I sensors : batch
,10-26 18:07:05.955   929  3750 I sensors : activate
,10-26 18:07:05.958   929  2688 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,10-26 18:07:05.960   929  2688 I hubconnection: sensorhub said: 'activate 21 enable:1'
,10-26 18:07:05.964   515   515 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,10-26 18:07:05.992  3754  4646 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,10-26 18:07:05.992  3754  4646 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-26 18:07:05.992  3754  4646 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-26 18:07:05.992   528  1314 D         : oem-qmi: Connection accepted
10-26 18:07:05.993   528  1314 D         : oem-qmi: Waiting to accept connection
,10-26 18:07:05.995   929   929 I sensors : activate
,10-26 18:07:05.996   515  2993 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,10-26 18:07:05.999   929  2688 I hubconnection: sensorhub said: 'activate 31 enable:0'
,10-26 18:07:06.000  3754  4646 D         : oem_qmi_lib:output 0
10-26 18:07:06.000  3754  4646 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-26 18:07:06.022  3754  4646 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,10-26 18:07:06.022  3754  4646 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
10-26 18:07:06.022  3754  4646 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
10-26 18:07:06.023   528  1314 D         : oem-qmi: Connection accepted
10-26 18:07:06.023   528  1314 D         : oem-qmi: Waiting to accept connection
,10-26 18:07:06.029  3754  4646 D         : oem_qmi_lib:output 0
10-26 18:07:06.029  3754  4646 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,10-26 18:07:06.805  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:07:06.806   929   939 D WifiService: setWifiEnabled: true pid=5659, uid=10077
,10-26 18:07:06.806   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 18:07:06.814   510   924 D SoftapController: Softap fwReload - Ok
,10-26 18:07:06.820   510   924 D CommandListener: Setting iface cfg
,10-26 18:07:06.820   510   924 D CommandListener: Trying to bring down wlan0
,10-26 18:07:06.822   510   924 D CommandListener: Clearing all IP addresses on wlan0
,10-26 18:07:06.828   929  2981 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 18:07:07.458   929  2981 D wifi    : set interface wlan0 flags (UP)
,10-26 18:07:07.459   929  2981 I WifiHAL : Initializing wifi
10-26 18:07:07.460   929  2981 I WifiHAL : Creating socket
,10-26 18:07:07.469   929  2981 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-26 18:07:07.469   929  2981 D wifi    : Did set static halHandle = 0x7f6b504080
,10-26 18:07:07.469   929  2981 D wifi    : halHandle = 0x7f6b504080, mVM = 0x7f87acd140, mCls = 0x101832
,10-26 18:07:07.469   929  2981 D wifi    : array field set
,10-26 18:07:07.469   929  2981 I WifiNative-HAL: interface[0] = wlan0
,10-26 18:07:07.471   929  6016 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547261268096
,10-26 18:07:07.472   929  6016 D wifi    : waitForHalEvents called, vm = 0x7f87acd140, obj = 0x101832, env = 0x7f68c9ae80
10-26 18:07:07.474   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-26 18:07:07.539  6017  6017 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 18:07:07.572   929  2981 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 18:07:07.576  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:07:07.586  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 18:07:07.617  6017  6017 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 18:07:07.690  6017  6017 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 18:07:07.690  6017  6017 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 18:07:07.712   929  2981 D WifiConfigStore: Loading config and enabling all networks 
,10-26 18:07:07.716  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:07:07.716  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:07.716  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:07.716  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:07.716  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:07.716  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:07:07.716  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:07:07.716  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 18:07:07.719  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:07:07.724  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:07:07.724  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:07.724  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:07.724  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:07.724  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:07.724  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 18:07:07.724  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 18:07:07.724  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 18:07:07.726  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 18:07:07.735   929  2981 D WifiConfigStore: loaded 0 passpoint configs
,10-26 18:07:07.735   929  2981 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
10-26 18:07:07.736   929  2981 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-26 18:07:07.736   929  2981 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-26 18:07:07.737   929  2981 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
10-26 18:07:07.737   929  2981 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
10-26 18:07:07.738   929  2981 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-26 18:07:07.738   929  2981 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
10-26 18:07:07.739   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
10-26 18:07:07.739   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
10-26 18:07:07.739   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-26 18:07:07.739   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,10-26 18:07:07.739   929  2981 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,10-26 18:07:07.742   929  2981 D WifiNative-HAL: Setting external_sim to 1
,10-26 18:07:07.742  4414  4414 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 18:07:07.743   929  2981 D wifi    : setting dfs flag to true, 0x7f7091f600
10-26 18:07:07.743   929  2981 D WifiStateMachine: Setting OUI to DA-A1-19
10-26 18:07:07.743   929  2981 D wifi    : setting scan oui 0x7f7091f600
10-26 18:07:07.743   929  2981 D WifiHAL : Sending mac address OUI
,10-26 18:07:07.747   929  2981 E native  : do suspend true
,10-26 18:07:07.753   929   929 D RttService: SCAN_AVAILABLE : 3
10-26 18:07:07.753   929  2981 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-26 18:07:07.753   510   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-26 18:07:07.753   929  3036 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 18:07:07.754   510   924 D CommandListener: Setting iface cfg
,10-26 18:07:07.760   929  2969 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '155 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 155 Failed to set address (No such device)'
10-26 18:07:07.760   929  2969 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-26 18:07:07.763   929  2969 D WifiNative-HAL: p2pGetDeviceAddress
,10-26 18:07:07.763   929  2969 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,10-26 18:07:07.787   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=151602 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=19 mControllerEnergyUsed=72 }
,10-26 18:07:10.608  3690  4365 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,10-26 18:07:10.897  6017  6017 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-26 18:07:10.923   929  2981 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-26 18:07:10.932   929  2981 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
10-26 18:07:10.932   929  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 18:07:10.949   929  2981 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-26 18:07:10.997   929  2981 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-26 18:07:11.340  6017  6017 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-26 18:07:11.378  6017  6017 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-26 18:07:11.379  6017  6017 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-26 18:07:11.391   929  2981 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 18:07:11.391   929  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-26 18:07:11.392   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-26 18:07:11.408   929  2981 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 18:07:11.418   510   924 D CommandListener: Setting iface cfg
,10-26 18:07:11.424   929  2981 D WifiStateMachine: Start Dhcp Watchdog 3
,10-26 18:07:11.428   929  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-26 18:07:11.434   929  6031 D DhcpClient: Receive thread started
,10-26 18:07:11.516   929  2981 E native  : do suspend false
,10-26 18:07:11.532   929  6030 D DhcpClient: Broadcasting DHCPDISCOVER
,10-26 18:07:11.553   929  6031 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.111, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-26 18:07:11.554   929  6030 D DhcpClient: Got pending lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-26 18:07:11.556   929  6030 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.111 serverid=192.168.1.1
,10-26 18:07:11.572   929  6031 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.111, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-26 18:07:11.573   929  6030 D DhcpClient: Confirmed lease: IP address 192.168.1.111/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-26 18:07:11.577   510   924 D CommandListener: Setting iface cfg
,10-26 18:07:11.581   929  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-26 18:07:11.588   929  2981 E native  : do suspend true
,10-26 18:07:11.589   929  6030 D DhcpClient: Scheduling renewal in 86399s
,10-26 18:07:11.605   929  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-26 18:07:11.607   929  2981 D WifiConfigStore: No blacklist allowed without epno enabled
,10-26 18:07:11.607   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-26 18:07:11.609   929  2983 D ConnectivityService: Adding iface wlan0 to network 102
10-26 18:07:11.613   929  2981 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-26 18:07:11.659   929  2983 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-26 18:07:11.659   929  2983 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-26 18:07:11.661   929  2983 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-26 18:07:11.663   929  2983 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-26 18:07:11.664   929  2983 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-26 18:07:11.671   929  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-26 18:07:11.676   929  2983 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-26 18:07:11.677   929  2983 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,10-26 18:07:11.677   929  2983 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-26 18:07:11.677   929  2983 D ConnectivityService:    accepting network in place of null
,10-26 18:07:11.677   929  2981 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-26 18:07:11.677   929  2981 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 18:07:11.678   929  2983 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 18:07:11.690   929  6029 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155506, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-26 18:07:11.701   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 18:07:11.723   510   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 18:07:11.727   929  2983 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-26 18:07:11.727   929  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-26 18:07:11.727  3714  3839 W QCNEJ   : |CORE| network available: 102
10-26 18:07:11.728   929  2983 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-26 18:07:11.729   929   946 D Tethering: MasterInitialState.processMessage what=3
10-26 18:07:11.729  3714  3839 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-26 18:07:11.731  3714  3839 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-26 18:07:11.731  3714  3839 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-26 18:07:11.738  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:07:11.738  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:11.738  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:11.738  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:11.738  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:11.738  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.738  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:07:11.738  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:07:11.741  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 18:07:11.745  3936  3936 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
10-26 18:07:11.747  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:07:11.747  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:11.747  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:11.747  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:11.747  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:11.747  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.747  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:07:11.747  5659  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:07:11.748  3968  3968 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 18:07:11.749  5659  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.752  3968  3968 D SystemUpdateService: onCreate
,10-26 18:07:11.755  3968  3968 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 18:07:11.764  3968  3968 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-26 18:07:11.769  3968  5381 I iu.UploadsManager: num queued entries: 0
,10-26 18:07:11.770  3968  5381 I iu.UploadsManager: num updated entries: 0
10-26 18:07:11.770  3968  5381 I iu.SyncManager: NEXT; no task
,10-26 18:07:11.771   929  6028 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-26 18:07:11.774  3968  6040 I SystemUpdateService: active receiver: enabled
,10-26 18:07:11.775  3968  3968 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 18:07:11.777  3968  3968 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-26 18:07:11.778  5795  5795 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-26 18:07:11.781  5795  5795 D SprintDMHelper: simOperator: 
10-26 18:07:11.781  5795  5795 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 18:07:11.804  3968  6040 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 18:07:11.810  3968  6040 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-26 18:07:11.810  3968  6040 I SystemUpdateService: now status is 0 (complete)
10-26 18:07:11.810  3968  6040 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 18:07:11.810  3968  6040 I SystemUpdateService: file has been verified
10-26 18:07:11.810  3968  6040 I SystemUpdateService: OTA package size = 21989297
,10-26 18:07:11.817  3968  6040 I SystemUpdateService: showing system update notification
,10-26 18:07:11.818  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 18:07:11.818  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:11.818  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:11.818  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:11.818  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:11.818  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.818  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:07:11.818  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:07:11.821  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.821  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.821  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dbf0e1a removed from the list
10-26 18:07:11.821  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:07:11.821  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.821  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.823   929  6028 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 26 Oct 2016 16:07:11 GMT], X-Android-Received-Millis=[1477498031822], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477498031793]}
10-26 18:07:11.823   929  2983 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-26 18:07:11.823   929  2983 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-26 18:07:11.823   929  2983 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-26 18:07:11.824  5659  5706 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-26 18:07:11.824   929  2983 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-26 18:07:11.825  5659  5706 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-26 18:07:11.827  5659  5706 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6820344 Bundle[{}]
10-26 18:07:11.827  5659  5706 I io.jxcore.node.LifeCycleMonitor: start: OK
10-26 18:07:11.827  5659  5706 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-26 18:07:11.828  5659  5706 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-26 18:07:11.828  5659  5706 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-26 18:07:11.828   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
10-26 18:07:11.829  5659  5706 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-26 18:07:11.829  5659  5706 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-26 18:07:11.832  3968  3968 D SystemUpdateService: onDestroy
,10-26 18:07:11.837  5659  5706 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,10-26 18:07:11.837  5659  5706 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-26 18:07:11.837  5659  5706 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 166)
,10-26 18:07:11.839  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 18:07:11.839  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6288328 added. We now have 3 listener(s)
,10-26 18:07:11.841  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 18:07:11.841  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:11.841  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:11.841  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:11.841  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@263841 added. We now have 4 listener(s)
10-26 18:07:11.841  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 18:07:11.842  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 18:07:11.845  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 18:07:11.849  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:07:11.849  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:11.849  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:11.849  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:11.849  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:11.849  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.849  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:07:11.849  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 18:07:11.852  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 18:07:11.852  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:07:11.852  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:07:11.852  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c824327 added. We now have 4 listener(s)
,10-26 18:07:11.854  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,10-26 18:07:11.854  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:11.854  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:11.854  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:11.854  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:11.855  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b16a9d4 added. We now have 5 listener(s)
,10-26 18:07:11.855  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:07:11.855  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:07:11.855  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:07:11.855  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:07:11.855  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:11.855  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.855  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:07:11.855  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 18:07:11.855  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:11.856  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6288328 removed from the list
10-26 18:07:11.856  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.856  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@263841 removed from the list
10-26 18:07:11.857  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:11.857  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:07:11.857  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 18:07:11.857  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 18:07:11.857  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.857  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:07:11.858  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.858  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:07:11.858  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.859  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:11.859  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:11.859  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.859  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@263841 not in the list
10-26 18:07:11.859  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.859  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.859  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.860  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:07:11.860  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.860  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.860  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:11.860  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:11.860  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.860  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b16a9d4 removed from the list
10-26 18:07:11.860  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:11.860  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.860  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.860  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 18:07:11.860  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:11.860  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c824327 removed from the list
10-26 18:07:11.860  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:07:11.861  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5d177d added. We now have 3 listener(s)
10-26 18:07:11.862  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:07:11.862  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:11.862  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:11.862  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:11.862  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2794672 added. We now have 4 listener(s)
10-26 18:07:11.862  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 18:07:11.862  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 18:07:11.864  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 18:07:11.867  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:07:11.867  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:11.867  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:11.867  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:11.867  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:11.867  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.867  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:07:11.867  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:07:11.868  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.868  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-26 18:07:11.869  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:07:11.869  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e8f40 added. We now have 4 listener(s)
10-26 18:07:11.870  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:07:11.870  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:11.870  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:11.870  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:11.870  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c28ae79 added. We now have 5 listener(s)
10-26 18:07:11.870  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:07:11.870  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 18:07:11.870  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 18:07:11.870  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 18:07:11.870  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:07:11.870  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 18:07:11.870  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:11.872  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 18:07:11.872  5659  5706 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 18:07:11.872  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 18:07:11.873  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:11.875  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 18:07:11.875  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 18:07:11.875  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 18:07:11.877  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.877  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 18:07:11.877  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 18:07:11.877  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 18:07:11.877  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 18:07:11.877  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.878  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:07:11.880  5955  5983 D BtGatt.GattService: registerClient() - UUID=f4ba7625-a2d7-4c54-8934-8572dd2e1b21
,10-26 18:07:11.880  5955  5971 D BtGatt.GattService: onClientRegistered() - UUID=f4ba7625-a2d7-4c54-8934-8572dd2e1b21, clientIf=5
10-26 18:07:11.881  5659  5669 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 18:07:11.881  5955  5992 D BtGatt.GattService: start scan with filters
,10-26 18:07:11.884  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-26 18:07:11.884  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.884  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 18:07:11.884  5955  5974 D BtGatt.ScanManager: handling starting scan
10-26 18:07:11.884  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.884  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.885  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 18:07:11.885  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 18:07:11.885  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.885  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:07:11.885  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 18:07:11.885  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.886  5955  5974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e881f1
,10-26 18:07:11.887  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:07:11.887  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:07:11.887  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.887  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:07:11.887  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.887  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.887  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 18:07:11.888  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-26 18:07:11.888  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.890  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.890  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.890  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.890  5659  5706 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-26 18:07:11.890  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 18:07:11.890  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 18:07:11.890  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.890  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 18:07:11.890  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:07:11.890  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-26 18:07:11.890  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 18:07:11.890  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 18:07:11.890  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 18:07:11.891  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.891  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.891  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 18:07:11.892  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:07:11.892  5955  5983 D BtGatt.GattService: stopScan() - queue size =1
10-26 18:07:11.893  5955  5992 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 18:07:11.893  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 18:07:11.893  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.893  5955  5971 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,10-26 18:07:11.893  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 18:07:11.893  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.893  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.893  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.893  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 18:07:11.893  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 18:07:11.893  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.893  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.893  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-26 18:07:11.894  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.894  5955  5974 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
,10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-58,5,main], id: 58
,10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.895  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 18:07:11.895  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 18:07:11.896  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:07:11.896  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.897  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.897  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.897  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.897  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:07:11.897  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:07:11.897  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:07:11.899  5955  5971 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 18:07:11.899  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:07:11.899  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.899  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:07:11.899  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:07:11.899  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:11.899  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.899  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:07:11.899  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:07:11.899  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:11.899  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5d177d removed from the list
10-26 18:07:11.899  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.899  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2794672 removed from the list
10-26 18:07:11.899  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:07:11.899  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.900  5955  5974 D BtGatt.ScanManager: Starting BLE batch scan
10-26 18:07:11.900  5955  5974 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 18:07:11.900  5659  5706 W, org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.900  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.900  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.901  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.901  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.901  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.901  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:11.901  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:11.901  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.901  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2794672 not in the list
10-26 18:07:11.902  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.902  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.902  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.902  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.903  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.903  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.903  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:11.903  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:11.903  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.903  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c28ae79 removed from the list
10-26 18:07:11.903  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:11.903  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.903  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.903  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:07:11.903  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:11.903  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e8f40 removed from the list
10-26 18:07:11.903  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:07:11.904  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87cb935 added. We now have 3 listener(s)
10-26 18:07:11.905  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:07:11.905  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:11.905  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:11.905  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:11.906  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18731ca added. We now have 4 listener(s)
10-26 18:07:11.906  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:07:11.908  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 18:07:11.910  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:07:11.910  5955  5971 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 18:07:11.910  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.913  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:07:11.913  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:11.913  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:11.913  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:11.913  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:11.913  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.913  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:07:11.913  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:07:11.914  5955  5971 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 18:07:11.914  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.916  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.916  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:07:11.916  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:07:11.916  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e170658 added. We now have 4 listener(s)
10-26 18:07:11.917  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:07:11.917  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:11.917  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:11.917  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:11.917  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ccb3b1 added. We now have 5 listener(s)
10-26 18:07:11.917  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:07:11.918  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 18:07:11.918  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 18:07:11.918  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 18:07:11.918  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 18:07:11.918  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:11.918  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:07:11.918  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 18:07:11.921  5955  5971 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 18:07:11.921  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 18:07:11.921  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.921  5659  5706 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 18:07:11.921  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 18:07:11.921  5955  5974 D BtGatt.ScanManager: stopping BLe Batch
10-26 18:07:11.921  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:11.924  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 18:07:11.925  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 18:07:11.925  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 18:07:11.926  5955  5971 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 18:07:11.926  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.926  5955  5974 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 18:07:11.929  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.929  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 18:07:11.929  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 18:07:11.930  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 18:07:11.930  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 18:07:11.930  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.930  5955  5971 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 18:07:11.931  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.931  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:07:11.933  5955  5991 D BtGatt.GattService: registerClient() - UUID=cd13d004-4940-4c41-ab76-cad2a0b4b719
10-26 18:07:11.933  5955  5971 D BtGatt.GattService: onClientRegistered() - UUID=cd13d004-4940-4c41-ab76-cad2a0b4b719, clientIf=5
,10-26 18:07:11.933  5659  5705 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 18:07:11.933  5955  5983 D BtGatt.GattService: start scan with filters
10-26 18:07:11.935  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 18:07:11.935  5955  5974 D BtGatt.ScanManager: handling starting scan
10-26 18:07:11.935  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.935  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 18:07:11.935  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.935  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.936  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 18:07:11.936  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 18:07:11.936  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.936  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.936  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 18:07:11.936  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.938  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.938  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:07:11.938  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.938  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:07:11.938  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.938  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.938  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 18:07:11.940  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 18:07:11.940  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.941  5955  5971 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 18:07:11.941  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.942  5955  5974 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 18:07:11.942  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.942  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.942  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.942  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 18:07:11.942  5659  5706 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-26 18:07:11.942  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:07:11.942  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:07:11.942  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:07:11.942  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:11.943  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.943  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 18:07:11.943  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:07:11.943  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:11.943  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87cb935 removed from the list
10-26 18:07:11.943  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.943  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18731ca removed from the list
10-26 18:07:11.943  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:07:11.943  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:07:11.943  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.943  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 18:07:11.943  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.943  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:07:11.943  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.944  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.944  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.944  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.945  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:11.945  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:11.945  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.945  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18731ca not in the list
10-26 18:07:11.945  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 18:07:11.945  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 18:07:11.945  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 18:07:11.945  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.945  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.945  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 18:07:11.946  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:07:11.946  5955  5971 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 18:07:11.946  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.946  5955  5992 D BtGatt.GattService: stopScan() - queue size =1
10-26 18:07:11.947  5955  5974 D BtGatt.ScanManager: Starting BLE batch scan
10-26 18:07:11.947  5955  5974 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 18:07:11.947  5955  5966 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 18:07:11.947  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 18:07:11.947  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.947  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 18:07:11.947  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.947  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.948  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 18:07:11.948  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 18:07:11.948  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.948  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.948  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 18:07:11.948  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.949  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.949  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 18:07:11.950  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.950  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.951  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.951  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.952  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.952  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:11.952  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:11.952  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.952  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:07:11.952  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ccb3b1 removed from the list
10-26 18:07:11.952  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:11.952  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:07:11.952  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.952  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:07:11.952  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.952  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:07:11.952  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:11.952  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e170658 removed from the list
10-26 18:07:11.953  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:07:11.953  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@847d9ed added. We now have 3 listener(s)
10-26 18:07:11.954  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:07:11.954  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:11.954  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:11.955  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:11.955  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54c3022 added. We now have 4 listener(s)
10-26 18:07:11.955  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:07:11.955  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 18:07:11.955  5955  5971 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 18:07:11.955  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.957  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:07:11.960  5955  5971 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 18:07:11.960  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.961  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:07:11.961  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:11.961  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:11.961  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:11.961  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:11.961  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.961  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:07:11.961  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:07:11.963  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:11.963  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:07:11.963  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:07:11.963  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e944870 added. We now have 4 listener(s)
10-26 18:07:11.964  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:07:11.964  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:11.964  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:11.964  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:11.964  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d527e9 added. We now have 5 listener(s)
10-26 18:07:11.964  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:07:11.965  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 18:07:11.965  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 18:07:11.965  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 18:07:11.965  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:07:11.965  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 18:07:11.965  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:11.966  5955  5971 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 18:07:11.966  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.966  5955  5974 D BtGatt.ScanManager: stopping BLe Batch
10-26 18:07:11.967  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 18:07:11.967  5659  5706 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 18:07:11.967  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 18:07:11.967  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:11.969  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 18:07:11.971  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 18:07:11.971  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 18:07:11.971  5955  5971 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 18:07:11.971  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.971  5955  5974 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 18:07:11.973  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.973  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 18:07:11.974  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 18:07:11.974  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 18:07:11.974  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 18:07:11.974  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.974  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:07:11.975  5955  5971 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 18:07:11.975  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.976  5955  5991 D BtGatt.GattService: registerClient() - UUID=0e043908-0dba-4ab6-b0e4-6793679b52a7
10-26 18:07:11.976  5955  5971 D BtGatt.GattService: onClientRegistered() - UUID=0e043908-0dba-4ab6-b0e4-6793679b52a7, clientIf=5
10-26 18:07:11.977  5659  5669 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 18:07:11.977  5955  5983 D BtGatt.GattService: start scan with filters
10-26 18:07:11.979  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 18:07:11.979  5955  5974 D BtGatt.ScanManager: handling starting scan
10-26 18:07:11.979  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.979  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 18:07:11.979  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.979  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.979  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 18:07:11.979  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 18:07:11.979  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.980  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.980  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 18:07:11.980  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.982  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.983  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:07:11.983  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.983  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 18:07:11.983  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.983  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.983  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 18:07:11.984  5955  5971 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 18:07:11.984  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.984  5955  5974 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 18:07:11.985  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 18:07:11.985  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.988  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.988  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.988  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.990  5955  5971 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 18:07:11.990  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:11.990  5955  5974 D BtGatt.ScanManager: Starting BLE batch scan
10-26 18:07:11.990  5955  5974 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 18:07:11.991  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:07:11.991  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:07:11.991  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:07:11.991  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:11.991  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.991  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 18:07:11.991  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:07:11.991  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:11.991  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@847d9ed removed from the list
10-26 18:07:11.991  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.992  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54c3022 removed from the list
10-26 18:07:11.992  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:07:11.992  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:07:11.992  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.992  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 18:07:11.992  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:11.992  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:07:11.993  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.993  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.993  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.994  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.994  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:11.994  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:11.994  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:11.994  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54c3022 not in the list
10-26 18:07:11.994  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 18:07:11.994  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 18:07:11.994  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 18:07:11.994  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.994  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.994  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 18:07:11.994  5659  5706 D BluetoothAdapter: STATE_ON
10-26 18:07:11.995  5955  5991 D BtGatt.GattService: stopScan() - queue size =1
10-26 18:07:11.996  5955  5983 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 18:07:11.996  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 18:07:11.996  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.996  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 18:07:11.996  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.996  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.996  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 18:07:11.996  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 18:07:11.996  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.996  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.996  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 18:07:11.996  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.997  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:11.998  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 18:07:11.998  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 18:07:11.999  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:11.999  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.000  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.000  5955  5971 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 18:07:12.000  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:12.000  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.000  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.000  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:12.000  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:12.000  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:12.000  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:07:12.000  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d527e9 removed from the list
10-26 18:07:12.000  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:12.001  5659  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 18:07:12.001  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:12.001  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:12.001  5659  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 18:07:12.001  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:07:12.001  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:12.001  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e944870 removed from the list
10-26 18:07:12.001  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:07:12.001  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cf59a5 added. We now have 3 listener(s)
10-26 18:07:12.002  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:07:12.002  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:12.002  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:12.003  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:12.003  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@537a17a added. We now have 4 listener(s)
10-26 18:07:12.003  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:07:12.003  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 18:07:12.005  5955  5971 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 18:07:12.005  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:12.005  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 18:07:12.008  5659  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 18:07:12.008  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 18:07:12.008  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 18:07:12.008  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 18:07:12.008  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 18:07:12.008  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:12.008  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 18:07:12.008  5659  5706 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 18:07:12.010  5659  5706 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 18:07:12.010  5659  5706 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 18:07:12.010  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 18:07:12.010  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@204b588 added. We now have 4 listener(s)
10-26 18:07:12.010  5955  5971 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 18:07:12.010  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:12.011  5955  5974 D BtGatt.ScanManager: stopping BLe Batch
10-26 18:07:12.011  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
10-26 18:07:12.011  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 18:07:12.011  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 18:07:12.012  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 18:07:12.012  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a80eb21 added. We now have 5 listener(s)
10-26 18:07:12.012  5659  5706 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 18:07:12.012  5659  5706 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 18:07:12.012  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:07:12.012  5659  5706 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 18:07:12.012  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:12.012  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:12.012  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:12.012  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 18:07:12.012  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:07:12.012  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:12.012  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cf59a5 removed from the list
10-26 18:07:12.012  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 18:07:12.012  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@537a17a removed from the list
10-26 18:07:12.014  5659  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 18:07:12.014  5659  5706 D io.jxcore.node.ConnectivityMonitor: stop
10-26 18:07:12.014  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:12.015  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:12.015  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:12.015  5955  5971 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 18:07:12.015  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:12.015  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.015  5955  5974 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 18:07:12.016  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.019  5955  5971 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 18:07:12.020  5955  5971 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 18:07:12.020  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.020  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.020  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:12.020  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:12.020  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:12.020  5659  5706 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@537a17a not in the list
10-26 18:07:12.020  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:12.020  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:12.020  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.021  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.021  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.022  5659  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-58,5,main], id: 58
10-26 18:07:12.022  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 18:07:12.022  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 18:07:12.022  5659  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 18:07:12.022  5659  5706 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a80eb21 removed from the list
10-26 18:07:12.022  5659  5706 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 18:07:12.022  5659  5706 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 18:07:12.022  5659  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 18:07:12.022  5659  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 18:07:12.022  5659  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 18:07:12.022  5659  5706 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@204b588 removed from the list
10-26 18:07:12.023  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-26 18:07:12.023  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-26 18:07:12.023  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-26 18:07:12.023  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 18:07:12.023  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-26 18:07:12.023  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-26 18:07:12.398  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 18:07:12.453  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 18:07:12.501  5659  5659 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 18:07:13.089   929  2981 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,10-26 18:07:13.102   929  2983 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-26 18:07:13.107  3714  3839 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,10-26 18:07:13.108  3714  3839 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::6283:34ff:fe25:d770/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-26 18:07:14.164  5659  6048 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 18:07:14.164  5659  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 18:07:14.961  5659  6048 W !!      : call onHalfStreamCopied
,10-26 18:07:14.962  5659  6048 I testCopyDataAndClose: closing input stream
,10-26 18:07:15.137  3577  6050 I VacuumService: Vacuum at: now=1477498035137 tag=VacuumService
,10-26 18:07:15.164  3577  6053 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-26 18:07:15.197  3577  6051 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-26 18:07:15.200  3577  6051 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-26 18:07:15.221  3577  6053 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 18:07:15.545  3577  6051 W Uploader:  no longer exists, so no auth token.
,10-26 18:07:15.552  3577  6055 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 18:07:15.618  3577  6053 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 18:07:15.733  3577  6055 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 18:07:15.747  5659  6048 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 18:07:15.747  5659  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 18:07:15.747  5659  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 18:07:15.747  5659  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 18:07:15.747  5659  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 18:07:15.747  5659  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 18:07:15.747  5659  6048 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 18:07:15.747  5659  6048 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-26 18:07:15.747  5659  6048 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-26 18:07:15.748  5659  6048 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 18:07:15.748  5659  6048 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 18:07:15.810  3577  6051 W Uploader:  no longer exists, so no auth token.
,10-26 18:07:15.815  3577  6053 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 18:07:15.903  3577  6055 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 18:07:16.012  3577  6053 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-26 18:07:19.684   929  2983 D ConnectivityService: handlePromptUnvalidated 102
,10-26 18:07:19.989  5659  6060 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-26 18:07:19.989  5659  6060 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 18:07:20.054   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:21.056   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:21.989  5659  5706 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 177. Connection data: Peer properties: [null null].
10-26 18:07:21.989  5659  5706 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 18:07:21.989  5659  5706 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 177, name: My test thread name)
,10-26 18:07:22.054  5659  6060 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
10-26 18:07:22.054  5659  6060 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: My test thread name). Connection data: Peer properties: [null null].
10-26 18:07:22.054  5659  6060 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,10-26 18:07:22.056   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:22.179  5659  6061 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 18:07:22.179  5659  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 18:07:23.058   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 179, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 179, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 18:07:23.832  5659  6061 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 18:07:24.059   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:25.060   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-26 18:07:28.062  5659  6062 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-26 18:07:28.062  5659  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 18:07:28.063  5659  6062 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 181, thread name: My test thread name). Connection data: Peer properties: [null null].
10-26 18:07:28.063  5659  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 18:07:28.063  5659  6062 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 18:07:28.063  5659  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 18:07:28.063  5659  6062 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-26 18:07:28.063  5659  6062 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 18:07:28.063  5659  6062 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-26 18:07:28.063  5659  6062 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-26 18:07:28.064  5659  6062 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-26 18:07:28.064  5659  6062 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-26 18:07:28.064  5659  6062 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-26 18:07:28.066  5659  5706 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-26 18:07:28.069  5659  6063 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-26 18:07:28.069  5659  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 18:07:28.069  5659  6063 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 185, thread name: My test thread name): Test exception.
10-26 18:07:28.070  5659  6063 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-26 18:07:28.070  5659  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-26 18:07:28.070  5659  6063 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,10-26 18:07:28.070  5659  6063 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-26 18:07:28.070  5659  6063 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-26 18:07:28.075  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-26 18:07:28.075  5659  5706 I jxcore-log: 
,10-26 18:07:28.075  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-26 18:07:28.075  5659  5706 I jxcore-log: 
10-26 18:07:28.076  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-26 18:07:28.076  5659  5706 I jxcore-log: 
10-26 18:07:28.076  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-26 18:07:28.076  5659  5706 I jxcore-log: 
10-26 18:07:28.076  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG UnitTest_app: 'Total duration:  91837'
10-26 18:07:28.076  5659  5706 I jxcore-log: 
,10-26 18:07:28.079  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-26 18:07:28.079  5659  5706 I jxcore-log: 
,10-26 18:07:28.084  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.084  5659  5706 I jxcore-log: 
,10-26 18:07:28.085  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.085  5659  5706 I jxcore-log: 
10-26 18:07:28.085  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.085  5659  5706 I jxcore-log: 
10-26 18:07:28.086  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.086  5659  5706 I jxcore-log: 
,10-26 18:07:28.086  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 18:07:28.086  5659  5706 I jxcore-log: 
10-26 18:07:28.086  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 18:07:28.086  5659  5706 I jxcore-log: 
10-26 18:07:28.087  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.087  5659  5706 I jxcore-log: 
10-26 18:07:28.087  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.087  5659  5706 I jxcore-log: 
10-26 18:07:28.087  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 18:07:28.087  5659  5706 I jxcore-log: 
10-26 18:07:28.087  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 18:07:28.087  5659  5706 I jxcore-log: 
10-26 18:07:28.088  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 18:07:28.088  5659  5706 I jxcore-log: 
10-26 18:07:28.088  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.088  5659  5706 I jxcore-log: 
10-26 18:07:28.088  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.088  5659  5706 I jxcore-log: 
10-26 18:07:28.088  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.088  5659  5706 I jxcore-log: 
10-26 18:07:28.089  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.089  5659  5706 I jxcore-log: 
10-26 18:07:28.089  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.089  5659  5706 I jxcore-log: 
,10-26 18:07:28.089  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.089  5659  5706 I jxcore-log: 
10-26 18:07:28.089  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.089  5659  5706 I jxcore-log: 
10-26 18:07:28.090  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.090  5659  5706 I jxcore-log: 
10-26 18:07:28.090  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.090  5659  5706 I jxcore-log: 
,10-26 18:07:28.090  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.090  5659  5706 I jxcore-log: 
10-26 18:07:28.090  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.090  5659  5706 I jxcore-log: 
10-26 18:07:28.091  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.091  5659  5706 I jxcore-log: 
10-26 18:07:28.092  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.092  5659  5706 I jxcore-log: 
,10-26 18:07:28.092  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.092  5659  5706 I jxcore-log: 
10-26 18:07:28.093  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.093  5659  5706 I jxcore-log: 
10-26 18:07:28.093  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.093  5659  5706 I jxcore-log: 
10-26 18:07:28.093  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.093  5659  5706 I jxcore-log: 
10-26 18:07:28.093  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.093  5659  5706 I jxcore-log: 
,10-26 18:07:28.094  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.094  5659  5706 I jxcore-log: 
10-26 18:07:28.094  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.094  5659  5706 I jxcore-log: 
10-26 18:07:28.094  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.094  5659  5706 I jxcore-log: 
10-26 18:07:28.094  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.094  5659  5706 I jxcore-log: 
10-26 18:07:28.095  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.095  5659  5706 I jxcore-log: 
10-26 18:07:28.095  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.095  5659  5706 I jxcore-log: 
10-26 18:07:28.095  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.095  5659  5706 I jxcore-log: 
10-26 18:07:28.095  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.095  5659  5706 I jxcore-log: 
10-26 18:07:28.096  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.096  5659  5706 I jxcore-log: 
,10-26 18:07:28.096  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.096  5659  5706 I jxcore-log: 
10-26 18:07:28.096  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.096  5659  5706 I jxcore-log: 
10-26 18:07:28.096  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 18:07:28.096  5659  5706 I jxcore-log: 
10-26 18:07:28.097  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.097  5659  5706 I jxcore-log: 
10-26 18:07:28.097  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 18:07:28.097  5659  5706 I jxcore-log: 
,10-26 18:07:28.097  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.097  5659  5706 I jxcore-log: 
10-26 18:07:28.097  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.097  5659  5706 I jxcore-log: 
10-26 18:07:28.097  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.097  5659  5706 I jxcore-log: 
10-26 18:07:28.098  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.098  5659  5706 I jxcore-log: 
,10-26 18:07:28.098  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.098  5659  5706 I jxcore-log: 
10-26 18:07:28.098  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 18:07:28.098  5659  5706 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-26 18:07:28.098  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.098  5659  5706 I jxcore-log: 
10-26 18:07:28.099  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.099  5659  5706 I jxcore-log: 
10-26 18:07:28.099  5659  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 18:07:28.099  5659  5706 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-26 18:07:28.099  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 18:07:28.099  5659  5706 I jxcore-log: 
10-26 18:07:28.099  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 18:07:28.099  5659  5706 I jxcore-log: 
,10-26 18:07:28.099  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 18:07:28.099  5659  5706 I jxcore-log: 
10-26 18:07:28.100  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 18:07:28.100  5659  5706 I jxcore-log: 
10-26 18:07:28.103  5659  5659 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-26 18:07:28.105  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-26 18:07:28.105  5659  5706 I jxcore-log: 
,10-26 18:07:28.105  5659  5706 I jxcore-log: 2016-10-26 16:07:28 - WARN testUtils: 'myNameCallback not set!'
10-26 18:07:28.105  5659  5706 I jxcore-log: 
,10-26 18:07:30.150  5659  5706 I jxcore-log: 2016-10-26 16:07:30 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
10-26 18:07:30.150  5659  5706 I jxcore-log: 
,10-26 18:07:30.152  5659  5706 I jxcore-log: 2016-10-26 16:07:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-26 18:07:30.152  5659  5706 I jxcore-log: 
,10-26 18:07:30.486  5659  5706 I jxcore-log: 2016-10-26 16:07:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-26 18:07:30.486  5659  5706 I jxcore-log: 
,10-26 18:07:30.498  5659  5706 I jxcore-log: 2016-10-26 16:07:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-26 18:07:30.498  5659  5706 I jxcore-log: 
,10-26 18:07:31.613  5659  5706 I jxcore-log: 2016-10-26 16:07:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-26 18:07:31.613  5659  5706 I jxcore-log: 
,10-26 18:07:31.803  5659  5706 I jxcore-log: 2016-10-26 16:07:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-26 18:07:31.803  5659  5706 I jxcore-log: 
,10-26 18:07:31.809  5659  5706 I jxcore-log: 2016-10-26 16:07:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-26 18:07:31.809  5659  5706 I jxcore-log: 
,10-26 18:07:31.814  5659  5706 I jxcore-log: 2016-10-26 16:07:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-26 18:07:31.814  5659  5706 I jxcore-log: 
,10-26 18:07:32.297  5659  5706 I jxcore-log: 2016-10-26 16:07:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-26 18:07:32.297  5659  5706 I jxcore-log: 
,10-26 18:07:32.342  5659  5706 I jxcore-log: 2016-10-26 16:07:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-26 18:07:32.342  5659  5706 I jxcore-log: 
,10-26 18:07:32.355  5659  5706 I jxcore-log: 2016-10-26 16:07:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-26 18:07:32.355  5659  5706 I jxcore-log: 
,10-26 18:07:32.359  5659  5706 I jxcore-log: 2016-10-26 16:07:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-26 18:07:32.359  5659  5706 I jxcore-log: 
,10-26 18:07:32.643  5659  5706 I jxcore-log: 2016-10-26 16:07:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-26 18:07:32.643  5659  5706 I jxcore-log: 
,10-26 18:07:32.929  5659  5706 I jxcore-log: 2016-10-26 16:07:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-26 18:07:32.929  5659  5706 I jxcore-log: 
,10-26 18:07:33.154  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-26 18:07:33.154  5659  5706 I jxcore-log: 
,10-26 18:07:33.164  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-26 18:07:33.164  5659  5706 I jxcore-log: 
,10-26 18:07:33.168  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-26 18:07:33.168  5659  5706 I jxcore-log: 
,10-26 18:07:33.174  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-26 18:07:33.174  5659  5706 I jxcore-log: 
,10-26 18:07:33.179  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-26 18:07:33.179  5659  5706 I jxcore-log: 
,10-26 18:07:33.206  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-26 18:07:33.206  5659  5706 I jxcore-log: 
,10-26 18:07:33.241  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-26 18:07:33.241  5659  5706 I jxcore-log: 
,10-26 18:07:33.249  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-26 18:07:33.249  5659  5706 I jxcore-log: 
,10-26 18:07:33.255  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-26 18:07:33.255  5659  5706 I jxcore-log: 
,10-26 18:07:33.271  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-26 18:07:33.271  5659  5706 I jxcore-log: 
,10-26 18:07:33.275  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-26 18:07:33.275  5659  5706 I jxcore-log: 
,10-26 18:07:33.281  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-26 18:07:33.281  5659  5706 I jxcore-log: 
,10-26 18:07:33.286  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-26 18:07:33.286  5659  5706 I jxcore-log: 
,10-26 18:07:33.299  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-26 18:07:33.299  5659  5706 I jxcore-log: 
,10-26 18:07:33.305  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-26 18:07:33.305  5659  5706 I jxcore-log: 
,10-26 18:07:33.327  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-26 18:07:33.327  5659  5706 I jxcore-log: 
,10-26 18:07:33.338  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-26 18:07:33.338  5659  5706 I jxcore-log: 
,10-26 18:07:33.350  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-26 18:07:33.350  5659  5706 I jxcore-log: 
,10-26 18:07:33.360  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-26 18:07:33.360  5659  5706 I jxcore-log: 
,10-26 18:07:33.374  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-26 18:07:33.374  5659  5706 I jxcore-log: 
,10-26 18:07:33.384  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-26 18:07:33.384  5659  5706 I jxcore-log: 
,10-26 18:07:33.391  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-26 18:07:33.391  5659  5706 I jxcore-log: 
,10-26 18:07:33.412  5659  5706 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-26 18:07:33.413  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - INFO testUtils: 'BLE multiple advertisement supported'
10-26 18:07:33.413  5659  5706 I jxcore-log: 
,10-26 18:07:33.483  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:33.483  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:33.483  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:33.483  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:33.483  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:33.483  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:33.483  5659  5706 I jxcore-log: 
,10-26 18:07:33.809  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:33.809  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:33.809  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:33.809  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:33.809  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:33.809  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:33.809  5659  5706 I jxcore-log: 
,10-26 18:07:33.811  5659  5706 I jxcore-log: 2016-10-26 16:07:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:33.811  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:33.811  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:33.811  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:33.811  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:33.811  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:33.811  5659  5706 I jxcore-log: 
,10-26 18:07:34.320  5659  5706 I jxcore-log: 2016-10-26 16:07:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:34.320  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:34.320  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:34.320  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:34.320  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:34.320  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:34.320  5659  5706 I jxcore-log: 
,10-26 18:07:34.324  5659  5706 I jxcore-log: 2016-10-26 16:07:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:34.324  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:34.324  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:34.324  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:34.324  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:34.324  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:34.324  5659  5706 I jxcore-log: 
,10-26 18:07:35.136  5659  5706 I jxcore-log: 2016-10-26 16:07:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:35.136  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:35.136  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:35.136  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:35.136  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:35.136  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:35.136  5659  5706 I jxcore-log: 
,10-26 18:07:35.140  5659  5706 I jxcore-log: 2016-10-26 16:07:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:35.140  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:35.140  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:35.140  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:35.140  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:35.140  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:35.140  5659  5706 I jxcore-log: 
,10-26 18:07:36.165  5659  5706 I jxcore-log: 2016-10-26 16:07:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:36.165  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:36.165  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:36.165  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:36.165  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:36.165  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:36.165  5659  5706 I jxcore-log: 
,10-26 18:07:36.170  5659  5706 I jxcore-log: 2016-10-26 16:07:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:36.170  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:36.170  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:36.170  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:36.170  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:36.170  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:36.170  5659  5706 I jxcore-log: 
,10-26 18:07:37.217  5659  5706 I jxcore-log: 2016-10-26 16:07:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:37.217  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:37.217  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:37.217  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:37.217  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:37.217  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:37.217  5659  5706 I jxcore-log: 
,10-26 18:07:37.221  5659  5706 I jxcore-log: 2016-10-26 16:07:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:37.221  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:37.221  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:37.221  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:37.221  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:37.221  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:37.221  5659  5706 I jxcore-log: 
,10-26 18:07:38.259  5659  5706 I jxcore-log: 2016-10-26 16:07:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:38.259  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:38.259  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:38.259  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:38.259  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:38.259  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:38.259  5659  5706 I jxcore-log: 
,10-26 18:07:38.262  5659  5706 I jxcore-log: 2016-10-26 16:07:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:38.262  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:38.262  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:38.262  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:38.262  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:38.262  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:38.262  5659  5706 I jxcore-log: 
,10-26 18:07:39.301  5659  5706 I jxcore-log: 2016-10-26 16:07:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:39.301  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:39.301  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:39.301  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:39.301  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:39.301  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:39.301  5659  5706 I jxcore-log: 
,10-26 18:07:39.305  5659  5706 I jxcore-log: 2016-10-26 16:07:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:39.305  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:39.305  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:39.305  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:39.305  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:39.305  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:39.305  5659  5706 I jxcore-log: 
,10-26 18:07:40.341  5659  5706 I jxcore-log: 2016-10-26 16:07:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:40.341  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:40.341  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:40.341  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:40.341  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:40.341  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:40.341  5659  5706 I jxcore-log: 
,10-26 18:07:40.345  5659  5706 I jxcore-log: 2016-10-26 16:07:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:40.345  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:40.345  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:40.345  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:40.345  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:40.345  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:40.345  5659  5706 I jxcore-log: 
,10-26 18:07:41.382  5659  5706 I jxcore-log: 2016-10-26 16:07:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:41.382  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:41.382  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:41.382  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:41.382  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:41.382  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:41.382  5659  5706 I jxcore-log: 
,10-26 18:07:41.386  5659  5706 I jxcore-log: 2016-10-26 16:07:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:41.386  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:41.386  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:41.386  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:41.386  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:41.386  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:41.386  5659  5706 I jxcore-log: 
,10-26 18:07:42.450  5659  5706 I jxcore-log: 2016-10-26 16:07:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:42.450  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:42.450  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:42.450  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:42.450  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:42.450  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:42.450  5659  5706 I jxcore-log: 
,10-26 18:07:42.454  5659  5706 I jxcore-log: 2016-10-26 16:07:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:42.454  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:42.454  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:42.454  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:42.454  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:42.454  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:42.454  5659  5706 I jxcore-log: 
,10-26 18:07:43.490  5659  5706 I jxcore-log: 2016-10-26 16:07:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:43.490  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:43.490  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:43.490  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:43.490  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:43.490  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:43.490  5659  5706 I jxcore-log: 
,10-26 18:07:43.494  5659  5706 I jxcore-log: 2016-10-26 16:07:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:43.494  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:43.494  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:43.494  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:43.494  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:43.494  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:43.494  5659  5706 I jxcore-log: 
,10-26 18:07:44.530  5659  5706 I jxcore-log: 2016-10-26 16:07:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:44.530  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:44.530  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:44.530  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:44.530  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:44.530  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:44.530  5659  5706 I jxcore-log: 
,10-26 18:07:44.535  5659  5706 I jxcore-log: 2016-10-26 16:07:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:44.535  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:44.535  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:44.535  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:44.535  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:44.535  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:44.535  5659  5706 I jxcore-log: 
,10-26 18:07:45.061   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:45.591  5659  5706 I jxcore-log: 2016-10-26 16:07:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:45.591  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:45.591  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:45.591  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:45.591  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:45.591  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:45.591  5659  5706 I jxcore-log: 
,10-26 18:07:45.595  5659  5706 I jxcore-log: 2016-10-26 16:07:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:45.595  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:45.595  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:45.595  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:45.595  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:45.595  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:45.595  5659  5706 I jxcore-log: 
,10-26 18:07:46.062   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:46.630  5659  5706 I jxcore-log: 2016-10-26 16:07:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:46.630  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:46.630  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:46.630  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:46.630  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:46.630  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:46.630  5659  5706 I jxcore-log: 
,10-26 18:07:46.635  5659  5706 I jxcore-log: 2016-10-26 16:07:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:46.635  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:46.635  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:46.635  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:46.635  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:46.635  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:46.635  5659  5706 I jxcore-log: 
,10-26 18:07:47.063   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:47.685  5659  5706 I jxcore-log: 2016-10-26 16:07:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 18:07:47.685  5659  5706 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 18:07:47.685  5659  5706 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 18:07:47.685  5659  5706 I jxcore-log: emit@events.js:82:1
10-26 18:07:47.685  5659  5706 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 18:07:47.685  5659  5706 I jxcore-log: emit@events.js:82:1'
10-26 18:07:47.685  5659  5706 I jxcore-log: 
,10-26 18:07:47.697  5659  5706 E jxcore  : Error!: error is undefined
10-26 18:07:47.697  5659  5706 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"221","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:221:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-26 18:07:47.701  5659  5706 I jxcore-log: 2016-10-26 16:07:47 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-26 18:07:47.701  5659  5706 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:221:1
10-26 18:07:47.701  5659  5706 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-26 18:07:47.701  5659  5706 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-26 18:07:47.701  5659  5706 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-26 18:07:47.701  5659  5706 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-26 18:07:47.701  5659  5706 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-26 18:07:47.701  5659  5706 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
10-26 18:07:47.702  5659  5706 I jxcore-log: 2016-10-26 16:07:47 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-26 18:07:47.702  5659  5706 I jxcore-log: 
10-26 18:07:47.703  5659  5706 E jxcore-log: TypeError: 
10-26 18:07:47.704  5659  5706 E jxcore-log: error is undefined
10-26 18:07:47.704  5659  5706 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 221:0)
10-26 18:07:47.704  5659  5706 E jxcore-log: 
,10-26 18:07:47.769   929  2961 W InputDispatcher: channel 'c16fc16 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-26 18:07:47.770   929  2961 E InputDispatcher: channel 'c16fc16 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-26 18:07:47.780   929  3816 D GraphicsStats: Buffer count: 2
,10-26 18:07:47.782   929  2982 D WifiService: Client connection lost with reason: 4
,10-26 18:07:47.785   530   530 I Zygote  : Process 5659 exited cleanly (139)
,10-26 18:07:47.785   929  3800 I WindowState: WIN DEATH: Window{c16fc16 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-26 18:07:47.785   929  3800 W InputDispatcher: Attempted to unregister already unregistered input channel 'c16fc16 com.test.thalitest/com.test.thalitest.MainActivity (server)'
10-26 18:07:47.786   929  3578 I ActivityManager: Process com.test.thalitest (pid 5659) has died
,10-26 18:07:47.812   929  3578 I ActivityManager: Start proc 6066:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-26 18:07:47.898  6066  6066 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-26 18:07:47.918  6066  6066 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-26 18:07:47.923  6066  6066 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1736-1738)
,10-26 18:07:47.923  6066  6066 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 18:07:47.932  6066  6066 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ca9f4b9}
10-26 18:07:47.932  6066  6066 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 18:07:47.932  6066  6066 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 18:07:47.936  6066  6066 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 18:07:47.936  6066  6066 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 18:07:47.947  6066  6066 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 18:07:47.955  6066  6066 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-26 18:07:47.955  6066  6066 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 18:07:47.955  6066  6066 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 18:07:47.955  6066  6066 I Adreno  : Build Date                       : 12/06/15
10-26 18:07:47.955  6066  6066 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 18:07:47.955  6066  6066 I Adreno  : Local Branch                     : mybranch17112971
10-26 18:07:47.955  6066  6066 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 18:07:47.955  6066  6066 I Adreno  : Remote Branch                    : NONE
10-26 18:07:47.955  6066  6066 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 18:07:47.988   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dd4e34:true
,10-26 18:07:48.000   402   402 W Binder_1: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[16815]" dev="sockfs" ino=16815 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:48.000   402   402 W Binder_1: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[16815]" dev="sockfs" ino=16815 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:48.013  6066  6066 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 18:07:48.021  6066  6066 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 18:07:48.047   504   504 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[37400]" dev="sockfs" ino=37400 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:48.047   504   504 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[37400]" dev="sockfs" ino=37400 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-26 18:07:48.051  6066  6102 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-26 18:07:48.050  3578  3578 W Binder_5: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[25461]" dev="sockfs" ino=25461 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 18:07:48.050  3578  3578 W Binder_5: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[25461]" dev="sockfs" ino=25461 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:48.056  6066  6089 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-26 18:07:48.064   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 18:07:48.083  6066  6102 I OpenGLRenderer: Initialized EGL, version 1.4
,10-26 18:07:48.095   929  3150 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5659 uid 10077
,10-26 18:07:48.093  3150  3150 W Binder_3: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[25465]" dev="sockfs" ino=25465 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:48.093  3150  3150 W Binder_3: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[25465]" dev="sockfs" ino=25465 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:48.099  3636  3636 I Keyboard.Facilitator: onFinishInput()
,10-26 18:07:48.097  3790  3790 W Binder_8: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[25464]" dev="sockfs" ino=25464 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:48.097  3790  3790 W Binder_8: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[25464]" dev="sockfs" ino=25464 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:48.116   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +280ms (total +327ms)
,10-26 18:07:48.117  6066  6066 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6066
,10-26 18:07:48.170  6066  6066 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-26 18:07:48.181  6064  6064 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-26 18:07:48.226  6064  6064 D AndroidRuntime: CheckJNI is OFF
,10-26 18:07:48.248  6064  6064 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-26 18:07:48.272  6064  6064 I Radio-JNI: register_android_hardware_Radio DONE
,10-26 18:07:48.287  6064  6064 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-26 18:07:48.293   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-26 18:07:48.294   929   942 I ActivityManager: Killing 6066:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-26 18:07:48.329   929   939 I WindowState: WIN DEATH: Window{d7d7a93 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-26 18:07:48.329   929  3183 D GraphicsStats: Buffer count: 2
,10-26 18:07:48.424   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-26 18:07:48.425   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-26 18:07:48.426   929   942 E ActivityManager: Failure starting process com.test.thalitest
10-26 18:07:48.426   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-26 18:07:48.426   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:07:48.426   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:07:48.426   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-26 18:07:48.426   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-26 18:07:48.427   929   942 I ActivityManager:   Force finishing activity ActivityRecord{140ebbf u0 com.test.thalitest/.MainActivity t66}
,10-26 18:07:48.429   929   952 I art     : Starting a blocking GC Explicit
,10-26 18:07:48.437   929  3150 W ActivityManager: Spurious death for ProcessRecord{f15cac9 0:com.test.thalitest/u0a77}, curProc for 6066: null
,10-26 18:07:48.530   929   952 I art     : Explicit concurrent mark sweep GC freed 49075(2MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 1.985ms total 101.332ms
,10-26 18:07:48.551   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-26 18:07:48.555  6064  6064 I art     : System.exit called, status: 0
,10-26 18:07:48.555  6064  6064 I AndroidRuntime: VM exiting with result code 0.
,10-26 18:07:48.572   929   952 I ActivityManager: Start proc 6116:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
10-26 18:07:48.572   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-26 18:07:48.577   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-26 18:07:48.589  3636  3636 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-26 18:07:48.590  5955  5955 D BluetoothMapAppObserver: onReceive
10-26 18:07:48.590  5955  5955 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-26 18:07:48.592  3690  4068 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-26 18:07:48.605   929  2962 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-26 18:07:48.619  3636  6128 I Keyboard.Facilitator.DecoderInitializer: run()
,10-26 18:07:48.625  3393  6129 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-26 18:07:48.643  3636  6128 I Decoder : createOrResetDecoder
,10-26 18:07:48.660  3754  3754 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-26 18:07:48.667  3750  3750 W Binder_7: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[26418]" dev="sockfs" ino=26418 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
10-26 18:07:48.667   929  3750 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6066 uid 10077
10-26 18:07:48.667  3750  3750 W Binder_7: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[26418]" dev="sockfs" ino=26418 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 18:07:48.671  3636  3636 I Keyboard.Facilitator: onFinishInput()
,10-26 18:07:48.670    17    17 W kworker/2:0: type=1400 audit(0.0:135): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 18:07:48.673    17    17 W kworker/2:0: type=1400 audit(0.0:136): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 18:07:48.687   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
10-26 18:07:48.690  3577  3577 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
10-26 18:07:48.690  3577  3577 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-26 18:07:48.690    17    17 W kworker/2:0: type=1400 audit(0.0:137): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 18:07:48.710  3791  3887 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-26 18:07:48.716  3393  3413 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjAA91E59A9) - 
,10-26 18:07:48.716  3968  6135 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
10-26 18:07:48.717  3968  6135 D AccountUtils: Clearing selected account for com.test.thalitest
--------- beginning of crash
10-26 18:07:48.717  3393  3413 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-26 18:07:48.717  3393  3413 E AndroidRuntime: Process: android.process.acore, PID: 3393
10-26 18:07:48.717  3393  3413 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:07:48.717  3393  3413 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-26 18:07:48.726   929  3802 I ActivityManager: Start proc 6137:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
10-26 18:07:48.726  3791  3887 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-26 18:07:48.726  3791  3887 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3791
10-26 18:07:48.726  3791  3887 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:07:48.726  3791  3887 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-26 18:07:48.737   929  6147 E DropBoxManagerService: Can't write: system_app_crash
10-26 18:07:48.737   929  6147 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-26 18:07:48.737   929  6147 E DropBoxManagerService: 	... 5 more
,10-26 18:07:48.737  3577  3577 I ConfigService: onCreate
,10-26 18:07:48.738   929  3183 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-26 18:07:48.739  3968  6135 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-26 18:07:48.744  3791  3887 I Process : Sending signal. PID: 3791 SIG: 9
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-26 18:07:48.744  3577  6151 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase,(ContextWrapper.java:269)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-26 18:07:48.745  3577  6151 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: Can't write: system_app_crash
10-26 18:07:48.745   929  6153 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-26 18:07:48.745   929  6153 E DropBoxManagerService: 	... 5 more
10-26 18:07:48.746  3577  6151 W SQLiteOpenHelper: Opened config.db in read-only mode
10-26 18:07:48.768  3393  6129 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
10-26 18:07:48.769  3393  6129 I Process : Sending signal. PID: 3393 SIG: 9
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-26 18:07:48.775  3968  6135 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
