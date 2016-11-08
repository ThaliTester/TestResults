#### Test 92339050883a779_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-08 19:52:25.546  3958  4231 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-08 19:52:25.616  3958  4231 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-08 19:52:25.950  5576  5576 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-08 19:52:25.955  5576  5576 D AndroidRuntime: CheckJNI is OFF
11-08 19:52:25.983  5576  5576 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-08 19:52:26.018  5576  5576 I Radio-JNI: register_android_hardware_Radio DONE
11-08 19:52:26.033  5576  5576 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-08 19:52:26.039   926  3134 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-08 19:52:26.057  5576  5576 D AndroidRuntime: Shutting down VM
11-08 19:52:26.059  3945  4136 W SearchService: Abort, client detached.
11-08 19:52:26.070  3945  3945 I HotwordDetector: Closing mic
11-08 19:52:26.070  3945  4218 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c18c5b2
11-08 19:52:26.071  3945  4232 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-08 19:52:26.087   926  3794 I ActivityManager: Start proc 5585:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-08 19:52:26.144   512  4234 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-08 19:52:26.146   512  4234 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-08 19:52:26.153   512  4234 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-08 19:52:26.153   512  4234 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-08 19:52:26.155   512  2984 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-08 19:52:26.157  3945  4228 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-08 19:52:26.157  3945  4230 I MicroRecognitionRnrImpl: Detection finished
11-08 19:52:26.177  5585  5585 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-08 19:52:26.198  5585  5585 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-08 19:52:26.257  5585  5585 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 4094-4151)
11-08 19:52:26.257  5585  5585 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 19:52:26.293  5585  5585 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bdee249}
11-08 19:52:26.294  5585  5585 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-08 19:52:26.294  5585  5585 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-08 19:52:26.300  5585  5585 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-08 19:52:26.302  5585  5585 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 19:52:26.349  5585  5585 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 19:52:26.363  5585  5585 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 19:52:26.363  5585  5585 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 19:52:26.363  5585  5585 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 19:52:26.363  5585  5585 I Adreno  : Build Date                       : 12/06/15
11-08 19:52:26.363  5585  5585 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 19:52:26.363  5585  5585 I Adreno  : Local Branch                     : mybranch17112971
11-08 19:52:26.363  5585  5585 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 19:52:26.363  5585  5585 I Adreno  : Remote Branch                    : NONE
11-08 19:52:26.363  5585  5585 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 19:52:26.404   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e222f63:true
,11-08 19:52:26.441   403   403 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[24360]" dev="sockfs" ino=24360 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 19:52:26.444   403   403 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[24360]" dev="sockfs" ino=24360 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 19:52:26.455  5585  5585 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 19:52:26.464  5585  5585 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 19:52:26.488   405   405 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33083]" dev="sockfs" ino=33083 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 19:52:26.488   405   405 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33083]" dev="sockfs" ino=33083 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-08 19:52:26.491  5585  5622 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-08 19:52:26.491  3785  3785 W Binder_9: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14300]" dev="sockfs" ino=14300 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:52:26.491  3785  3785 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14300]" dev="sockfs" ino=14300 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 19:52:26.497  5585  5609 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 19:52:26.518  5585  5622 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 19:52:26.605   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +543ms
,11-08 19:52:26.604  3134  3134 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33087]" dev="sockfs" ino=33087 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:52:26.610  3625  3625 I Keyboard.Facilitator: onFinishInput()
,11-08 19:52:26.604  3134  3134 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33087]" dev="sockfs" ino=33087 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 19:52:26.608  3793  3793 W Binder_A: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33086]" dev="sockfs" ino=33086 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 19:52:26.608  3793  3793 W Binder_A: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33086]" dev="sockfs" ino=33086 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:52:26.658  5585  5585 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5585
,11-08 19:52:26.761  5585  5585 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-08 19:52:27.100  5585  5624 D jxcore_app_log: JniHelper::setJavaVM(0xf557c000), pthread_self() = -581437136
,11-08 19:52:27.127  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-08 19:52:27.127  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-08 19:52:27.127  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-08 19:52:27.127  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-08 19:52:27.127  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-08 19:52:27.128  5585  5624 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7224a27 added. We now have 1 listener(s)
,11-08 19:52:27.135  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-08 19:52:27.136  5585  5624 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 19:52:27.137  5585  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 19:52:27.138  5585  5624 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-08 19:52:27.149  5585  5624 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15f61c3 added. We now have 1 listener(s)
11-08 19:52:27.150  5585  5624 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 19:52:27.154   926  2942 D WifiService: New client listening to asynchronous messages
,11-08 19:52:27.156  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 19:52:27.156  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-08 19:52:27.156  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,11-08 19:52:27.156  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-08 19:52:27.156  5585  5624 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-08 19:52:27.162  5585  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 19:52:27.162  5585  5624 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-08 19:52:27.171  5585  5624 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-08 19:52:27.172  5585  5624 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 19:52:27.172  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:27.172  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:27.172  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:27.172  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:27.172  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:52:27.172  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:52:27.172  5585  5624 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:52:27.172  5585  5624 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-08 19:52:27.172  5585  5624 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 19:52:27.172  5585  5624 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-08 19:52:27.444  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:27.455  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:27.463  5585  5585 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-08 19:52:27.898  5585  5594 I art     : Background sticky concurrent mark sweep GC freed 78959(7MB) AllocSpace objects, 17(1496KB) LOS objects, 26% free, 24MB/32MB, paused 1.804ms total 326ms
,11-08 19:52:28.407  5585  5632 W jxcore-log: Initializing JXcore engine
,11-08 19:52:28.407  5585  5632 W jxcore-log: JXcore engine is ready
,11-08 19:52:28.428  5632  5632 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12039 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-08 19:52:28.428  5632  5632 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13649]" dev="sockfs" ino=13649 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-08 19:52:28.428  5632  5632 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-08 19:52:28.428  5632  5632 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33057]" dev="sockfs" ino=33057 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-08 19:52:28.443  5585  5632 W jxcore-log: Starting JXcore engine
,11-08 19:52:28.493  5585  5632 W jxcore-log: Platform android
11-08 19:52:28.493  5585  5632 W jxcore-log: 
11-08 19:52:28.493  5585  5632 W jxcore-log: Process ARCH arm
11-08 19:52:28.493  5585  5632 W jxcore-log: 
,11-08 19:52:28.636  5585  5632 I jxcore-log: JXcore Cordova bridge is ready!
11-08 19:52:28.636  5585  5632 I jxcore-log: 
,11-08 19:52:28.637  5585  5632 W jxcore-log: JXcore engine is started
,11-08 19:52:28.642  5585  5624 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-08 19:52:28.646  5585  5585 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-08 19:52:29.650  3572  3572 I ConfigService: onDestroy
,11-08 19:52:31.079   926   936 I ActivityManager: Killing 5140:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-08 19:52:32.499   926  2931 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-08 19:52:34.612   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:52:35.613   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:52:36.614   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:52:37.615   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:52:38.617   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:52:38.687  5585  5632 I jxcore-log: 2016-11-08 18:52:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-08 19:52:38.687  5585  5632 I jxcore-log: 
,11-08 19:52:38.689  5585  5632 I jxcore-log: 2016-11-08 18:52:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-08 19:52:38.689  5585  5632 I jxcore-log: 
,11-08 19:52:38.693  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 19:52:38.693  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:38.693  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:38.693  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:38.693  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:38.693  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:52:38.693  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:52:38.693  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 19:52:38.694  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:52:38.695  5585  5632 I jxcore-log: 2016-11-08 18:52:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-08 19:52:38.695  5585  5632 I jxcore-log: 
11-08 19:52:38.696  5585  5632 I jxcore-log: 2016-11-08 18:52:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-08 19:52:38.696  5585  5632 I jxcore-log: 
,11-08 19:52:38.961  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 19:52:38.961  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@355200 added. We now have 2 listener(s)
11-08 19:52:38.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 19:52:38.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-08 19:52:38.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 19:52:38.962  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-08 19:52:38.962  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b01a39 added. We now have 2 listener(s)
,11-08 19:52:38.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 19:52:38.963  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 19:52:38.965  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:52:38.968  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 19:52:38.968  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:38.968  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:38.968  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:38.968  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:38.968  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:52:38.968  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:52:38.968  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 19:52:38.969  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:52:38.969  5585  5632 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 19:52:38.969  5585  5632 D ExecuteNativeTests: Running unit tests
11-08 19:52:38.971  5585  5632 D BluetoothAdapter: enable(): BT is already enabled..!
11-08 19:52:38.972   926  3784 D WifiService: setWifiEnabled: true pid=5585, uid=10077
11-08 19:52:38.972   926  3784 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 19:52:38.974  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:38.979  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:39.317  3945  5634 W CronetSyncConnectionRcs: Upload content type not set.
,11-08 19:52:39.440  4872  4902 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-08 19:52:39.441  4872  4872 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-08 19:52:39.444   926  3794 I ActivityManager: Killing 5228:org.codeaurora.ims/1001 (adj 15): empty #17
,11-08 19:52:39.618   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-08 19:52:46.693   926  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-08 19:52:48.979  5585  5632 I com.test.thalitest.ThaliTestRunner: Running UT
,11-08 19:52:49.040  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 19:52:49.041  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@206fc63 added. We now have 3 listener(s)
11-08 19:52:49.041  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 19:52:49.041  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 19:52:49.041  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 19:52:49.042  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 19:52:49.042  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571d060 added. We now have 3 listener(s)
11-08 19:52:49.042  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 19:52:49.042  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 19:52:49.052  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 19:52:49.057  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 19:52:49.057  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:49.057  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:49.057  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:49.057  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:49.057  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:52:49.057  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:52:49.057  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 19:52:49.058  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:52:49.058  5585  5632 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 19:52:49.064  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:49.067  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-08 19:52:49.067  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 19:52:49.067  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 19:52:49.067  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 19:52:49.068  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 19:52:49.068  5585  5632 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-08 19:52:49.068  5585  5632 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-08 19:52:49.068  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 19:52:49.069  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 19:52:49.069  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 19:52:49.069  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 19:52:49.069  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-08 19:52:49.070  5585  5632 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-08 19:52:49.071  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-08 19:52:49.072  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:49.073  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-08 19:52:49.073  5585  5632 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 19:52:49.073  5585  5632 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 19:52:49.073  5585  5632 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-08 19:52:49.073  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-08 19:52:49.074  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 19:52:49.074  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 19:52:49.074  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 19:52:49.074  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:52:49.074  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 19:52:49.075  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 19:52:49.075  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 19:52:49.075  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 19:52:49.076  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 19:52:49.076  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 19:52:49.076  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:52:49.076  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 19:52:49.076  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 19:52:49.076  5585  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 19:52:49.079  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 19:52:49.079  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 19:52:49.080  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-08 19:52:49.081  5585  5638 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 19:52:49.087  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 19:52:49.084  4868  4868 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31136]" dev="sockfs" ino=31136 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 19:52:49.089  5585  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 19:52:49.084  4868  4868 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31136]" dev="sockfs" ino=31136 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 19:52:49.090  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 19:52:49.091  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 19:52:49.094  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.094  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 19:52:49.095  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 19:52:49.095  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-08 19:52:49.097  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 19:52:49.097  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.097  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.097  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.097  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.098  5585  5632 D BluetoothAdapter: STATE_ON
,11-08 19:52:49.104  4648  4661 D BtGatt.GattService: registerClient() - UUID=fe3c6047-895f-43f7-9b74-ab94c68f381d
,11-08 19:52:49.105  4648  4708 D BtGatt.GattService: onClientRegistered() - UUID=fe3c6047-895f-43f7-9b74-ab94c68f381d, clientIf=5
,11-08 19:52:49.106  5585  5595 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 19:52:49.108  4648  4710 D BtGatt.AdvertiseManager: message : 0
,11-08 19:52:49.111  4648  4710 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 19:52:49.129  4648  4708 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 19:52:49.137  4648  4708 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 19:52:49.139  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.139  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.139  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 19:52:49.139  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.139  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.140  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.140  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.140  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.140  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 19:52:49.141  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 19:52:49.141  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.143  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.143  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.143  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.144  5585  5632 I io.jxcore.node.ConnectionHelper: start: OK
11-08 19:52:49.144  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 19:52:49.144  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.144  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:49.144  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 19:52:49.144  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.144  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:49.144  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-08 19:52:49.145  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 19:52:49.145  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 19:52:49.145  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.145  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.145  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 19:52:49.145  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 19:52:49.148  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-08 19:52:49.148  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 19:52:49.148  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.148  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-08 19:52:49.148  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.149  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:49.149  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 19:52:49.649  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-08 19:52:49.650  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-08 19:52:49.650  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-08 19:52:49.650  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 19:52:49.650  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-08 19:52:49.651  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-08 19:52:49.651  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 19:52:49.651  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-08 19:52:49.651  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 19:52:49.651  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-08 19:52:49.651  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-08 19:52:49.651  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-08 19:52:49.652  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-08 19:52:49.652  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-08 19:52:49.652  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-08 19:52:49.652  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-08 19:52:49.653  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-08 19:52:49.653  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-08 19:52:49.653  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-08 19:52:49.653  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-08 19:52:49.654  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-08 19:52:49.654  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-08 19:52:49.654  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-08 19:52:49.654  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-08 19:52:49.654  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-08 19:52:49.655  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-08 19:52:49.655  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-08 19:52:49.655  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-08 19:52:49.655  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-08 19:52:49.656  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-08 19:52:49.657  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-08 19:52:49.657  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-08 19:52:49.657  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-08 19:52:49.658  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-08 19:52:49.658  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-08 19:52:49.658  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-08 19:52:49.659  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 19:52:49.659  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-08 19:52:49.659  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 19:52:49.660  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 19:52:49.661  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 19:52:49.661  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 19:52:49.661  5585  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 19:52:49.661  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 19:52:49.661  5585  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 19:52:49.661  5585  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 19:52:49.661  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-08 19:52:49.661  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 19:52:49.661  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 19:52:49.662  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 19:52:49.662  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 19:52:49.662  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.663  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.664  5585  5632 D BluetoothAdapter: STATE_ON
11-08 19:52:49.664  5585  5632 D BluetoothLeScanner: could not find callback wrapper
11-08 19:52:49.665  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 19:52:49.665  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.665  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.665  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 19:52:49.665  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.667  4648  4710 D BtGatt.AdvertiseManager: message : 1
11-08 19:52:49.667  4648  4710 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 19:52:49.675  4648  4708 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 19:52:49.675  4648  4708 D BtGatt.GattService: Client app is not null!
,11-08 19:52:49.676  4648  4661 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 19:52:49.677  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 19:52:49.677  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.677  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 19:52:49.677  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.677  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.677  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.677  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 19:52:49.678  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 19:52:49.678  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.678  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.678  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-08 19:52:49.678  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.680  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.680  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:52:49.680  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.680  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.680  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.680  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.680  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.680  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 19:52:49.680  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 19:52:49.681  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 19:52:49.681  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.683  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:49.683  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.683  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.684  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 19:52:49.684  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 19:52:49.684  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 19:52:49.684  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 19:52:49.684  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:52:49.684  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:52:49.684  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:52:49.685  5585  5632 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 19:52:49.685  5585  5632 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 19:52:49.685  5585  5632 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-08 19:52:49.685  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-08 19:52:49.686  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 19:52:49.686  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 19:52:49.686  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 19:52:49.686  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:52:49.687  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 19:52:49.688  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 19:52:49.688  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 19:52:49.688  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 19:52:49.688  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 19:52:49.688  5585  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 19:52:49.688  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 19:52:49.688  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 19:52:49.689  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:52:49.689  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 19:52:49.689  5585  5641 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 19:52:49.688  4661  4661 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31140]" dev="sockfs" ino=31140 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 19:52:49.688  4661  4661 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31140]" dev="sockfs" ino=31140 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 19:52:49.694  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 19:52:49.694  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 19:52:49.694  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 19:52:49.696  5585  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 19:52:49.699  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 19:52:49.700  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 19:52:49.700  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 19:52:49.702  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.702  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 19:52:49.702  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 19:52:49.702  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-08 19:52:49.703  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 19:52:49.703  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.703  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.703  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.703  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.704  5585  5632 D BluetoothAdapter: STATE_ON
11-08 19:52:49.706  4648  4661 D BtGatt.GattService: registerClient() - UUID=c5568e34-57fa-4dcc-8c37-7e967c159f41
11-08 19:52:49.707  4648  4708 D BtGatt.GattService: onClientRegistered() - UUID=c5568e34-57fa-4dcc-8c37-7e967c159f41, clientIf=5
11-08 19:52:49.708  5585  5596 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 19:52:49.708  4648  4710 D BtGatt.AdvertiseManager: message : 0
11-08 19:52:49.711  4648  4710 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 19:52:49.719   926  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-08 19:52:49.723  4648  4708 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-08 19:52:49.730  4648  4708 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-08 19:52:49.731  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.731  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.731  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 19:52:49.731  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.731  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.731  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.731  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.731  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.731  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 19:52:49.733  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 19:52:49.733  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.734  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.734  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.734  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:49.734  5585  5632 I io.jxcore.node.ConnectionHelper: start: OK
11-08 19:52:49.734  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 19:52:49.735  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.735  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:49.735  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 19:52:49.735  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.735  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:49.735  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.735  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 19:52:49.735  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 19:52:49.735  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.736  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.736  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 19:52:49.736  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.739  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.739  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 19:52:49.739  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.740  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.741  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 19:52:49.742  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:49.742  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 19:52:50.239  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-08 19:52:50.239  5585  5632 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 19:52:50.239  5585  5632 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 19:52:50.240  5585  5632 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-08 19:52:50.240  5585  5632 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-08 19:52:50.240  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,11-08 19:52:50.241  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 19:52:50.241  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 19:52:50.241  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 19:52:50.241  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-08 19:52:50.241  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 19:52:50.241  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 19:52:50.241  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 19:52:50.241  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 19:52:50.241  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-08 19:52:50.241  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.243  4648  4710 D BtGatt.AdvertiseManager: message : 1
11-08 19:52:50.244  4648  4710 D BtGatt.AdvertiseManager: stop advertise for client 5
11-08 19:52:50.244  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-08 19:52:50.259  4648  4708 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 19:52:50.260  4648  4708 D BtGatt.GattService: Client app is not null!
11-08 19:52:50.262  4648  4868 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 19:52:50.263  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 19:52:50.263  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.264  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 19:52:50.264  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.264  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.264  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 19:52:50.264  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.264  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 19:52:50.264  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 19:52:50.265  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-08 19:52:50.265  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 19:52:50.265  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.265  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.266  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.266  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.267  5585  5632 D BluetoothAdapter: STATE_ON
,11-08 19:52:50.273  4648  4859 D BtGatt.GattService: registerClient() - UUID=b0aac498-51ac-4717-b7ac-051246cc6ca0
,11-08 19:52:50.275  4648  4708 D BtGatt.GattService: onClientRegistered() - UUID=b0aac498-51ac-4717-b7ac-051246cc6ca0, clientIf=5
11-08 19:52:50.276  5585  5595 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 19:52:50.278  4648  4710 D BtGatt.AdvertiseManager: message : 0
,11-08 19:52:50.283  4648  4710 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 19:52:50.297  4648  4708 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 19:52:50.305  4648  4708 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 19:52:50.306  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.306  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.306  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-08 19:52:50.306  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.306  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.307  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.307  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.307  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.307  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 19:52:50.307  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 19:52:50.307  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 19:52:50.307  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-08 19:52:50.307  5585  5632 I io.jxcore.node.ConnectionHelper: start: OK
,11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.308  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.308  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:50.309  5585  5632 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-08 19:52:50.309  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-08 19:52:50.309  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 19:52:50.309  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 19:52:50.309  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 19:52:50.309  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 19:52:50.309  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 19:52:50.309  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-08 19:52:50.309  5585  5641 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 19:52:50.310  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 19:52:50.310  5585  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 19:52:50.310  5585  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 19:52:50.310  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 19:52:50.310  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 19:52:50.310  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-08 19:52:50.310  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-08 19:52:50.310  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 19:52:50.310  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.310  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.311  5585  5632 D BluetoothAdapter: STATE_ON
11-08 19:52:50.311  5585  5632 D BluetoothLeScanner: could not find callback wrapper
11-08 19:52:50.311  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 19:52:50.311  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.311  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.311  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 19:52:50.312  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.312  4648  4710 D BtGatt.AdvertiseManager: message : 1
11-08 19:52:50.313  4648  4710 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 19:52:50.322  4648  4708 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 19:52:50.322  4648  4708 D BtGatt.GattService: Client app is not null!
,11-08 19:52:50.323  4648  4859 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.324  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.324  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 19:52:50.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.326  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.326  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:52:50.326  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.326  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.326  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.326  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.326  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.326  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 19:52:50.326  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 19:52:50.327  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 19:52:50.327  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.328  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.328  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-,08 19:52:50.328  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.328  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 19:52:50.328  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 19:52:50.328  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 19:52:50.328  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 19:52:50.329  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:52:50.329  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:52:50.329  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:52:50.330  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-08 19:52:50.330  5585  5632 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-08 19:52:50.332  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-08 19:52:50.332  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-08 19:52:50.333  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,11-08 19:52:50.333  5585  5632 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-08 19:52:50.334  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-08 19:52:50.334  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-08 19:52:50.335  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-08 19:52:50.335  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 19:52:50.335  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 19:52:50.335  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 19:52:50.335  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 19:52:50.335  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 19:52:50.335  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-08 19:52:50.335  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 19:52:50.335  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 19:52:50.335  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 19:52:50.336  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 19:52:50.336  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 19:52:50.336  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 19:52:50.336  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-08 19:52:50.337  5585  5632 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-08 19:52:50.337  5585  5632 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-08 19:52:50.340  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
,11-08 19:52:50.340  5585  5632 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-08 19:52:50.341  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-08 19:52:50.341  5585  5632 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-08 19:52:50.342  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-08 19:52:50.342  5585  5632 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-08 19:52:50.342  5585  5632 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-08 19:52:50.342  5585  5632 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-08 19:52:50.342  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 19:52:50.342  5585  5632 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-08 19:52:50.342  5585  5632 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-08 19:52:50.343  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-08 19:52:50.343  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 19:52:50.343  5585  5632 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-08 19:52:50.343  5585  5632 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-08 19:52:50.343  5585  5632 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,11-08 19:52:50.343  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 19:52:50.343  5585  5632 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-08 19:52:50.344  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-08 19:52:50.344  5585  5632 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 19:52:50.344  5585  5632 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 19:52:50.344  5585  5632 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-08 19:52:50.344  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-08 19:52:50.344  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 19:52:50.344  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 19:52:50.344  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 19:52:50.344  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 19:52:50.346  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 19:52:50.346  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 19:52:50.346  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 19:52:50.346  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 19:52:50.346  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 19:52:50.346  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 19:52:50.346  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-08 19:52:50.346  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:52:50.346  5585  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 19:52:50.346  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-08 19:52:50.347  5585  5645 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 19:52:50.348  4859  4859 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32007]" dev="sockfs" ino=32007 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 19:52:50.350  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 19:52:50.350  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 19:52:50.350  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 19:52:50.350  5585  5645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 19:52:50.348  4859  4859 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32007]" dev="sockfs" ino=32007 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 19:52:50.354  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 19:52:50.354  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 19:52:50.354  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 19:52:50.358  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.358  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 19:52:50.358  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 19:52:50.358  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-08 19:52:50.358  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 19:52:50.358  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.358  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.359  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.359  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.360  5585  5632 D BluetoothAdapter: STATE_ON
11-08 19:52:50.364  4648  4660 D BtGatt.GattService: registerClient() - UUID=4838b083-9eb9-42fd-902e-c7b68356955b
11-08 19:52:50.364  4648  4708 D BtGatt.GattService: onClientRegistered() - UUID=4838b083-9eb9-42fd-902e-c7b68356955b, clientIf=5
11-08 19:52:50.365  5585  5595 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 19:52:50.366  4648  4710 D BtGatt.AdvertiseManager: message : 0
11-08 19:52:50.367  4648  4710 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 19:52:50.376  4648  4708 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 19:52:50.381  4648  4708 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 19:52:50.382  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.382  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.382  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 19:52:50.382  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.382  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.382  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.382  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.382  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.382  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 19:52:50.384  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 19:52:50.384  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.385  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.385  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.385  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.385  5585  5632 I io.jxcore.node.ConnectionHelper: start: OK
11-08 19:52:50.385  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 19:52:50.385  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-08 19:52:50.386  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:50.386  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 19:52:50.386  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,11-08 19:52:50.386  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:50.386  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.386  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 19:52:50.386  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 19:52:50.386  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.386  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.386  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 19:52:50.386  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.388  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-08 19:52:50.388  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 19:52:50.388  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.388  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.388  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 19:52:50.388  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 19:52:50.389  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 19:52:50.887  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 19:52:50.887  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 19:52:50.887  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 19:52:50.887  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 19:52:50.888  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 19:52:50.888  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-08 19:52:50.888  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 19:52:50.888  5585  5645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 19:52:50.888  5585  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 19:52:50.888  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-08 19:52:50.888  5585  5645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 19:52:50.889  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@206fc63 removed from the list
11-08 19:52:50.889  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 19:52:50.889  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 19:52:50.889  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 19:52:50.889  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-08 19:52:50.890  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 19:52:50.890  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.890  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 19:52:50.890  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.890  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-08 19:52:50.890  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 19:52:50.892  5585  5632 D BluetoothAdapter: STATE_ON
11-08 19:52:50.893  5585  5632 D BluetoothLeScanner: could not find callback wrapper
11-08 19:52:50.893  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 19:52:50.893  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.893  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.894  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 19:52:50.894  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.896  4648  4710 D BtGatt.AdvertiseManager: message : 1
11-08 19:52:50.897  4648  4710 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 19:52:50.924  4648  4708 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 19:52:50.924  4648  4708 D BtGatt.GattService: Client app is not null!
,11-08 19:52:50.925  4648  4868 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 19:52:50.926  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 19:52:50.926  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.927  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 19:52:50.927  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.927  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.927  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.927  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 19:52:50.928  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-08 19:52:50.928  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.928  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.928  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 19:52:50.928  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.930  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.930  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:52:50.931  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.931  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:50.931  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.931  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.931  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.931  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 19:52:50.931  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-08 19:52:50.932  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,11-08 19:52:50.932  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.934  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.934  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.934  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:50.934  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571d060 removed from the list
11-08 19:52:50.934  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:52:50.934  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-08 19:52:50.934  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-08 19:52:50.934  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 19:52:50.935  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 19:52:51.436  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 19:52:55.938  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-08 19:52:55.941  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 19:52:55.941  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 19:52:55.943  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 19:52:55.944  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-08 19:52:55.944  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 19:52:55.944  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 19:52:55.945  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 19:52:55.945  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-08 19:52:55.945  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 19:52:55.945  5585  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 19:52:55.947  5585  5646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 19:52:55.947  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-08 19:52:55.949  5585  5632 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-08 19:52:55.950  5585  5632 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,11-08 19:52:55.950  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 19:52:55.951  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-08 19:52:55.951  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 19:52:55.952  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-08 19:52:55.955  5585  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 19:52:55.951  4868  4868 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30561]" dev="sockfs" ino=30561 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 19:52:55.951  4868  4868 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[30561]" dev="sockfs" ino=30561 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 19:52:55.961  5585  5632 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-08 19:52:55.961  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-08 19:52:55.961  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 19:52:55.961  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 19:52:55.961  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 19:52:55.962  5585  5646 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 19:52:55.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 19:52:55.962  5585  5646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-08 19:52:55.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 19:52:55.962  5585  5646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 19:52:55.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 19:52:55.962  5585  5632 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@206fc63 not in the list
11-08 19:52:55.962  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 19:52:55.962  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-08 19:52:55.962  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 19:52:55.962  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 19:52:55.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 19:52:55.962  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 19:52:55.962  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 19:52:55.963  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-08 19:52:55.963  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 19:52:55.963  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:55.965  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:55.965  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:52:55.965  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:52:55.965  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:52:55.965  5585  5632 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@571d060 not in the list
11-08 19:52:55.965  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:52:55.965  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-08 19:52:55.965  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 19:52:55.965  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:52:55.965  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 19:52:55.965  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:52:55.967  5585  5632 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-08 19:52:55.968  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-08 19:52:55.968  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 19:52:55.968  5585  5632 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-08 19:52:55.968  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-08 19:52:55.968  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-08 19:52:55.968  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 19:52:55.969  5585  5632 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-08 19:52:55.969  5585  5632 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-08 19:52:55.971  5585  5632 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-08 19:52:55.971  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-08 19:52:55.971  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-08 19:52:55.972  5585  5632 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-08 19:52:55.972  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-08 19:52:55.972  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-08 19:52:55.974  5585  5632 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,11-08 19:52:55.974  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-08 19:52:55.974  5585  5632 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-08 19:52:55.974  5585  5632 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-08 19:52:55.975  5585  5632 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-08 19:52:55.975  5585  5632 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-08 19:52:55.975  5585  5632 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-08 19:52:55.976  5585  5632 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-08 19:52:55.976  5585  5632 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-08 19:52:55.976  5585  5632 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-08 19:52:55.977  5585  5632 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-08 19:52:55.977  5585  5632 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-08 19:52:55.977  5585  5632 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-08 19:52:55.978  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-08 19:52:55.978  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4a1190 added. We now have 3 listener(s)
,11-08 19:52:55.980  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 19:52:55.980  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 19:52:55.980  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 19:52:55.980  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 19:52:55.980  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c438a89 added. We now have 3 listener(s)
,11-08 19:52:55.980  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 19:52:55.981  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 19:52:55.984  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 19:52:55.988  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 19:52:55.988  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:55.988  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:55.988  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:55.988  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:55.988  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:52:55.988  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:52:55.988  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:52:55.989  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 19:52:55.989  5585  5632 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 19:52:55.991  5585  5632 D BluetoothAdapter: enable(): BT is already enabled..!
,11-08 19:52:55.991   926  3793 D WifiService: setWifiEnabled: true pid=5585, uid=10077
11-08 19:52:55.991   926  3793 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 19:52:55.992  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:55.993  5585  5632 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-08 19:52:55.995  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:55.996  5585  5632 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
11-08 19:52:55.996  5585  5632 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-08 19:52:55.999   926   936 D WifiService: setWifiEnabled: false pid=5585, uid=10077
,11-08 19:52:55.999   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 19:52:56.003   926  2931 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-08 19:52:56.003   926  2931 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-08 19:52:56.003   926  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 19:52:56.003   926  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 19:52:56.011   926  5357 D DhcpClient: Clearing IP address
,11-08 19:52:56.011   507   919 D CommandListener: Clearing all IP addresses on wlan0
,11-08 19:52:56.018   507   919 D CommandListener: Setting iface cfg
,11-08 19:52:56.024  3572  5412 V NativeCrypto: Read error: ssl=0x7f90a55180: I/O error during system call, Connection timed out
,11-08 19:52:56.026  3572  5412 V NativeCrypto: SSL shutdown failed: ssl=0x7f90a55180: I/O error during system call, Broken pipe
11-08 19:52:56.028   926  5358 D DhcpClient: Receive thread stopped
11-08 19:52:56.028   926  3785 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-08 19:52:56.029   926  5355 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-08 19:52:56.031   926  5355 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-08 19:52:56.032   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-08 19:52:56.032   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-08 19:52:56.032   926  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-08 19:52:56.033   926  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-08 19:52:56.035   926   926 D RttService: SCAN_AVAILABLE : 1
,11-08 19:52:56.036   926  3051 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 19:52:56.036   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-08 19:52:56.038   535   535 E Parcel  : Reading a NULL string not supported here.
11-08 19:52:56.041   926  2946 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-08 19:52:56.046  3743  3842 W QCNEJ   : |CORE| network lost: 100
11-08 19:52:56.047   926  3741 I ActivityManager: Killing 5244:com.android.settings/1000 (adj 15): empty #17
,11-08 19:52:56.048  3743  3842 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-08 19:52:56.056   926  2931 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-08 19:52:56.074   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 19:52:56.075   926  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 19:52:56.095   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-08 19:52:56.095   507   919 D CommandListener: Clearing all IP addresses on wlan0
,11-08 19:52:56.096   926  2946 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-08 19:52:56.096   926  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-08 19:52:56.099   926  2931 D DhcpClient: doQuit
11-08 19:52:56.100   926  2931 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-08 19:52:56.100   926   943 D Tethering: MasterInitialState.processMessage what=3
11-08 19:52:56.100  5262  5262 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@44c13c5 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-08 19:52:56.100   926  5357 D DhcpClient: onQuitting
11-08 19:52:56.101  3429  3429 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-08 19:52:56.106  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:56.106  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:56.106  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:56.106  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:56.106  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:56.106  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:56.106  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:56.106  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:52:56.107  3945  3945 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-08 19:52:56.108  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:52:56.108  3958  3958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-08 19:52:56.112  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:56.112  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:56.112  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:56.112  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 19:52:56.112  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:56.112  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:56.112  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:56.112  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 19:52:56.114  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-08 19:52:56.117  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:56.117  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:56.117  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:56.117  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 19:52:56.117  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:56.117  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:56.117  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:56.117  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 19:52:56.119  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:52:56.122  3958  3958 D SystemUpdateService: onCreate
,11-08 19:52:56.123  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:56.123  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:56.123  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:56.123  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 19:52:56.123  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:56.123  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:56.123  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:56.123  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 19:52:56.124  3429  3429 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-08 19:52:56.124  3958  3958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-08 19:52:56.125  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:52:56.127  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:56.128  3958  5663 I SystemUpdateService: active receiver: enabled
11-08 19:52:56.129  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:56.131  3429  3429 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-08 19:52:56.144  3958  3958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-08 19:52:56.148  3958  4212 I iu.UploadsManager: num queued entries: 0
11-08 19:52:56.149  3958  4212 I iu.UploadsManager: num updated entries: 0
11-08 19:52:56.149  3958  4212 I iu.SyncManager: NEXT; no task
11-08 19:52:56.152  3958  5663 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-08 19:52:56.153  3958  3958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 19:52:56.154  3958  3958 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 19:52:56.156  5385  5385 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 19:52:56.157   507   919 E Netd    : netlink response contains error (No such file or directory)
11-08 19:52:56.158   507   919 D TetherController: Setting IP forward enable = 0
11-08 19:52:56.159  3429  3429 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-08 19:52:56.160   926  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-08 19:52:56.161  5385  5385 D SprintDMHelper: simOperator: 
11-08 19:52:56.161  5385  5385 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 19:52:56.169  3958  5663 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-08 19:52:56.169  3958  5663 I SystemUpdateService: now status is 0 (complete)
11-08 19:52:56.170  3958  5663 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 19:52:56.171  3958  5663 I SystemUpdateService: file has been verified
11-08 19:52:56.172  3958  5663 I SystemUpdateService: OTA package size = 21989297
11-08 19:52:56.173  3429  3429 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-08 19:52:56.182  3958  5663 I SystemUpdateService: showing system update notification
,11-08 19:52:56.188   926  3784 I ActivityManager: Start proc 5671:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-08 19:52:56.196   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 19:52:56.198  3958  3958 D SystemUpdateService: onDestroy
,11-08 19:52:56.203   507   919 D TetherController: Setting IP forward enable = 0
,11-08 19:52:56.232  5671  5671 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-08 19:52:56.238   926  3741 I ActivityManager: Killing 5039:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-08 19:52:56.277   926  2931 D wifi    : In wifi stop Hal
,11-08 19:52:56.277   926  2931 D wifi    : halHandle = 0x7f8f3d8400, mVM = 0x7faba0d140, mCls = 0x100a02
11-08 19:52:56.277   926  3428 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-08 19:52:56.277   926  3428 D WifiHAL : Got a signal to exit!!!
,11-08 19:52:56.277   926  3428 I WifiHAL : Exit wifi_event_loop
11-08 19:52:56.277   926  2931 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-08 19:52:56.277   926  2931 E WifiHAL : Event processing terminated
11-08 19:52:56.278   926  2931 D wifi    : In wifi cleaned up handler
,11-08 19:52:56.278   926  2931 I WifiHAL : Internal cleanup completed
11-08 19:52:56.280  4493  4493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 19:52:56.281  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:56.283  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:56.283  3728  4156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 19:52:56.284  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:56.299   926  3428 D wifi    : set interface wlan0 flags (DOWN)
,11-08 19:52:56.299   926  2931 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 19:52:56.466  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 19:52:56.507  5585  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:56.509   926   943 D Tethering: InitialState.processMessage what=4
,11-08 19:52:56.510   926  3785 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,11-08 19:52:56.511   926  3785 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 19:52:56.517   507   919 D SoftapController: Softap fwReload - Ok
,11-08 19:52:56.518   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-08 19:52:56.523   507   919 D CommandListener: Setting iface cfg
,11-08 19:52:56.523   507   919 D CommandListener: Trying to bring down wlan0
11-08 19:52:56.524   507   919 D CommandListener: Clearing all IP addresses on wlan0
,11-08 19:52:56.528   926  2931 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 19:52:57.016   926  3793 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,11-08 19:52:57.020   926  3793 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 19:52:57.117   926  2931 D wifi    : set interface wlan0 flags (UP)
,11-08 19:52:57.118   926  2931 I WifiHAL : Initializing wifi
11-08 19:52:57.118   926  2931 I WifiHAL : Creating socket
,11-08 19:52:57.125   926  2931 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-08 19:52:57.125   926  2931 D wifi    : Did set static halHandle = 0x7f8f3d8400
,11-08 19:52:57.126   926  2931 D wifi    : halHandle = 0x7f8f3d8400, mVM = 0x7faba0d140, mCls = 0x20179a
11-08 19:52:57.126   926  2931 D wifi    : array field set
11-08 19:52:57.126   926  2931 I WifiNative-HAL: interface[0] = wlan0
11-08 19:52:57.128   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-08 19:52:57.129   926  5692 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547864019968
11-08 19:52:57.129   926  5692 D wifi    : waitForHalEvents called, vm = 0x7faba0d140, obj = 0x20179a, env = 0x7f91472e00
,11-08 19:52:57.209  5693  5693 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 19:52:57.230   926  2931 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-08 19:52:57.236  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:57.240  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:57.245  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:57.292  5693  5693 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 19:52:57.318  5693  5693 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 19:52:57.318  5693  5693 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 19:52:57.334   926  2931 D WifiConfigStore: Loading config and enabling all networks 
,11-08 19:52:57.342  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:57.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:57.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:57.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:57.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:57.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:57.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:57.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:52:57.344  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:52:57.351  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:57.351  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:57.351  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:57.351  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:57.351  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:57.351  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:57.351  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:57.351  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:52:57.353  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:52:57.355   926  2931 D WifiConfigStore: loaded 0 passpoint configs
,11-08 19:52:57.356  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:57.356  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:57.356  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:57.356  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:57.356  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:52:57.356  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:57.356  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:57.356  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:52:57.356   926  2931 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-08 19:52:57.356   926  2931 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-08 19:52:57.357   926  2931 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-08 19:52:57.357   926  2931 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-08 19:52:57.357   926  2931 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-08 19:52:57.358  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 19:52:57.358   926  2931 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-08 19:52:57.359   926  2931 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-08 19:52:57.359   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-08 19:52:57.359   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-08 19:52:57.359   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 19:52:57.359   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-08 19:52:57.359   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-08 19:52:57.363   926  2931 D WifiNative-HAL: Setting external_sim to 1
,11-08 19:52:57.363  4493  4493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 19:52:57.363   926  2931 D wifi    : setting dfs flag to true, 0x7fa0fb1aa0
11-08 19:52:57.363   926  2931 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 19:52:57.363   926  2931 D wifi    : setting scan oui 0x7fa0fb1aa0
11-08 19:52:57.363   926  2931 D WifiHAL : Sending mac address OUI
,11-08 19:52:57.366   926  2931 E native  : do suspend false
,11-08 19:52:57.372   926  2931 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-08 19:52:57.373   926   926 D RttService: SCAN_AVAILABLE : 3
,11-08 19:52:57.373   507   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-08 19:52:57.373   926  3051 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-08 19:52:57.374   507   919 D CommandListener: Setting iface cfg
,11-08 19:52:57.377   926  2927 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,11-08 19:52:57.377   926  2927 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-08 19:52:57.385   926  2927 D WifiNative-HAL: p2pGetDeviceAddress
11-08 19:52:57.385   926  2927 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-08 19:52:57.390   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=105284 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-08 19:52:57.529  5585  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:57.539  4648  4704 D BluetoothAdapterState: Current state: ON, message: 23
,11-08 19:52:57.539  4648  4704 D BluetoothAdapterProperties: Setting state to 13
11-08 19:52:57.539  4648  4704 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-08 19:52:57.540  4648  4704 D BluetoothAdapterProperties: onBluetoothDisable()
,11-08 19:52:57.543  4648  4704 I BluetoothAdapterState: Entering PendingCommandState
,11-08 19:52:57.544  4648  4648 D BluetoothMapService: onReceive
11-08 19:52:57.544  4648  4648 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 19:52:57.544  4648  4648 D BluetoothMapService: STATE_TURNING_OFF
11-08 19:52:57.545  4648  4648 D BluetoothMapService: MAP Service closeService in
11-08 19:52:57.545  4648  4648 D BluetoothMapMasInstance0: MAP Service shutdown
11-08 19:52:57.545  4648  4648 D ObexServerSockets0: shutdown(block = true)
11-08 19:52:57.546  4648  4648 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 19:52:57.546  4648  4648 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 19:52:57.547  4648  4871 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-08 19:52:57.547  4648  4870 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-08 19:52:57.547  4648  4855 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-08 19:52:57.552  4648  4648 I BtOppRfcommListener: stopping Accept Thread
11-08 19:52:57.553  4648  5275 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-08 19:52:57.553  4648  5275 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-08 19:52:57.554  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 19:52:57.555  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:57.555  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:57.555  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:57.555  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:57.555  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 19:52:57.555  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:57.555  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:57.555  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 19:52:57.556  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:52:57.556  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 19:52:57.559  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:52:57.560  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:57.560  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:57.560  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:57.560  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:57.560  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 19:52:57.560  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:57.560  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:57.560  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:52:57.561  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 19:52:57.561  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:52:57.565  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 19:52:57.565  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:52:57.565  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:52:57.565  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:52:57.565  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:52:57.565  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 19:52:57.565  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:52:57.565  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:52:57.565  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:52:57.566  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:52:57.566  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:52:57.573   926   939 I ActivityManager: Start proc 5697:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-08 19:52:57.573  4648  4708 D BluetoothAdapterProperties: Scan Mode:20
,11-08 19:52:57.574  4648  4704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-08 19:52:57.577  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:57.578  4648  4648 D HeadsetService: Received stop request...Stopping profile...
11-08 19:52:57.579  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:57.580  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:57.581  3098  3112 D BluetoothHeadset: Proxy object disconnected
11-08 19:52:57.581   926   926 D BluetoothHeadset: Proxy object disconnected
11-08 19:52:57.581  3765  3782 D BluetoothHeadset: Proxy object disconnected
,11-08 19:52:57.582  3098  3098 D HeadsetProfile: Bluetooth service disconnected
11-08 19:52:57.582   926   926 D BluetoothHeadset: Proxy object disconnected
11-08 19:52:57.582   926   926 D BluetoothHeadset: Proxy object disconnected
,11-08 19:52:57.584  4648  4648 D A2dpService: Received stop request...Stopping profile...
,11-08 19:52:57.584  4648  4863 D A2dpStateMachine: Exit Disconnected: -1
11-08 19:52:57.585   926   926 D BluetoothA2dp: Proxy object disconnected
,11-08 19:52:57.585  3098  3098 D BluetoothA2dp: Proxy object disconnected
11-08 19:52:57.586  4648  4648 V BluetoothAdapterState: isTurningOff()=true
11-08 19:52:57.586  4648  4648 V BluetoothAdapterState: isTurningOn()=false
11-08 19:52:57.586  4648  4648 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:52:57.586  4648  4648 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:52:57.590  4648  4648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-08 19:52:57.590  4648  4648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-08 19:52:57.590  4648  4838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 19:52:57.590  4648  4838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 19:52:57.590  4648  4838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 19:52:57.590  4648  4708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-08 19:52:57.591  4648  4708 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-08 19:52:57.591  4648  4648 D HidService: Received stop request...Stopping profile...
11-08 19:52:57.591  4648  4648 D HidService: Stopping Bluetooth HidService
11-08 19:52:57.592  3098  3098 D BluetoothInputDevice: Proxy object disconnected
11-08 19:52:57.592  3098  3098 D HidProfile: Bluetooth service disconnected
11-08 19:52:57.593  4648  4648 D HealthService: Received stop request...Stopping profile...
11-08 19:52:57.595  4648  4648 V BluetoothAdapterState: isTurningOff()=true
11-08 19:52:57.596  4648  4648 V BluetoothAdapterState: isTurningOn()=false
11-08 19:52:57.596  4648  4648 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:52:57.596  4648  4648 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 19:52:57.597  4648  4838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 19:52:57.597  4648  4838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
,11-08 19:52:57.598  4648  4708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,11-08 19:52:57.598  4648  4838 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-08 19:52:57.598  4648  4648 D PanService: Received stop request...Stopping profile...
11-08 19:52:57.598  4648  4838 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 19:52:57.598  4648  4838 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 19:52:57.598  4648  4838 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 19:52:57.599  3098  3098 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 19:52:57.599  3098  3098 D PanProfile: Bluetooth service disconnected
11-08 19:52:57.599  4648  4648 D BluetoothMapService: Received stop request...Stopping profile...
,11-08 19:52:57.599  4648  4648 D BluetoothMapService: stop()
11-08 19:52:57.600  4648  4648 D BluetoothMapAppObserver: deinitObservers()
11-08 19:52:57.600  4648  4648 D BluetoothMapAppObserver: removeReceiver()
11-08 19:52:57.602  3098  3098 D BluetoothMap: Proxy object disconnected
11-08 19:52:57.602  3098  3098 D MapProfile: Bluetooth service disconnected
11-08 19:52:57.604  4648  4648 D SapService: Received stop request...Stopping profile...
11-08 19:52:57.604  4648  4648 V SapService: stop()
11-08 19:52:57.605  4648  4648 V BluetoothAdapterState: isTurningOff()=true
11-08 19:52:57.605  4648  4648 V BluetoothAdapterState: isTurningOn()=false
11-08 19:52:57.605  4648  4648 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:52:57.605  4648  4648 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:52:57.606  4648  4648 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-08 19:52:57.606  4648  4648 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 19:52:57.606  4648  4648 V BluetoothAdapterState: isTurningOff()=true
11-08 19:52:57.606  4648  4648 V BluetoothAdapterState: isTurningOn()=false
11-08 19:52:57.606  4648  4648 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:52:57.606  4648  4648 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:52:57.606  4648  4648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 19:52:57.607  4648  4708 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 19:52:57.607  4648  4708 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-08 19:52:57.608  4648  4648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-08 19:52:57.608  4648  4648 V BluetoothAdapterState: isTurningOff()=true
11-08 19:52:57.608  4648  4648 V BluetoothAdapterState: isTurningOn()=false
11-08 19:52:57.608  4648  4648 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:52:57.608  4648  4648 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:52:57.608  4648  4648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-08 19:52:57.608  4648  4648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-08 19:52:57.609  4648  4648 D BluetoothMapService: MAP Service closeService in
11-08 19:52:57.610  4648  4648 V BluetoothAdapterState: isTurningOff()=true
11-08 19:52:57.610  4648  4648 V BluetoothAdapterState: isTurningOn()=false
11-08 19:52:57.610  4648  4648 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:52:57.610  4648  4648 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:52:57.610  4648  4648 D BluetoothMapService: cleanup()
11-08 19:52:57.610  4648  4648 D BluetoothMapService: MAP Service closeService in
11-08 19:52:57.610  4648  4648 V BluetoothAdapterState: isTurningOff()=true
,11-08 19:52:57.610  4648  4648 V BluetoothAdapterState: isTurningOn()=false
11-08 19:52:57.610  4648  4648 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:52:57.610  4648  4648 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:52:57.610  4648  4704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-08 19:52:57.610  4648  4704 D BluetoothAdapterProperties: Setting state to 15
11-08 19:52:57.610  4648  4704 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-08 19:52:57.611  4648  4704 I BluetoothAdapterState: Entering BleOnState
11-08 19:52:57.611   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-08 19:52:57.611   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:52:57.612  3765  3994 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:52:57.612  3098  4014 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 19:52:57.613   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:52:57.613   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:52:57.613  3098  3110 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-08 19:52:57.614  3098  3112 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-08 19:52:57.615  3098  4014 D BluetoothPan: onBluetoothStateChange on: false
,11-08 19:52:57.615  3098  3110 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 19:52:57.617  3098  3112 D BluetoothMap: onBluetoothStateChange: up=false
,11-08 19:52:57.620  4648  4704 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-08 19:52:57.620  4648  4704 D BluetoothAdapterProperties: Setting state to 16
11-08 19:52:57.620  4648  4704 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 19:52:57.621  4648  4704 D BluetoothAdapterProperties: onBleDisable
11-08 19:52:57.621  4648  4704 I BluetoothAdapterState: Entering PendingCommandState
11-08 19:52:57.622  4648  4705 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-08 19:52:57.623  4648  4838 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-08 19:52:57.623  4648  4838 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-08 19:52:57.624  4648  4708 D BluetoothAdapterProperties: Scan Mode:20
11-08 19:52:57.625  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:57.627  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:57.630  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:57.631  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:57.632  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:57.634  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:52:57.636  5697  5697 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-08 19:52:57.651  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 19:52:57.657   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c2c1311:true
11-08 19:52:57.659  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 19:52:57.672   926  3784 I ActivityManager: Start proc 5709:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-08 19:52:57.679  5697  5697 D LocalBluetoothProfileManager: Adding local MAP profile
,11-08 19:52:57.683  5697  5697 D BluetoothMap: Create BluetoothMap proxy object
,11-08 19:52:57.689  5697  5697 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-08 19:52:57.708  5709  5709 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-08 19:52:57.710  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,11-08 19:52:57.712   926  3741 I ActivityManager: Killing 5262:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-08 19:52:57.832  4648  4708 I bt_hci  : shut_down
,11-08 19:52:57.834  4648  4713 D bt_hwcfg: hw_epilog_process
,11-08 19:52:57.834  4648  4713 I bt_vendor: low_power_mode_cb
,11-08 19:52:57.837  4648  4713 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-08 19:52:57.837  4648  4713 I bt_vendor: epilog_cb
,11-08 19:52:57.837  4648  4713 I bt_hci  : epilog_finished_callback
,11-08 19:52:57.839  4648  4708 I bt_hci_h4: hal_close
11-08 19:52:57.839  4648  4708 I bt_userial_vendor: device fd = 54 close
,11-08 19:52:57.914  5709  5709 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 19:52:57.914  5709  5709 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 19:52:57.914  5709  5709 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 19:52:57.914  5709  5709 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 19:52:57.914  5709  5709 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.k.d(PG:583)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 19:52:57.914  5709  5709 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:52:57.914  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 19:52:57.915  5709  5709 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 19:52:57.915  5709  5709 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:52:57.915  5709  5709 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 19:52:57.930  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 19:52:57.935  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 19:52:57.943  5697  5697 D DockEventReceiver: finishStartingService: stopping service
11-08 19:52:57.947   926  3785 I ActivityManager: Killing 3865:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-08 19:52:57.988  4648  4705 D bt_stack_manager: event_shut_down_stack finished.
11-08 19:52:57.989  4648  4704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-08 19:52:57.991  4648  4704 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-08 19:52:57.991  4648  4648 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 19:52:57.991  4648  4648 D BtGatt.GattService: Received stop request...Stopping profile...
11-08 19:52:57.991  4648  4648 D BtGatt.GattService: stop()
11-08 19:52:57.992  4648  4648 D BtGatt.AdvertiseManager: advertise clients cleared
11-08 19:52:57.993  4648  4648 V BluetoothAdapterState: isTurningOff()=false
11-08 19:52:57.993  4648  4648 V BluetoothAdapterState: isTurningOn()=false
11-08 19:52:57.994  4648  4648 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:52:57.994  4648  4648 V BluetoothAdapterState: isBleTurningOff()=true
11-08 19:52:57.994  4648  4704 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-08 19:52:57.994  4648  4704 D BluetoothAdapterProperties: Setting state to 10
11-08 19:52:57.994  4648  4704 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-08 19:52:57.995   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-08 19:52:57.995  4648  4704 I BluetoothAdapterState: Entering OffState
,11-08 19:52:58.000  4648  4648 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-08 19:52:58.001  4648  4648 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-08 19:52:58.001  4648  4648 I BluetoothServiceJni: cleanupNative: return from cleanup
11-08 19:52:58.002  4648  4705 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-08 19:52:58.005  4648  4648 I art     : System.exit called, status: 0
,11-08 19:52:58.005  4648  4648 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 19:52:58.037  5585  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:52:58.039   380   380 E lowmemorykiller: Error writing /proc/4648/oom_score_adj; errno=22
,11-08 19:52:58.040   926   943 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,11-08 19:52:58.040   926   943 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
11-08 19:52:58.041   926   943 W ActivityManager: Application dead when creating service ServiceRecord{d14a280 u0 com.android.bluetooth/.btservice.AdapterService}
,11-08 19:52:58.046   926   943 I ActivityManager: Process com.android.bluetooth (pid 4648) has died
,11-08 19:52:58.047   926   943 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
11-08 19:52:58.048   926   943 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
,11-08 19:52:58.048   926   943 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
11-08 19:52:58.048   926   943 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-08 19:52:58.048   926   943 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
11-08 19:52:58.048   926   943 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
11-08 19:52:58.048   926   943 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
11-08 19:52:58.048   926   943 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
11-08 19:52:58.048   926   943 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
11-08 19:52:58.048   926   943 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
11-08 19:52:58.048   926   943 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
11-08 19:52:58.048   926   943 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
11-08 19:52:58.048   926   943 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
11-08 19:52:58.048   926   943 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
11-08 19:52:58.048   926   943 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
11-08 19:52:58.048   926   943 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
11-08 19:52:58.048   926   943 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
11-08 19:52:58.048   926   943 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:52:58.048   926   943 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:52:58.048   926   943 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 19:52:58.048   926   943 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-08 19:52:58.049   926  3741 W ActivityManager: Spurious death for ProcessRecord{d20035d 0:com.android.bluetooth/1002}, curProc for 4648: null
,11-08 19:52:58.174  5709  5735 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-08 19:52:58.183   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13bcfe:true
,11-08 19:53:00.452  5693  5693 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 19:53:00.457  5693  5693 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 19:53:00.462  5693  5693 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 19:53:00.472  5693  5693 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 19:53:00.518   926  2931 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-08 19:53:00.520   926  2931 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-08 19:53:00.520   926  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 19:53:00.531   926  2931 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-08 19:53:00.567   926  2931 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-08 19:53:00.574  5693  5693 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-08 19:53:01.001  5693  5693 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-08 19:53:01.031  5693  5693 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-08 19:53:01.032  5693  5693 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-08 19:53:01.040   926   943 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,11-08 19:53:01.044   926  2931 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 19:53:01.044   926  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-08 19:53:01.044   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-08 19:53:01.074   926   943 I ActivityManager: Start proc 5745:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-08 19:53:01.076   926  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 19:53:01.090   507   919 D CommandListener: Setting iface cfg
,11-08 19:53:01.098   926  2931 D WifiStateMachine: Start Dhcp Watchdog 2
,11-08 19:53:01.109   926  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-08 19:53:01.110   926  2946 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-08 19:53:01.110   926  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-08 19:53:01.112   926  5758 D DhcpClient: Receive thread started
,11-08 19:53:01.150  5745  5745 D AdapterServiceConfig: Adding HeadsetService
,11-08 19:53:01.150  5745  5745 D AdapterServiceConfig: Adding A2dpService
11-08 19:53:01.150  5745  5745 D AdapterServiceConfig: Adding HidService
11-08 19:53:01.150  5745  5745 D AdapterServiceConfig: Adding HealthService
11-08 19:53:01.151  5745  5745 D AdapterServiceConfig: Adding PanService
11-08 19:53:01.151  5745  5745 D AdapterServiceConfig: Adding GattService
11-08 19:53:01.151  5745  5745 D AdapterServiceConfig: Adding BluetoothMapService
,11-08 19:53:01.151  5745  5745 D AdapterServiceConfig: Adding SapService
,11-08 19:53:01.162   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7411d2f:true
,11-08 19:53:01.163  5745  5745 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 19:53:01.165  5745  5745 I bt_bluedroid: init
,11-08 19:53:01.165  5745  5759 I BluetoothAdapterState: Entering OffState
,11-08 19:53:01.167  5745  5760 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-08 19:53:01.168  5745  5760 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 19:53:01.168  5745  5760 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-08 19:53:01.168  5745  5760 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-08 19:53:01.168  5745  5745 I bt_bluedroid: get_profile_interface socket
,11-08 19:53:01.170  5745  5763 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 19:53:01.170  5745  5745 I bt_bluedroid: get_profile_interface sdp
,11-08 19:53:01.172  5745  5763 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 19:53:01.174  5745  5756 I bt_bluedroid: config_hci_snoop_log
,11-08 19:53:01.175   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-08 19:53:01.180  5745  5759 D BluetoothAdapterState: Current state: OFF, message: 0
,11-08 19:53:01.180  5745  5759 D BluetoothAdapterProperties: Setting state to 14
11-08 19:53:01.180  5745  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-08 19:53:01.181  5745  5759 D BluetoothBondStateMachine: make
,11-08 19:53:01.183  5745  5764 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-08 19:53:01.186  5745  5759 I BluetoothAdapterState: Entering PendingCommandState
,11-08 19:53:01.187  5745  5745 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-08 19:53:01.189  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
11-08 19:53:01.190  5745  5745 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 19:53:01.190  5745  5745 D BtGatt.GattService: Received start request. Starting profile...
,11-08 19:53:01.190  5745  5745 D BtGatt.GattService: start()
11-08 19:53:01.190  5745  5745 I bt_bluedroid: get_profile_interface gatt
,11-08 19:53:01.191  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:01.192  5745  5745 D BtGatt.AdvertiseManager: advertise manager created
11-08 19:53:01.192   926  2931 E native  : do suspend false
,11-08 19:53:01.197  5745  5745 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:01.197  5745  5745 V BluetoothAdapterState: isTurningOn()=false
11-08 19:53:01.197  5745  5745 V BluetoothAdapterState: isBleTurningOn()=true
11-08 19:53:01.197  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:01.197  5745  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 19:53:01.199  5745  5759 I bt_bluedroid: bt_bluedroid
,11-08 19:53:01.199  5745  5760 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-08 19:53:01.199  5745  5760 I bt_hci  : start_up
,11-08 19:53:01.201   926  5757 D DhcpClient: Broadcasting DHCPDISCOVER
,11-08 19:53:01.205  5745  5760 I bt_vendor: alloc value 0xf4226871
,11-08 19:53:01.205  5745  5760 I bt_vendor: init
11-08 19:53:01.205  5745  5760 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 19:53:01.205  5745  5760 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 19:53:01.215   926  5758 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172731, domain null
,11-08 19:53:01.215   926  5757 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172731 seconds
,11-08 19:53:01.216   926  5757 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-08 19:53:01.228   926  5758 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-08 19:53:01.228   926  5757 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-08 19:53:01.230   507   919 D CommandListener: Setting iface cfg
,11-08 19:53:01.233   926  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-08 19:53:01.235   926  5757 D DhcpClient: Scheduling renewal in 86399s
,11-08 19:53:01.241   926  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-08 19:53:01.241   926  2931 D WifiConfigStore: No blacklist allowed without epno enabled
11-08 19:53:01.242   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-08 19:53:01.244   926  2931 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-08 19:53:01.246   926  2946 D ConnectivityService: Adding iface wlan0 to network 101
,11-08 19:53:01.275   926  2946 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-08 19:53:01.275   926  2946 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-08 19:53:01.276   926  2946 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-08 19:53:01.277   926  2946 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-08 19:53:01.278   926  2946 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-08 19:53:01.283   926  2946 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-08 19:53:01.286   926  2946 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-08 19:53:01.286   926  2946 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-08 19:53:01.287   926  2946 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-08 19:53:01.287   926  2931 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-08 19:53:01.287   926  2946 D ConnectivityService:    accepting network in place of null
,11-08 19:53:01.287   926  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 19:53:01.287   926  2946 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 19:53:01.295   926  5744 D NetlinkSocketObserver: NeighborEvent{elapsedMs=109188, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-08 19:53:01.306   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 19:53:01.313  5745  5760 D bt_hci  : start_up starting async portion
,11-08 19:53:01.313  5745  5767 I bt_hci  : event_finish_startup
11-08 19:53:01.313  5745  5767 I bt_hci_h4: hal_open
,11-08 19:53:01.313  5745  5767 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-08 19:53:01.314  5745  5767 I bt_userial_vendor: device fd = 54 open
11-08 19:53:01.311  5776  5776 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 19:53:01.325   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 19:53:01.327  5745  5767 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 19:53:01.329  5745  5767 D bt_hwcfg: Chipset BCM4358A3
11-08 19:53:01.329  5745  5767 D bt_hwcfg: Target name = [BCM4358A3]
11-08 19:53:01.330  5745  5767 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
11-08 19:53:01.330   926  2946 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-08 19:53:01.330  3743  3842 W QCNEJ   : |CORE| network available: 101
,11-08 19:53:01.330   926  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-08 19:53:01.331   926  2946 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-08 19:53:01.331  3743  3842 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-08 19:53:01.332   926   943 D Tethering: MasterInitialState.processMessage what=3
11-08 19:53:01.333  3743  3842 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-08 19:53:01.333  3743  3842 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-08 19:53:01.338  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:53:01.338  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:01.338  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:01.338  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:01.338  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:01.338  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 19:53:01.338  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:01.338  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:01.338  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 19:53:01.339  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 19:53:01.339  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:01.340  3945  3945 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-08 19:53:01.341  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 19:53:01.342  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:01.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:01.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:01.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:01.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 19:53:01.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:01.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:01.342  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:53:01.343  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:53:01.343  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:01.344  3958  3958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-08 19:53:01.346  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:53:01.346  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:01.346  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:01.346  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:01.346  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:01.346  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 19:53:01.346  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:01.346  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:01.346  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:53:01.347  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:53:01.347  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:53:01.348  3958  3958 D SystemUpdateService: onCreate
,11-08 19:53:01.352  3958  3958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 19:53:01.361  3958  3958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-08 19:53:01.366  3958  4212 I iu.UploadsManager: num queued entries: 0
,11-08 19:53:01.366  3958  4212 I iu.UploadsManager: num updated entries: 0
11-08 19:53:01.367  3958  4212 I iu.SyncManager: NEXT; no task
,11-08 19:53:01.369   926  5743 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-08 19:53:01.372  3958  3958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 19:53:01.373  3958  3958 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 19:53:01.375  5385  5385 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 19:53:01.378  5385  5385 D SprintDMHelper: simOperator: 
,11-08 19:53:01.379  5385  5385 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 19:53:01.390  3958  5782 I SystemUpdateService: active receiver: enabled
,11-08 19:53:01.410  3958  5782 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 19:53:01.412  3958  5782 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-08 19:53:01.412  3958  5782 I SystemUpdateService: now status is 0 (complete)
11-08 19:53:01.412  3958  5782 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 19:53:01.412  3958  5782 I SystemUpdateService: file has been verified
11-08 19:53:01.412  3958  5782 I SystemUpdateService: OTA package size = 21989297
,11-08 19:53:01.421  3958  5782 I SystemUpdateService: showing system update notification
,11-08 19:53:01.427   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 19:53:01.430   926  5743 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 08 Nov 2016 18:53:01 GMT], X-Android-Received-Millis=[1478631181429], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478631181392]}
,11-08 19:53:01.431   926  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-08 19:53:01.431  3958  3958 D SystemUpdateService: onDestroy
11-08 19:53:01.431   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-08 19:53:01.431   926  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-08 19:53:01.432   926  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-08 19:53:01.558  5745  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 19:53:01.680  5745  5767 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-08 19:53:01.681  5745  5767 D bt_hwcfg: Settlement delay -- 100 ms
11-08 19:53:01.681  5745  5767 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 19:53:01.805  5745  5767 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-08 19:53:01.805  5745  5767 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-08 19:53:01.807  5745  5767 I bt_hwcfg: vendor lib fwcfg completed
11-08 19:53:01.807  5745  5767 I bt_vendor: firmware callback
11-08 19:53:01.807  5745  5767 I bt_hci  : firmware_config_callback
,11-08 19:53:01.816  5745  5790 I bt_btu  : btu_task pending for preload complete event
,11-08 19:53:01.817  5745  5790 I bt_btu_task: Bluetooth chip preload is complete
11-08 19:53:01.817  5745  5790 I bt_btu  : btu_task received preload complete event
,11-08 19:53:01.825  5745  5790 I         : BTE_InitTraceLevels -- TRC_HCI
,11-08 19:53:01.825  5745  5790 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-08 19:53:01.825  5745  5790 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-08 19:53:01.825  5745  5790 I         : BTE_InitTraceLevels -- TRC_AVDT
11-08 19:53:01.825  5745  5790 I         : BTE_InitTraceLevels -- TRC_AVRC
11-08 19:53:01.825  5745  5790 I         : BTE_InitTraceLevels -- TRC_A2D
11-08 19:53:01.826  5745  5790 I         : BTE_InitTraceLevels -- TRC_BNEP
11-08 19:53:01.826  5745  5790 I         : BTE_InitTraceLevels -- TRC_BTM
,11-08 19:53:01.826  5745  5790 I         : BTE_InitTraceLevels -- TRC_GAP
11-08 19:53:01.826  5745  5790 I         : BTE_InitTraceLevels -- TRC_PAN
11-08 19:53:01.826  5745  5790 I         : BTE_InitTraceLevels -- TRC_SDP
11-08 19:53:01.826  5745  5790 I         : BTE_InitTraceLevels -- TRC_GATT
,11-08 19:53:01.826  5745  5790 I         : BTE_InitTraceLevels -- TRC_SMP
11-08 19:53:01.827  5745  5790 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-08 19:53:01.827  5745  5790 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 19:53:01.908  5745  5790 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41a4549
,11-08 19:53:01.908  5745  5790 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41a4549 
,11-08 19:53:01.921  5745  5763 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-08 19:53:01.922  5745  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-08 19:53:01.923  5745  5763 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-08 19:53:01.925  5745  5763 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 19:53:01.928  5745  5763 D BluetoothAdapterProperties: Scan Mode:20
,11-08 19:53:01.929  5745  5763 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 19:53:01.929  5745  5763 D bt_hci  : do_postload posting postload work item
11-08 19:53:01.930  5745  5767 I bt_hci  : event_postload
11-08 19:53:01.930  5745  5767 I bt_vendor: sco_config_cb
11-08 19:53:01.930  5745  5767 I bt_hci  : sco_config_callback postload finished.
11-08 19:53:01.933  5745  5763 D bt_bte_conf: Device ID record 1 : primary
11-08 19:53:01.933  5745  5763 D bt_bte_conf:   vendorId            = 000f
11-08 19:53:01.933  5745  5763 D bt_bte_conf:   vendorIdSource      = 0001
11-08 19:53:01.934  5745  5763 D bt_bte_conf:   product             = 1200
11-08 19:53:01.934  5745  5763 D bt_bte_conf:   version             = 1436
11-08 19:53:01.934  5745  5763 D bt_bte_conf:   clientExecutableURL = 
11-08 19:53:01.934  5745  5763 D bt_bte_conf:   serviceDescription  = 
11-08 19:53:01.934  5745  5763 D bt_bte_conf:   documentationURL    = 
11-08 19:53:01.934  5745  5763 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-08 19:53:01.934  5745  5760 D bt_stack_manager: event_start_up_stack finished
11-08 19:53:01.935  5745  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-08 19:53:01.936  5745  5759 D BluetoothAdapterProperties: Setting state to 15
11-08 19:53:01.936  5745  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 19:53:01.937  5745  5759 I BluetoothAdapterState: Entering BleOnState
11-08 19:53:01.938  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:01.940  5745  5767 I bt_vendor: low_power_mode_cb
11-08 19:53:01.942  5745  5759 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-08 19:53:01.942  5745  5759 D BluetoothAdapterProperties: Setting state to 11
,11-08 19:53:01.942  5745  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-08 19:53:01.944  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:01.948  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
11-08 19:53:01.948  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:01.950  5745  5745 D HeadsetService: Received start request. Starting profile...
,11-08 19:53:01.954  5745  5745 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
11-08 19:53:01.955  5745  5745 D HeadsetStateMachine: make
11-08 19:53:01.959  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:01.964  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:01.965  5745  5759 I BluetoothAdapterState: Entering PendingCommandState
,11-08 19:53:01.967  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:01.968  5745  5745 D HeadsetStateMachine: max_hf_connections = 1
,11-08 19:53:01.969  5745  5745 I bt_bluedroid: get_profile_interface handsfree
11-08 19:53:01.969  5745  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-08 19:53:01.969  5745  5763 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-08 19:53:01.972  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
11-08 19:53:01.973  5745  5745 D A2dpService: Received start request. Starting profile...
11-08 19:53:01.973  5745  5745 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-08 19:53:01.974  5745  5745 I bt_bluedroid: get_profile_interface avrcp
,11-08 19:53:01.980  5745  5745 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-08 19:53:01.980  5745  5745 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-08 19:53:01.980  5745  5745 D A2dpStateMachine: make
,11-08 19:53:01.981  5745  5745 I bt_bluedroid: get_profile_interface a2dp
,11-08 19:53:01.982  5745  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-08 19:53:01.983  5745  5797 D A2dpStateMachine: Enter Disconnected: -2
,11-08 19:53:01.984  5745  5745 I BluetoothHidServiceJni: classInitNative: succeeds
,11-08 19:53:01.985  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:01.987  5745  5745 D HidService: Received start request. Starting profile...
,11-08 19:53:01.987  5745  5745 I bt_bluedroid: get_profile_interface hidhost
11-08 19:53:01.987  5745  5745 D HidService: setHidService(): set to: null
,11-08 19:53:01.987  5745  5763 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf418556d
,11-08 19:53:01.988  5745  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-08 19:53:01.988  5745  5745 I BluetoothHealthServiceJni: classInitNative: succeeds
11-08 19:53:01.989  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
11-08 19:53:01.989  5745  5745 D HealthService: Received start request. Starting profile...
11-08 19:53:01.991  5745  5745 I bt_bluedroid: get_profile_interface health
11-08 19:53:01.992  5697  5697 D BluetoothInputDevice: Proxy object connected
11-08 19:53:01.993  5745  5745 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-08 19:53:01.992  5697  5697 D HidProfile: Bluetooth service connected
11-08 19:53:01.993  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:01.995  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 19:53:01.996  5745  5745 D PanService: Received start request. Starting profile...
11-08 19:53:01.996  5745  5745 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 19:53:01.996  5697  5697 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 19:53:01.996  5745  5745 I bt_bluedroid: get_profile_interface pan
11-08 19:53:01.997  5697  5697 D PanProfile: Bluetooth service connected
11-08 19:53:01.999  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
11-08 19:53:01.999  5745  5763 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-08 19:53:02.000  5697  5697 D BluetoothMap: Proxy object connected
11-08 19:53:02.000  5745  5745 D BluetoothMapService: Received start request. Starting profile...
11-08 19:53:02.000  5745  5745 D BluetoothMapService: start()
11-08 19:53:02.000  5697  5697 D MapProfile: Bluetooth service connected
,11-08 19:53:02.001  5697  5697 D BluetoothMap: getConnectedDevices()
11-08 19:53:02.001  5697  5697 D BluetoothMap: Bluetooth is Not enabled
,11-08 19:53:02.003  5745  5745 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-08 19:53:02.004  5745  5745 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-08 19:53:02.004  5745  5745 D BluetoothMapAppObserver: createReceiver()
11-08 19:53:02.005  5745  5745 D BluetoothMapAppObserver: initObservers()
11-08 19:53:02.005  5745  5745 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-08 19:53:02.011  5745  5745 V SapService: SapBinder()
,11-08 19:53:02.011  5745  5745 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:02.012  5745  5745 D SapService: Received start request. Starting profile...
11-08 19:53:02.012  5745  5745 V SapService: start()
,11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isTurningOff()=false
,11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isTurningOff()=false
,11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.015  5745  5795 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isTurningOn()=true
,11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.015  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.016  5745  5745 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:02.016  5745  5745 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:02.016  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.016  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.016  5745  5745 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:02.016  5745  5745 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:02.016  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.016  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.017  5745  5745 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:02.017  5745  5745 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:02.017  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.017  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.017  5745  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-08 19:53:02.017  5745  5759 D BluetoothAdapterProperties: ScanMode =  20
11-08 19:53:02.017  5745  5759 D BluetoothAdapterProperties: State =  11
11-08 19:53:02.019  5745  5759 D BluetoothAdapterProperties: Setting state to 12
11-08 19:53:02.019  5745  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-08 19:53:02.020   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 19:53:02.020  5745  5759 I BluetoothAdapterState: Entering OnState
11-08 19:53:02.021  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 19:53:02.021  5745  5763 D BluetoothAdapterProperties: Scan Mode:21
11-08 19:53:02.021  5745  5763 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 19:53:02.021  5697  5707 D BluetoothMap: onBluetoothStateChange: up=true
,11-08 19:53:02.021  5697  5708 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 19:53:02.022   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:02.022  3765  3782 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:02.022   926   926 D BluetoothA2dp: Proxy object connected
11-08 19:53:02.023  5697  5707 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 19:53:02.023  5585  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-08 19:53:02.024  3098  3112 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 19:53:02.026  5585  5585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-08 19:53:02.027  3098  3098 D BluetoothInputDevice: Proxy object connected
11-08 19:53:02.027  3098  3098 D HidProfile: Bluetooth service connected
11-08 19:53:02.027   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:02.027   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:02.027  5697  5708 D BluetoothPan: onBluetoothStateChange on: true
11-08 19:53:02.028  3098  3110 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 19:53:02.030  3098  4014 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:02.030  3098  3098 D BluetoothA2dp: Proxy object connected
11-08 19:53:02.030  5745  5745 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 19:53:02.031  5745  5745 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-08 19:53:02.032  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:02.032  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:02.032  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:02.032  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:02.032  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:02.032  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:02.032  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:02.032  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 19:53:02.032  5745  5745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 19:53:02.033  3098  3110 D BluetoothPan: onBluetoothStateChange on: true
11-08 19:53:02.035  3098  3110 D BluetoothPbap: onBluetoothStateChange: up=true
,11-08 19:53:02.035  3098  3098 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 19:53:02.035  3098  3098 D PanProfile: Bluetooth service connected
11-08 19:53:02.036  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:02.036  5745  5745 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 19:53:02.036  3098  3112 D BluetoothMap: onBluetoothStateChange: up=true
11-08 19:53:02.037  5745  5745 D ObexServerSockets: Succeed to create listening sockets 
11-08 19:53:02.037  5745  5745 D ObexServerSockets0: startAccept()
11-08 19:53:02.037  5745  5745 D ObexServerSockets0: prepareForNewConnect()
11-08 19:53:02.038  3098  3098 D BluetoothMap: Proxy object connected
11-08 19:53:02.038  3098  3098 D MapProfile: Bluetooth service connected
11-08 19:53:02.038  3098  3098 D BluetoothMap: getConnectedDevices()
,11-08 19:53:02.039   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,11-08 19:53:02.040  5745  5745 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-08 19:53:02.040  5745  5745 D BluetoothSdpJni: SDP Create record success - handle: 0
11-08 19:53:02.041  5745  5745 D BluetoothMapService: onReceive
11-08 19:53:02.041  5745  5745 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 19:53:02.041  5745  5745 D BluetoothMapService: STATE_ON
11-08 19:53:02.042  5745  5803 D ObexServerSockets0: Accepting socket connection...
11-08 19:53:02.042  5745  5804 D ObexServerSockets0: Accepting socket connection...
,11-08 19:53:02.044  5697  5697 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-08 19:53:02.044  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:02.044  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:02.044  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:02.044  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:02.044  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:02.044  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:02.044  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:02.044  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:53:02.045  5745  5805 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 19:53:02.047  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:02.048  5745  5805 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 19:53:02.048  5697  5697 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-08 19:53:02.048  5745  5805 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-08 19:53:02.052  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:02.052  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:02.052  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:02.052  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:02.052  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:02.052  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:02.052  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:02.052  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:53:02.053  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:53:02.053  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 19:53:02.055  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:02.057  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:02.059  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 19:53:02.060  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:02.061  5697  5697 D BluetoothA2dp: Proxy object connected
11-08 19:53:02.061  5585  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:02.062  5745  5745 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 19:53:02.062  5745  5745 D ObexServerSockets0: prepareForNewConnect()
11-08 19:53:02.062  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-08 19:53:02.062  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 19:53:02.065  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 19:53:02.066  5585  5632 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-08 19:53:02.067  5585  5632 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-08 19:53:02.070  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,11-08 19:53:02.071  5745  5759 D BluetoothAdapterState: Current state: ON, message: 23
11-08 19:53:02.071  5745  5759 D BluetoothAdapterProperties: Setting state to 13
11-08 19:53:02.071  5745  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-08 19:53:02.071  5745  5759 D BluetoothAdapterProperties: onBluetoothDisable()
11-08 19:53:02.071  5697  5697 D BluetoothPbap: Proxy object connected
11-08 19:53:02.072  5745  5759 I BluetoothAdapterState: Entering PendingCommandState
11-08 19:53:02.072  5697  5697 D PbapServerProfile: Bluetooth service connected
11-08 19:53:02.074  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 19:53:02.074  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:02.074  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:02.074  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:02.074  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:02.074  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 19:53:02.074  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:02.074  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:02.074  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:53:02.075  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:53:02.075  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:53:02.077  5745  5763 D BluetoothAdapterProperties: Scan Mode:20
,11-08 19:53:02.078  5745  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-08 19:53:02.078  3098  3098 D BluetoothPbap: Proxy object connected
11-08 19:53:02.078  3098  3098 D PbapServerProfile: Bluetooth service connected
,11-08 19:53:02.083  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 19:53:02.083  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:02.083  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:02.083  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:02.083  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:02.083  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 19:53:02.083  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:02.083  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:02.083  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:53:02.083  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:53:02.084  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:53:02.089  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 19:53:02.090  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:02.090  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:02.090  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:02.090  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:02.090  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 19:53:02.090  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:02.090  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:02.090  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 19:53:02.090  5585  5585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 19:53:02.090  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:02.093  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:02.093  3098  3098 D BluetoothPbap: Proxy object disconnected
11-08 19:53:02.093  3098  3098 D PbapServerProfile: Bluetooth service disconnected
11-08 19:53:02.095  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:02.096  5697  5697 D BluetoothPbap: Proxy object disconnected
11-08 19:53:02.096  5697  5697 D PbapServerProfile: Bluetooth service disconnected
,11-08 19:53:02.098  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 19:53:02.099  5745  5745 D BluetoothMapService: onReceive
11-08 19:53:02.099  5745  5745 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 19:53:02.099  5745  5745 D BluetoothMapService: STATE_TURNING_OFF
11-08 19:53:02.099  5745  5745 D HeadsetService: Received stop request...Stopping profile...
11-08 19:53:02.101  5745  5745 D A2dpService: Received stop request...Stopping profile...
11-08 19:53:02.101  5745  5797 D A2dpStateMachine: Exit Disconnected: -1
11-08 19:53:02.102   926   926 D BluetoothA2dp: Proxy object disconnected
11-08 19:53:02.103  5745  5745 D HidService: Received stop request...Stopping profile...
11-08 19:53:02.103  5745  5745 D HidService: Stopping Bluetooth HidService
11-08 19:53:02.104  5745  5745 D HealthService: Received stop request...Stopping profile...
11-08 19:53:02.105  5745  5745 D PanService: Received stop request...Stopping profile...
11-08 19:53:02.107  5745  5745 D BluetoothMapService: Received stop request...Stopping profile...
11-08 19:53:02.107  5745  5745 D BluetoothMapService: stop()
11-08 19:53:02.107  5697  5697 D DockEventReceiver: finishStartingService: stopping service
11-08 19:53:02.108  5745  5745 D BluetoothMapAppObserver: deinitObservers()
11-08 19:53:02.108  5745  5745 D BluetoothMapAppObserver: removeReceiver()
11-08 19:53:02.108  5697  5697 D BluetoothA2dp: Proxy object disconnected
11-08 19:53:02.108  5697  5697 D BluetoothInputDevice: Proxy object disconnected
,11-08 19:53:02.108  5697  5697 D HidProfile: Bluetooth service disconnected
11-08 19:53:02.108  5697  5697 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-08 19:53:02.108  5697  5697 D PanProfile: Bluetooth service disconnected
,11-08 19:53:02.110  5697  5697 D BluetoothMap: Proxy object disconnected
,11-08 19:53:02.110  5697  5697 D MapProfile: Bluetooth service disconnected
11-08 19:53:02.111  5745  5745 D SapService: Received stop request...Stopping profile...
11-08 19:53:02.111  5745  5745 V SapService: stop()
11-08 19:53:02.111  3098  3098 D BluetoothA2dp: Proxy object disconnected
11-08 19:53:02.111  3098  3098 D BluetoothInputDevice: Proxy object disconnected
,11-08 19:53:02.111  3098  3098 D HidProfile: Bluetooth service disconnected
11-08 19:53:02.112  3098  3098 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 19:53:02.112  3098  3098 D PanProfile: Bluetooth service disconnected
11-08 19:53:02.112  3098  3098 D BluetoothMap: Proxy object disconnected
11-08 19:53:02.112  3098  3098 D MapProfile: Bluetooth service disconnected
11-08 19:53:02.114  5745  5745 V BluetoothAdapterState: isTurningOff()=true
,11-08 19:53:02.114  5745  5745 V BluetoothAdapterState: isTurningOn()=false
11-08 19:53:02.114  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.114  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 19:53:02.117  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 19:53:02.118  5745  5745 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-08 19:53:02.118  5745  5745 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-08 19:53:02.118  5745  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-08 19:53:02.118  5745  5790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-08 19:53:02.118  5745  5790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 19:53:02.118  5745  5790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 19:53:02.119  5745  5745 V BluetoothAdapterState: isTurningOff()=true
11-08 19:53:02.119  5745  5745 V BluetoothAdapterState: isTurningOn()=false
11-08 19:53:02.119  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 19:53:02.119  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.119  5745  5763 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
11-08 19:53:02.120  5745  5745 V BluetoothAdapterState: isTurningOff()=true
11-08 19:53:02.120  5745  5745 V BluetoothAdapterState: isTurningOn()=false
11-08 19:53:02.120  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.120  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.121  5745  5745 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-08 19:53:02.121  5745  5745 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 19:53:02.121  5745  5745 V BluetoothAdapterState: isTurningOff()=true
11-08 19:53:02.121  5745  5745 V BluetoothAdapterState: isTurningOn()=false
11-08 19:53:02.121  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.121  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.121  5745  5745 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 19:53:02.121  5745  5745 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-08 19:53:02.122  5745  5745 V BluetoothAdapterState: isTurningOff()=true
11-08 19:53:02.122  5745  5745 V BluetoothAdapterState: isTurningOn()=false
11-08 19:53:02.122  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.122  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.123  5745  5745 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-08 19:53:02.123  5745  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 19:53:02.123  5745  5745 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-08 19:53:02.123  5745  5763 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 19:53:02.123  5745  5790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 19:53:02.123  5745  5763 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-08 19:53:02.123  5745  5790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 19:53:02.123  5745  5790 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 19:53:02.123  5745  5790 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 19:53:02.123  5745  5790 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 19:53:02.123  5745  5790 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 19:53:02.124  5745  5745 D BluetoothMapService: MAP Service closeService in
11-08 19:53:02.124  5745  5745 D BluetoothMapMasInstance0: MAP Service shutdown
11-08 19:53:02.124  5745  5745 D ObexServerSockets0: shutdown(block = true)
11-08 19:53:02.125  5745  5745 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 19:53:02.125  5745  5803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-08 19:53:02.125  5745  5745 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 19:53:02.125  5745  5804 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-08 19:53:02.126  5745  5745 V BluetoothAdapterState: isTurningOff()=true
11-08 19:53:02.126  5745  5745 V BluetoothAdapterState: isTurningOn()=false
11-08 19:53:02.126  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 19:53:02.126  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.126  5745  5745 D BluetoothMapService: cleanup()
11-08 19:53:02.127  5745  5792 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-08 19:53:02.127  5745  5745 D BluetoothMapService: MAP Service closeService in
11-08 19:53:02.127  5745  5745 V BluetoothAdapterState: isTurningOff()=true
11-08 19:53:02.128  5745  5745 V BluetoothAdapterState: isTurningOn()=false
,11-08 19:53:02.128  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.128  5745  5745 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 19:53:02.129  5745  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-08 19:53:02.129  5745  5759 D BluetoothAdapterProperties: Setting state to 15
11-08 19:53:02.129  5745  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-08 19:53:02.130   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 19:53:02.130  5745  5759 I BluetoothAdapterState: Entering BleOnState
11-08 19:53:02.130  5697  5707 D BluetoothMap: onBluetoothStateChange: up=false
,11-08 19:53:02.131  5697  5708 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-08 19:53:02.131   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:53:02.132  3765  5650 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:53:02.132  5697  5707 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 19:53:02.133  3098  3112 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 19:53:02.133   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:53:02.133   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:53:02.133  5697  5708 D BluetoothPan: onBluetoothStateChange on: false
11-08 19:53:02.134  5697  5707 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 19:53:02.134  3098  4014 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 19:53:02.135  3098  3110 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:53:02.135  3098  3112 D BluetoothPan: onBluetoothStateChange on: false
,11-08 19:53:02.135  3098  4014 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 19:53:02.136  3098  3110 D BluetoothMap: onBluetoothStateChange: up=false
11-08 19:53:02.137  5697  5708 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 19:53:02.138  5745  5759 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-08 19:53:02.138  5745  5759 D BluetoothAdapterProperties: Setting state to 16
,11-08 19:53:02.138  5745  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 19:53:02.138  5745  5759 D BluetoothAdapterProperties: onBleDisable
11-08 19:53:02.138  5745  5759 I BluetoothAdapterState: Entering PendingCommandState
11-08 19:53:02.138  5745  5760 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-08 19:53:02.139  5745  5790 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-08 19:53:02.139  5745  5790 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 19:53:02.140  5745  5763 D BluetoothAdapterProperties: Scan Mode:20
,11-08 19:53:02.142  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:02.146  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:02.150  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:02.151  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:02.154  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 19:53:02.158  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 19:53:02.162  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,11-08 19:53:02.331   926  2946 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-08 19:53:02.340  5745  5763 I bt_hci  : shut_down
,11-08 19:53:02.340  5745  5767 D bt_hwcfg: hw_epilog_process
11-08 19:53:02.341  5745  5767 I bt_vendor: low_power_mode_cb
,11-08 19:53:02.343  5745  5767 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-08 19:53:02.343  5745  5767 I bt_vendor: epilog_cb
11-08 19:53:02.343  5745  5767 I bt_hci  : epilog_finished_callback
11-08 19:53:02.344  5745  5763 I bt_hci_h4: hal_close
11-08 19:53:02.344  5745  5763 I bt_userial_vendor: device fd = 54 close
,11-08 19:53:02.461  5745  5760 D bt_stack_manager: event_shut_down_stack finished.
,11-08 19:53:02.462  5745  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-08 19:53:02.465  5745  5759 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-08 19:53:02.465  5745  5745 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-08 19:53:02.466  5745  5745 D BtGatt.GattService: Received stop request...Stopping profile...
,11-08 19:53:02.466  5745  5745 D BtGatt.GattService: stop()
11-08 19:53:02.466  5745  5745 D BtGatt.AdvertiseManager: advertise clients cleared
11-08 19:53:02.468  5745  5745 V BluetoothAdapterState: isTurningOff()=false
,11-08 19:53:02.468  5745  5745 V BluetoothAdapterState: isTurningOn()=false
11-08 19:53:02.468  5745  5745 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:02.468  5745  5745 V BluetoothAdapterState: isBleTurningOff()=true
11-08 19:53:02.468  5745  5759 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-08 19:53:02.469  5745  5759 D BluetoothAdapterProperties: Setting state to 10
11-08 19:53:02.469  5745  5759 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-08 19:53:02.469  5745  5759 I BluetoothAdapterState: Entering OffState
11-08 19:53:02.470   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-08 19:53:02.479  5745  5745 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-08 19:53:02.480  5745  5745 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-08 19:53:02.480  5745  5745 I BluetoothServiceJni: cleanupNative: return from cleanup
11-08 19:53:02.482  5745  5760 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-08 19:53:02.488  5745  5745 I art     : System.exit called, status: 0
,11-08 19:53:02.488  5745  5745 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 19:53:02.514   926  3785 I ActivityManager: Process com.android.bluetooth (pid 5745) has died
,11-08 19:53:02.573  5585  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:02.578  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:02.600   926   943 I ActivityManager: Start proc 5817:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-08 19:53:02.668  5817  5817 D AdapterServiceConfig: Adding HeadsetService
,11-08 19:53:02.668  5817  5817 D AdapterServiceConfig: Adding A2dpService
11-08 19:53:02.669  5817  5817 D AdapterServiceConfig: Adding HidService
11-08 19:53:02.669  5817  5817 D AdapterServiceConfig: Adding HealthService
11-08 19:53:02.669  5817  5817 D AdapterServiceConfig: Adding PanService
11-08 19:53:02.669  5817  5817 D AdapterServiceConfig: Adding GattService
11-08 19:53:02.669  5817  5817 D AdapterServiceConfig: Adding BluetoothMapService
11-08 19:53:02.669  5817  5817 D AdapterServiceConfig: Adding SapService
,11-08 19:53:02.679   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b27bc00:true
,11-08 19:53:02.679  5817  5817 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 19:53:02.682  5817  5817 I bt_bluedroid: init
11-08 19:53:02.682  5817  5829 I BluetoothAdapterState: Entering OffState
,11-08 19:53:02.684  5817  5830 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-08 19:53:02.684  5817  5830 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 19:53:02.685  5817  5830 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-08 19:53:02.685  5817  5830 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-08 19:53:02.685  5817  5817 I bt_bluedroid: get_profile_interface socket
,11-08 19:53:02.686  5817  5833 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 19:53:02.687  5817  5817 I bt_bluedroid: get_profile_interface sdp
11-08 19:53:02.688  5817  5833 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 19:53:02.691  5817  5828 I bt_bluedroid: config_hci_snoop_log
,11-08 19:53:02.692   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-08 19:53:02.746  5817  5829 D BluetoothAdapterState: Current state: OFF, message: 0
,11-08 19:53:02.746  5817  5829 D BluetoothAdapterProperties: Setting state to 14
11-08 19:53:02.746  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-08 19:53:02.748  5817  5829 D BluetoothBondStateMachine: make
,11-08 19:53:02.749  5817  5834 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-08 19:53:02.751  5817  5829 I BluetoothAdapterState: Entering PendingCommandState
,11-08 19:53:02.752  5817  5817 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-08 19:53:02.754  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
11-08 19:53:02.755  5817  5817 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 19:53:02.755  5817  5817 D BtGatt.GattService: Received start request. Starting profile...
11-08 19:53:02.755  5817  5817 D BtGatt.GattService: start()
11-08 19:53:02.755  5817  5817 I bt_bluedroid: get_profile_interface gatt
11-08 19:53:02.756  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
11-08 19:53:02.756  5817  5817 D BtGatt.AdvertiseManager: advertise manager created
,11-08 19:53:02.760  5817  5817 V BluetoothAdapterState: isTurningOff()=false
,11-08 19:53:02.760  5817  5817 V BluetoothAdapterState: isTurningOn()=false
11-08 19:53:02.760  5817  5817 V BluetoothAdapterState: isBleTurningOn()=true
11-08 19:53:02.760  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:02.761  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 19:53:02.762  5817  5829 I bt_bluedroid: bt_bluedroid
11-08 19:53:02.762  5817  5830 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-08 19:53:02.762  5817  5830 I bt_hci  : start_up
,11-08 19:53:02.767  5817  5830 I bt_vendor: alloc value 0xf4226871
,11-08 19:53:02.767  5817  5830 I bt_vendor: init
11-08 19:53:02.767  5817  5830 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 19:53:02.767  5817  5830 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 19:53:02.877  5817  5830 D bt_hci  : start_up starting async portion
,11-08 19:53:02.878  5817  5837 I bt_hci  : event_finish_startup
,11-08 19:53:02.878  5817  5837 I bt_hci_h4: hal_open
,11-08 19:53:02.878  5817  5837 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-08 19:53:02.874  5838  5838 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 19:53:02.880  5817  5837 I bt_userial_vendor: device fd = 54 open
,11-08 19:53:02.894  5817  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 19:53:02.897  5817  5837 D bt_hwcfg: Chipset BCM4358A3
,11-08 19:53:02.897  5817  5837 D bt_hwcfg: Target name = [BCM4358A3]
11-08 19:53:02.898  5817  5837 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-08 19:53:03.082  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 19:53:03.299  5817  5837 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-08 19:53:03.299  5817  5837 D bt_hwcfg: Settlement delay -- 100 ms
11-08 19:53:03.300  5817  5837 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 19:53:03.424  5817  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-08 19:53:03.424  5817  5837 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-08 19:53:03.426  5817  5837 I bt_hwcfg: vendor lib fwcfg completed
,11-08 19:53:03.426  5817  5837 I bt_vendor: firmware callback
,11-08 19:53:03.426  5817  5837 I bt_hci  : firmware_config_callback
,11-08 19:53:03.434  5817  5840 I bt_btu  : btu_task pending for preload complete event
11-08 19:53:03.434  5817  5840 I bt_btu_task: Bluetooth chip preload is complete
,11-08 19:53:03.434  5817  5840 I bt_btu  : btu_task received preload complete event
,11-08 19:53:03.442  5817  5840 I         : BTE_InitTraceLevels -- TRC_HCI
11-08 19:53:03.442  5817  5840 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-08 19:53:03.442  5817  5840 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-08 19:53:03.442  5817  5840 I         : BTE_InitTraceLevels -- TRC_AVDT
11-08 19:53:03.442  5817  5840 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-08 19:53:03.442  5817  5840 I         : BTE_InitTraceLevels -- TRC_A2D
11-08 19:53:03.442  5817  5840 I         : BTE_InitTraceLevels -- TRC_BNEP
11-08 19:53:03.442  5817  5840 I         : BTE_InitTraceLevels -- TRC_BTM
11-08 19:53:03.443  5817  5840 I         : BTE_InitTraceLevels -- TRC_GAP
,11-08 19:53:03.443  5817  5840 I         : BTE_InitTraceLevels -- TRC_PAN
11-08 19:53:03.443  5817  5840 I         : BTE_InitTraceLevels -- TRC_SDP
11-08 19:53:03.443  5817  5840 I         : BTE_InitTraceLevels -- TRC_GATT
11-08 19:53:03.443  5817  5840 I         : BTE_InitTraceLevels -- TRC_SMP
,11-08 19:53:03.443  5817  5840 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-08 19:53:03.443  5817  5840 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 19:53:03.525  5817  5840 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf41a4549
,11-08 19:53:03.525  5817  5840 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf41a4549 
,11-08 19:53:03.546  5817  5833 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-08 19:53:03.547  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-08 19:53:03.548  5817  5833 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-08 19:53:03.550  5817  5833 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 19:53:03.553  5817  5833 D BluetoothAdapterProperties: Scan Mode:20
,11-08 19:53:03.553  5817  5833 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-08 19:53:03.553  5817  5833 D bt_hci  : do_postload posting postload work item
11-08 19:53:03.553  5817  5837 I bt_hci  : event_postload
,11-08 19:53:03.554  5817  5837 I bt_vendor: sco_config_cb
11-08 19:53:03.554  5817  5837 I bt_hci  : sco_config_callback postload finished.
11-08 19:53:03.556  5817  5833 D bt_bte_conf: Device ID record 1 : primary
11-08 19:53:03.557  5817  5833 D bt_bte_conf:   vendorId            = 000f
11-08 19:53:03.557  5817  5833 D bt_bte_conf:   vendorIdSource      = 0001
11-08 19:53:03.557  5817  5833 D bt_bte_conf:   product             = 1200
11-08 19:53:03.557  5817  5833 D bt_bte_conf:   version             = 1436
11-08 19:53:03.557  5817  5833 D bt_bte_conf:   clientExecutableURL = 
11-08 19:53:03.557  5817  5833 D bt_bte_conf:   serviceDescription  = 
11-08 19:53:03.557  5817  5833 D bt_bte_conf:   documentationURL    = 
11-08 19:53:03.557  5817  5833 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-08 19:53:03.557  5817  5830 D bt_stack_manager: event_start_up_stack finished
11-08 19:53:03.558  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-08 19:53:03.559  5817  5829 D BluetoothAdapterProperties: Setting state to 15
11-08 19:53:03.559  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 19:53:03.560  5817  5829 I BluetoothAdapterState: Entering BleOnState
,11-08 19:53:03.564  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:03.564  5817  5837 I bt_vendor: low_power_mode_cb
11-08 19:53:03.564  5817  5829 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-08 19:53:03.565  5817  5829 D BluetoothAdapterProperties: Setting state to 11
11-08 19:53:03.565  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-08 19:53:03.567  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:03.569  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:03.573  3098  4014 D BluetoothHeadset: Proxy object connected
,11-08 19:53:03.573  5817  5817 D HeadsetService: Received start request. Starting profile...
,11-08 19:53:03.573   926   926 D BluetoothHeadset: Proxy object connected
,11-08 19:53:03.573  3765  3994 D BluetoothHeadset: Proxy object connected
,11-08 19:53:03.575  3098  3098 D HeadsetProfile: Bluetooth service connected
11-08 19:53:03.575  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:03.575  5817  5817 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-08 19:53:03.576  5697  5707 D BluetoothHeadset: Proxy object connected
11-08 19:53:03.576  5817  5817 D HeadsetStateMachine: make
11-08 19:53:03.577   926   926 D BluetoothHeadset: Proxy object connected
11-08 19:53:03.577   926   926 D BluetoothHeadset: Proxy object connected
11-08 19:53:03.581  5697  5697 D HeadsetProfile: Bluetooth service connected
,11-08 19:53:03.587  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:03.589  5817  5817 D HeadsetStateMachine: max_hf_connections = 1
11-08 19:53:03.589  5817  5817 I bt_bluedroid: get_profile_interface handsfree
11-08 19:53:03.589  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-08 19:53:03.590  5817  5833 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-08 19:53:03.590  5817  5829 I BluetoothAdapterState: Entering PendingCommandState
11-08 19:53:03.590  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 19:53:03.592  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:03.593  5817  5817 D A2dpService: Received start request. Starting profile...
11-08 19:53:03.593  5817  5817 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-08 19:53:03.594  5817  5817 I bt_bluedroid: get_profile_interface avrcp
,11-08 19:53:03.599  5817  5817 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-08 19:53:03.599  5817  5817 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-08 19:53:03.599  5817  5817 D A2dpStateMachine: make
11-08 19:53:03.600  5817  5817 I bt_bluedroid: get_profile_interface a2dp
11-08 19:53:03.601  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-08 19:53:03.602  5817  5850 D A2dpStateMachine: Enter Disconnected: -2
,11-08 19:53:03.603  5817  5817 I BluetoothHidServiceJni: classInitNative: succeeds
,11-08 19:53:03.604  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
11-08 19:53:03.605  5817  5817 D HidService: Received start request. Starting profile...
11-08 19:53:03.605  5817  5817 I bt_bluedroid: get_profile_interface hidhost
11-08 19:53:03.605  5817  5833 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf418556d
,11-08 19:53:03.605  5817  5817 D HidService: setHidService(): set to: null
,11-08 19:53:03.605  5817  5833 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-08 19:53:03.607  5817  5817 I BluetoothHealthServiceJni: classInitNative: succeeds
11-08 19:53:03.608  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
11-08 19:53:03.608  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 19:53:03.609  5817  5817 D HealthService: Received start request. Starting profile...
,11-08 19:53:03.611  5817  5817 I bt_bluedroid: get_profile_interface health
11-08 19:53:03.612  5817  5817 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-08 19:53:03.613  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:03.614  5817  5817 D PanService: Received start request. Starting profile...
,11-08 19:53:03.614  5817  5817 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 19:53:03.614  5817  5817 I bt_bluedroid: get_profile_interface pan
11-08 19:53:03.615  5817  5833 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-08 19:53:03.617  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:03.618  5817  5817 D BluetoothMapService: Received start request. Starting profile...
11-08 19:53:03.618  5817  5817 D BluetoothMapService: start()
11-08 19:53:03.620  5817  5817 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-08 19:53:03.621  5817  5817 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-08 19:53:03.621  5817  5817 D BluetoothMapAppObserver: createReceiver()
,11-08 19:53:03.622  5817  5817 D BluetoothMapAppObserver: initObservers()
,11-08 19:53:03.622  5817  5817 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-08 19:53:03.628  5817  5817 V SapService: SapBinder()
11-08 19:53:03.628  5817  5817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:03.628  5817  5817 D SapService: Received start request. Starting profile...
11-08 19:53:03.628  5817  5817 V SapService: start()
,11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:03.630  5817  5847 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:03.630  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isTurningOff()=false
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:03.631  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:03.632  5817  5817 V BluetoothAdapterState: isTurningOff()=false
,11-08 19:53:03.632  5817  5817 V BluetoothAdapterState: isTurningOn()=true
11-08 19:53:03.632  5817  5817 V BluetoothAdapterState: isBleTurningOn()=false
11-08 19:53:03.632  5817  5817 V BluetoothAdapterState: isBleTurningOff()=false
11-08 19:53:03.632  5817  5829 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-08 19:53:03.632  5817  5829 D BluetoothAdapterProperties: ScanMode =  20
11-08 19:53:03.632  5817  5829 D BluetoothAdapterProperties: State =  11
,11-08 19:53:03.634  5817  5833 D BluetoothAdapterProperties: Scan Mode:21
,11-08 19:53:03.635  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 19:53:03.635  5817  5833 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 19:53:03.637  5817  5829 D BluetoothAdapterProperties: Setting state to 12
11-08 19:53:03.637  5817  5829 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-08 19:53:03.637   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 19:53:03.637  5817  5829 I BluetoothAdapterState: Entering OnState
,11-08 19:53:03.638  5697  5708 D BluetoothMap: onBluetoothStateChange: up=true
11-08 19:53:03.638   926   926 D BluetoothA2dp: Proxy object connected
11-08 19:53:03.640  5697  5707 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 19:53:03.640  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:03.640  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:03.640  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:03.640  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:03.640  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:03.640  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:03.640  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:03.640  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:53:03.641   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:03.642  3765  3782 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:03.642  5697  5848 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 19:53:03.642  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:03.644  3098  4014 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 19:53:03.645   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:03.645  3098  3098 D BluetoothInputDevice: Proxy object connected
11-08 19:53:03.645   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:03.645  3098  3098 D HidProfile: Bluetooth service connected
11-08 19:53:03.645  5697  5707 D BluetoothPan: onBluetoothStateChange on: true
11-08 19:53:03.646  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:03.646  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:03.646  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:03.646  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:03.646  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:03.646  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:03.646  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:03.646  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 19:53:03.647  5817  5817 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 19:53:03.647  5697  5708 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 19:53:03.647  5817  5817 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-08 19:53:03.648  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:03.649  5697  5697 D BluetoothMap: Proxy object connected
11-08 19:53:03.649  5697  5697 D MapProfile: Bluetooth service connected
11-08 19:53:03.649  5697  5697 D BluetoothMap: getConnectedDevices()
,11-08 19:53:03.649  3098  3112 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 19:53:03.649  5817  5817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 19:53:03.651  3098  3110 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:03.651  3098  3098 D BluetoothA2dp: Proxy object connected
11-08 19:53:03.651  3098  3112 D BluetoothPan: onBluetoothStateChange on: true
11-08 19:53:03.651  5817  5817 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 19:53:03.652  5697  5697 D BluetoothInputDevice: Proxy object connected
11-08 19:53:03.652  5697  5697 D HidProfile: Bluetooth service connected
11-08 19:53:03.652  5817  5817 D ObexServerSockets: Succeed to create listening sockets 
,11-08 19:53:03.652  5817  5817 D ObexServerSockets0: startAccept()
11-08 19:53:03.652  3098  4014 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 19:53:03.653  5817  5817 D ObexServerSockets0: prepareForNewConnect()
11-08 19:53:03.654  3098  3110 D BluetoothMap: onBluetoothStateChange: up=true
11-08 19:53:03.654  5697  5697 D BluetoothA2dp: Proxy object connected
11-08 19:53:03.655  5817  5817 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-08 19:53:03.655  5817  5817 D BluetoothSdpJni: SDP Create record success - handle: 0
11-08 19:53:03.655  3098  3098 D BluetoothMap: Proxy object connected
11-08 19:53:03.656  3098  3098 D MapProfile: Bluetooth service connected
11-08 19:53:03.656  3098  3098 D BluetoothMap: getConnectedDevices()
11-08 19:53:03.656  5697  5707 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 19:53:03.657  5817  5856 D ObexServerSockets0: Accepting socket connection...
11-08 19:53:03.657  5817  5857 D ObexServerSockets0: Accepting socket connection...
11-08 19:53:03.657   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
,11-08 19:53:03.657   926   926 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-08 19:53:03.660  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 19:53:03.660  5817  5817 D BluetoothMapService: onReceive
11-08 19:53:03.660  5817  5817 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 19:53:03.660  5817  5817 D BluetoothMapService: STATE_ON
11-08 19:53:03.661  3098  3098 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 19:53:03.661  3098  3098 D PanProfile: Bluetooth service connected
11-08 19:53:03.663  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:03.664  5817  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 19:53:03.665  5697  5697 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 19:53:03.665  5817  5859 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 19:53:03.665  5817  5859 D BluetoothSdpJni: SDP Create record success - handle: 1
11-08 19:53:03.666  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:03.667  5697  5697 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 19:53:03.667  5697  5697 D PanProfile: Bluetooth service connected
,11-08 19:53:03.671  3572  3572 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 19:53:03.671  5697  5697 D DockEventReceiver: finishStartingService: stopping service
,11-08 19:53:03.682  5697  5697 D BluetoothPbap: Proxy object connected
,11-08 19:53:03.682  5697  5697 D PbapServerProfile: Bluetooth service connected
,11-08 19:53:03.686  5817  5817 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-08 19:53:03.686  5817  5817 D ObexServerSockets0: prepareForNewConnect()
11-08 19:53:03.686  5817  5863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 19:53:03.699  3098  3098 D BluetoothPbap: Proxy object connected
,11-08 19:53:03.700  3098  3098 D PbapServerProfile: Bluetooth service connected
,11-08 19:53:03.703  5817  5867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 19:53:03.705  5817  5867 I BtOppRfcommListener: Accept thread started.
,11-08 19:53:04.100  5585  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:04.100  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:04.100  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:04.100  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:04.100  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:04.100  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:04.100  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:04.100  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 19:53:04.105  5585  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:53:04.108  5585  5632 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-08 19:53:04.111   926   937 D WifiService: setWifiEnabled: false pid=5585, uid=10077
,11-08 19:53:04.112   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 19:53:04.116  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:04.137   926  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-08 19:53:04.143   926  2931 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-08 19:53:04.143   926  2931 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-08 19:53:04.144   926  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 19:53:04.144   926  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 19:53:04.167   926  5757 D DhcpClient: Clearing IP address
,11-08 19:53:04.168   507   919 D CommandListener: Clearing all IP addresses on wlan0
,11-08 19:53:04.173   507   919 D CommandListener: Setting iface cfg
,11-08 19:53:04.184  3572  5789 V NativeCrypto: Read error: ssl=0x7f91670180: I/O error during system call, Connection timed out
,11-08 19:53:04.188  3572  5789 V NativeCrypto: SSL shutdown failed: ssl=0x7f91670180: I/O error during system call, Broken pipe
,11-08 19:53:04.193   926   936 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-08 19:53:04.195   926  5758 D DhcpClient: Receive thread stopped
11-08 19:53:04.195   926  5743 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-08 19:53:04.198   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-08 19:53:04.198   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-08 19:53:04.201   926  5743 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-08 19:53:04.206   535   535 E Parcel  : Reading a NULL string not supported here.
,11-08 19:53:04.209   926  2946 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-08 19:53:04.211   926   926 D RttService: SCAN_AVAILABLE : 1
11-08 19:53:04.211   926  3051 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-08 19:53:04.213  3743  3842 W QCNEJ   : |CORE| network lost: 101
,11-08 19:53:04.214  3743  3842 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-08 19:53:04.225   926  2931 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-08 19:53:04.234   926  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 19:53:04.240   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 19:53:04.261   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 19:53:04.262   926  2946 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-08 19:53:04.262   926  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-08 19:53:04.262   507   919 D CommandListener: Clearing all IP addresses on wlan0
,11-08 19:53:04.264   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-08 19:53:04.269  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:04.269  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:04.269  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:04.269  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:04.269  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:04.269  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:53:04.269  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:53:04.269  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:53:04.271  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 19:53:04.274  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:04.274  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:04.274  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:04.274  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:04.274  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:04.274  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:53:04.274  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:53:04.274  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 19:53:04.275  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:53:04.277  3945  3945 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-08 19:53:04.279  3958  3958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-08 19:53:04.282  3958  3958 D SystemUpdateService: onCreate
,11-08 19:53:04.285  3958  3958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 19:53:04.288  3958  5878 I SystemUpdateService: active receiver: enabled
,11-08 19:53:04.293  3958  3958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-08 19:53:04.297  3958  4212 I iu.UploadsManager: num queued entries: 0
,11-08 19:53:04.298  3958  4212 I iu.UploadsManager: num updated entries: 0
11-08 19:53:04.298  3958  4212 I iu.SyncManager: NEXT; no task
,11-08 19:53:04.300  3958  5878 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 19:53:04.302  3958  3958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-08 19:53:04.303  3958  3958 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 19:53:04.305  5385  5385 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 19:53:04.309  5385  5385 D SprintDMHelper: simOperator: 
11-08 19:53:04.309  5385  5385 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 19:53:04.315   507   919 E Netd    : netlink response contains error (No such file or directory)
11-08 19:53:04.316   926  2946 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-08 19:53:04.316   926  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-08 19:53:04.317   926  2931 D DhcpClient: doQuit
,11-08 19:53:04.317   926  2931 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-08 19:53:04.317   926  5757 D DhcpClient: onQuitting
11-08 19:53:04.317  3958  5878 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-08 19:53:04.317  3958  5878 I SystemUpdateService: now status is 0 (complete)
,11-08 19:53:04.317  3958  5878 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 19:53:04.317  3958  5878 I SystemUpdateService: file has been verified
11-08 19:53:04.317  3958  5878 I SystemUpdateService: OTA package size = 21989297
11-08 19:53:04.317  5693  5693 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-08 19:53:04.325  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:04.325  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:04.325  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:04.325  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 19:53:04.325  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:04.325  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:53:04.325  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:53:04.325  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:53:04.327  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:53:04.330  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:04.330  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:04.330  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:04.330  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 19:53:04.330  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:04.330  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:53:04.330  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:53:04.330  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 19:53:04.330  3958  5878 I SystemUpdateService: showing system update notification
,11-08 19:53:04.332  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:53:04.336  5693  5693 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-08 19:53:04.340  5693  5693 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-08 19:53:04.347   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 19:53:04.354  3958  3958 D SystemUpdateService: onDestroy
,11-08 19:53:04.368  5693  5693 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-08 19:53:04.374  5693  5693 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-08 19:53:04.477   926  2931 D wifi    : In wifi stop Hal
11-08 19:53:04.477  4493  4493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 19:53:04.477   926  2931 D wifi    : halHandle = 0x7f8f3d8400, mVM = 0x7faba0d140, mCls = 0x20179a
11-08 19:53:04.478   926  5692 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-08 19:53:04.478   926  5692 D WifiHAL : Got a signal to exit!!!
,11-08 19:53:04.478   926  5692 I WifiHAL : Exit wifi_event_loop
11-08 19:53:04.481   926  2931 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-08 19:53:04.482   926  2931 E WifiHAL : Event processing terminated
,11-08 19:53:04.483   926  2931 D wifi    : In wifi cleaned up handler
11-08 19:53:04.483   926  2931 I WifiHAL : Internal cleanup completed
11-08 19:53:04.489  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:04.493  3728  4156 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 19:53:04.495  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:04.514   926  5692 D wifi    : set interface wlan0 flags (DOWN)
11-08 19:53:04.515   926  2931 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 19:53:04.619   541   541 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-08 19:53:04.619   541   541 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-08 19:53:04.624  5585  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:04.624  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:04.624  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:04.624  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 19:53:04.624  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:04.624  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:53:04.624  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:53:04.624  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:53:04.627  5585  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:53:04.629   926  3793 D WifiService: setWifiEnabled: true pid=5585, uid=10077
11-08 19:53:04.629   926  3793 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 19:53:04.631  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:04.722   926   943 D Tethering: InitialState.processMessage what=4
11-08 19:53:04.722   507   919 D SoftapController: Softap fwReload - Ok
,11-08 19:53:04.727   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-08 19:53:04.727   507   919 D CommandListener: Setting iface cfg
11-08 19:53:04.727   507   919 D CommandListener: Trying to bring down wlan0
,11-08 19:53:04.728   507   919 D CommandListener: Clearing all IP addresses on wlan0
,11-08 19:53:04.732   926  2931 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 19:53:05.132   926  3134 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,11-08 19:53:05.132   926  3134 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 19:53:05.324   926  2931 D wifi    : set interface wlan0 flags (UP)
,11-08 19:53:05.325   926  2931 I WifiHAL : Initializing wifi
,11-08 19:53:05.325   926  2931 I WifiHAL : Creating socket
11-08 19:53:05.330   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-08 19:53:05.335   926  2931 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-08 19:53:05.335   926  2931 D wifi    : Did set static halHandle = 0x7f8f3d8400
,11-08 19:53:05.335   926  2931 D wifi    : halHandle = 0x7f8f3d8400, mVM = 0x7faba0d140, mCls = 0x101936
11-08 19:53:05.335   926  2931 D wifi    : array field set
11-08 19:53:05.336   926  2931 I WifiNative-HAL: interface[0] = wlan0
,11-08 19:53:05.338   926  5888 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547864019968
11-08 19:53:05.339   926  5888 D wifi    : waitForHalEvents called, vm = 0x7faba0d140, obj = 0x101936, env = 0x7f91473100
11-08 19:53:05.343   926  2931 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-08 19:53:05.344   926  2931 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
11-08 19:53:05.348  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:05.350  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:05.396  5889  5889 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 19:53:05.465  5889  5889 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 19:53:05.519  5889  5889 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 19:53:05.519  5889  5889 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 19:53:05.634   926   937 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,11-08 19:53:05.635   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 19:53:06.138   926  3793 D WifiService: setWifiEnabled: true pid=5585, uid=10077
,11-08 19:53:06.138   926  3793 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 19:53:06.361   926  2931 D WifiConfigStore: Loading config and enabling all networks 
,11-08 19:53:06.369  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:06.369  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:06.369  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:06.369  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:06.369  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:06.369  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:53:06.369  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:53:06.369  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:53:06.374  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:53:06.382  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:06.382  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:06.382  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:06.382  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:06.382  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:06.382  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:53:06.382  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:53:06.382  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:53:06.386  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:53:06.407   926  2931 D WifiConfigStore: loaded 0 passpoint configs
,11-08 19:53:06.408   926  2931 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-08 19:53:06.409   926  2931 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-08 19:53:06.410   926  2931 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-08 19:53:06.410   926  2931 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-08 19:53:06.411   926  2931 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-08 19:53:06.412   926  2931 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-08 19:53:06.412   926  2931 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-08 19:53:06.412   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-08 19:53:06.412   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-08 19:53:06.412   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 19:53:06.412   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
,11-08 19:53:06.412   926  2931 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-08 19:53:06.416   926  2931 D WifiNative-HAL: Setting external_sim to 1
,11-08 19:53:06.416  4493  4493 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 19:53:06.417   926  2931 D wifi    : setting dfs flag to true, 0x7f90dbe220
,11-08 19:53:06.417   926  2931 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 19:53:06.418   926  2931 D wifi    : setting scan oui 0x7f90dbe220
11-08 19:53:06.418   926  2931 D WifiHAL : Sending mac address OUI
,11-08 19:53:06.422   926  2931 E native  : do suspend false
,11-08 19:53:06.430   926  2931 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-08 19:53:06.430   507   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-08 19:53:06.431   926   926 D RttService: SCAN_AVAILABLE : 3
,11-08 19:53:06.431   926  3051 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-08 19:53:06.432   507   919 D CommandListener: Setting iface cfg
,11-08 19:53:06.436   926  2927 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
,11-08 19:53:06.436   926  2927 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-08 19:53:06.445   926  2927 D WifiNative-HAL: p2pGetDeviceAddress
,11-08 19:53:06.450   926  2927 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
11-08 19:53:06.451   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=114344 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-08 19:53:06.650  5585  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:06.650  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:06.650  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:06.650  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:06.650  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:06.650  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:53:06.650  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:53:06.650  5585  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:53:06.655  5585  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:53:06.658  5585  5632 D BluetoothAdapter: enable(): BT is already enabled..!
,11-08 19:53:06.658   926   937 D WifiService: setWifiEnabled: true pid=5585, uid=10077
11-08 19:53:06.659   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 19:53:06.660  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 19:53:06.661  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 19:53:06.661  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 19:53:06.661  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-08 19:53:06.661  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-08 19:53:06.661  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4a1190 removed from the list
,11-08 19:53:06.661  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-08 19:53:06.661  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c438a89 removed from the list
,11-08 19:53:06.662  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
11-08 19:53:06.662  5585  5632 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 19:53:06.662  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-08 19:53:06.673  5585  5632 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-08 19:53:06.676  5585  5632 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-08 19:53:06.678  5585  5632 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-08 19:53:06.682  5585  5632 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-08 19:53:06.685  5585  5632 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-08 19:53:06.686  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-08 19:53:06.687  5585  5632 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-08 19:53:06.687  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-08 19:53:06.689  5585  5632 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-08 19:53:06.693  5585  5632 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-08 19:53:06.694  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9345e67 Bundle[{}]
11-08 19:53:06.694  5585  5632 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-08 19:53:06.695  5585  5632 I io.jxcore.node.LifeCycleMonitor: start: OK
11-08 19:53:06.695  5585  5632 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-08 19:53:06.696  5585  5632 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-08 19:53:06.696  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-08 19:53:06.697  5585  5632 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-08 19:53:06.697  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-08 19:53:06.698  5585  5632 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-08 19:53:06.699  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-08 19:53:06.701  5585  5632 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-08 19:53:06.702  5585  5632 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-08 19:53:06.705  5585  5632 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-08 19:53:06.708  5585  5632 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-08 19:53:06.709  5585  5632 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-08 19:53:06.709  5585  5632 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-08 19:53:06.710  5585  5632 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-08 19:53:06.712  5585  5632 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-08 19:53:06.714  5585  5632 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-08 19:53:06.715  5585  5632 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
11-08 19:53:06.717  5585  5632 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-08 19:53:06.719  5585  5632 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-08 19:53:06.721  5585  5632 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-08 19:53:06.722  5585  5632 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-08 19:53:06.722  5585  5632 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
,11-08 19:53:06.723  5585  5632 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-08 19:53:06.724  5585  5632 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-08 19:53:06.724  5585  5632 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,11-08 19:53:06.725  5585  5632 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-08 19:53:06.726  5585  5632 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-08 19:53:06.727  5585  5632 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-08 19:53:06.728  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-08 19:53:06.728  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166b6bc added. We now have 3 listener(s)
11-08 19:53:06.729  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 19:53:06.729  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 19:53:06.729  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 19:53:06.730  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 19:53:06.730  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d14645 added. We now have 3 listener(s)
11-08 19:53:06.730  5585  5632 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 19:53:06.731  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 19:53:06.733  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 19:53:06.737  5585  5632 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 19:53:06.737  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:06.737  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:06.737  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:06.737  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:06.737  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 19:53:06.737  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 19:53:06.737  5585  5632 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 19:53:06.739  5585  5632 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 19:53:06.740  5585  5632 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 19:53:06.742  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 19:53:06.745  5585  5632 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-08 19:53:06.745  5585  5632 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-08 19:53:06.746  5585  5632 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-08 19:53:06.746  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-08 19:53:06.746  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 19:53:06.746  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-08 19:53:06.746  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 19:53:06.746  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:53:06.747  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 19:53:06.748  5585  5891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 19:53:06.748  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 19:53:06.748  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 19:53:06.748  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-08 19:53:06.748  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 19:53:06.748  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 19:53:06.748  5585  5891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 19:53:06.748  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 19:53:06.748  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 19:53:06.748  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:53:06.749  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 19:53:06.750  5585  5891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 19:53:06.748  5858  5858 W Binder_6: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34867]" dev="sockfs" ino=34867 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:06.748  5858  5858 W Binder_6: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34867]" dev="sockfs" ino=34867 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:06.754  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 19:53:06.754  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 19:53:06.754  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-08 19:53:06.757  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 19:53:06.758  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 19:53:06.758  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 19:53:06.760  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:06.760  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 19:53:06.760  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 19:53:06.760  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-08 19:53:06.760  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 19:53:06.760  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.760  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.760  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.761  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.761  5585  5632 D BluetoothAdapter: STATE_ON
,11-08 19:53:06.764  5817  5858 D BtGatt.GattService: registerClient() - UUID=c182b465-4473-4fdb-b5f0-4b4a8d74f0bc
,11-08 19:53:06.765  5817  5833 D BtGatt.GattService: onClientRegistered() - UUID=c182b465-4473-4fdb-b5f0-4b4a8d74f0bc, clientIf=5
,11-08 19:53:06.766  5585  5596 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 19:53:06.767  5817  5835 D BtGatt.AdvertiseManager: message : 0
,11-08 19:53:06.769  5817  5835 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 19:53:06.778  5817  5833 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 19:53:06.783  5817  5833 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 19:53:06.784  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.784  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:06.784  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 19:53:06.784  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.784  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.784  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.784  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.785  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.785  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 19:53:06.786  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-08 19:53:06.786  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.787  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.787  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.787  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:06.787  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 19:53:06.787  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 19:53:06.787  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-08 19:53:06.787  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 19:53:06.787  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 19:53:06.787  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 19:53:06.787  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 19:53:06.787  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 19:53:06.787  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 19:53:06.788  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 19:53:06.788  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 19:53:06.788  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-08 19:53:06.788  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 19:53:06.791  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-08 19:53:06.791  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 19:53:06.791  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 19:53:06.791  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 19:53:06.791  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 19:53:06.791  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 19:53:06.791  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 19:53:07.292  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 19:53:07.293  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-08 19:53:07.293  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 19:53:09.292   926  2946 D ConnectivityService: handlePromptUnvalidated 101
,11-08 19:53:09.509  5889  5889 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 19:53:09.513  5889  5889 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 19:53:09.520  5889  5889 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 19:53:09.525  5889  5889 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 19:53:09.567   926  2931 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-08 19:53:09.569   926  2931 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-08 19:53:09.569   926  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 19:53:09.581   926  2931 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-08 19:53:09.618   926  2931 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-08 19:53:09.620   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:09.624  5889  5889 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-08 19:53:10.048  5889  5889 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-08 19:53:10.083  5889  5889 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-08 19:53:10.084  5889  5889 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-08 19:53:10.093   926  2931 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 19:53:10.094   926  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-08 19:53:10.094   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-08 19:53:10.111   926  2931 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 19:53:10.129   507   919 D CommandListener: Setting iface cfg
,11-08 19:53:10.135   926  2931 D WifiStateMachine: Start Dhcp Watchdog 3
,11-08 19:53:10.141   926  5896 D DhcpClient: Receive thread started
,11-08 19:53:10.147   926  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-08 19:53:10.147   926  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-08 19:53:10.147   926  2946 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-08 19:53:10.227   926  2931 E native  : do suspend false
,11-08 19:53:10.240   926  5895 D DhcpClient: Broadcasting DHCPDISCOVER
,11-08 19:53:10.252   926  5896 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172791, domain null
,11-08 19:53:10.252   926  5895 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172791 seconds
,11-08 19:53:10.254   926  5895 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-08 19:53:10.270   926  5896 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-08 19:53:10.270   926  5895 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-08 19:53:10.273   507   919 D CommandListener: Setting iface cfg
,11-08 19:53:10.277   926  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-08 19:53:10.282   926  5895 D DhcpClient: Scheduling renewal in 86399s
,11-08 19:53:10.289  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-08 19:53:10.289  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 19:53:10.289  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-08 19:53:10.290  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 19:53:10.290  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 19:53:10.290  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 19:53:10.290  5585  5891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 19:53:10.290  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 19:53:10.290  5585  5891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 19:53:10.291  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 19:53:10.291  5585  5891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 19:53:10.291  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 19:53:10.291  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 19:53:10.291  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-08 19:53:10.291  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 19:53:10.292  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 19:53:10.292  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.292  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.294  5585  5632 D BluetoothAdapter: STATE_ON
11-08 19:53:10.294  5585  5632 D BluetoothLeScanner: could not find callback wrapper
,11-08 19:53:10.294  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 19:53:10.295  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.295  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:10.295  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-08 19:53:10.295  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.297  5817  5835 D BtGatt.AdvertiseManager: message : 1
11-08 19:53:10.297   926  2931 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-08 19:53:10.298   926  2931 D WifiConfigStore: No blacklist allowed without epno enabled
11-08 19:53:10.298  5817  5835 D BtGatt.AdvertiseManager: stop advertise for client 5
11-08 19:53:10.300   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-08 19:53:10.303   926  2946 D ConnectivityService: Adding iface wlan0 to network 102
,11-08 19:53:10.309   926  2931 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-08 19:53:10.316  5817  5833 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 19:53:10.316  5817  5833 D BtGatt.GattService: Client app is not null!
11-08 19:53:10.318  5817  5858 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 19:53:10.319  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 19:53:10.319  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.320  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 19:53:10.320  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.320  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.320  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.320  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 19:53:10.320  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 19:53:10.320  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.320  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.321  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 19:53:10.321  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.323  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.323  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:53:10.323  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.323  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.323  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.323  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.324  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 19:53:10.324  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 19:53:10.325  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 19:53:10.325  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.327  5585  5632 D org.thaliproject.p2p.b,tconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.327  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.327  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.328  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 19:53:10.328  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 19:53:10.328  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 19:53:10.328  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 19:53:10.328  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:53:10.328  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:53:10.329  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 19:53:10.330  5585  5632 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-08 19:53:10.330  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 19:53:10.331  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 19:53:10.331  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-08 19:53:10.331  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-08 19:53:10.331  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:53:10.331  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-08 19:53:10.335  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 19:53:10.335  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-08 19:53:10.335  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 19:53:10.339  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 19:53:10.340  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 19:53:10.340  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 19:53:10.345  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.345  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-08 19:53:10.345  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 19:53:10.345  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-08 19:53:10.346  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 19:53:10.346  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:10.347  5585  5632 D BluetoothAdapter: STATE_ON
,11-08 19:53:10.350  5817  5858 D BtGatt.GattService: registerClient() - UUID=2729dd7a-f0e5-419a-ab22-b99862625d0a
,11-08 19:53:10.350   926  2946 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-08 19:53:10.350   926  2946 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-08 19:53:10.351  5817  5833 D BtGatt.GattService: onClientRegistered() - UUID=2729dd7a-f0e5-419a-ab22-b99862625d0a, clientIf=5
11-08 19:53:10.352  5585  5899 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-08 19:53:10.352  5817  5846 D BtGatt.GattService: start scan with filters
11-08 19:53:10.353   926  2946 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-08 19:53:10.354   926  2946 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
11-08 19:53:10.357  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-08 19:53:10.357  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.357  5817  5836 D BtGatt.ScanManager: handling starting scan
11-08 19:53:10.357  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-08 19:53:10.358   926  2946 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
11-08 19:53:10.358  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.358  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.358  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-08 19:53:10.358  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 19:53:10.358  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.358  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.358  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-08 19:53:10.358  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:10.360  5817  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@9827968
,11-08 19:53:10.365  5817  5833 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-08 19:53:10.365  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 19:53:10.366  5817  5836 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-08 19:53:10.366  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.366  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-08 19:53:10.366  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:10.366  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.366  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-08 19:53:10.367  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.367  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 19:53:10.367   926  2946 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-08 19:53:10.369  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-08 19:53:10.369  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:10.373   926  2946 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-08 19:53:10.373   926  2946 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-08 19:53:10.373   926  2946 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-08 19:53:10.373   926  2946 D ConnectivityService:    accepting network in place of null
11-08 19:53:10.373   926  2931 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-08 19:53:10.373   926  2931 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 19:53:10.374   926  2946 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-08 19:53:10.375  5817  5833 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-08 19:53:10.375  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 19:53:10.376  5817  5836 D BtGatt.ScanManager: Starting BLE batch scan
11-08 19:53:10.376  5817  5836 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-08 19:53:10.377  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.377  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:10.377  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:10.385  5817  5833 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-08 19:53:10.386  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 19:53:10.390   926  5894 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118283, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-08 19:53:10.390  5817  5833 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-08 19:53:10.390  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 19:53:10.396   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 19:53:10.414   507   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 19:53:10.418   926  2946 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-08 19:53:10.419   926  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-08 19:53:10.419  3743  3842 W QCNEJ   : |CORE| network available: 102
,11-08 19:53:10.419   926  2946 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-08 19:53:10.421   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-08 19:53:10.428  3743  3842 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-08 19:53:10.429  3743  3842 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-08 19:53:10.429  3743  3842 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-08 19:53:10.429  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:10.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:10.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:10.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:10.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:10.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:10.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:10.429  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:53:10.431  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:53:10.434  3945  3945 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-08 19:53:10.436  3958  3958 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-08 19:53:10.437  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:10.437  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:10.437  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:10.437  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:10.437  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:10.437  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:10.437  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:10.437  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 19:53:10.439  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:10.439  3958  3958 D SystemUpdateService: onCreate
,11-08 19:53:10.443  3958  3958 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-08 19:53:10.443  5585  5585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 19:53:10.443  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 19:53:10.443  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 19:53:10.443  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 19:53:10.443  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 19:53:10.443  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 19:53:10.443  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 19:53:10.443  5585  5585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 19:53:10.445  5585  5585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 19:53:10.454  3958  3958 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-08 19:53:10.459  3958  5909 I SystemUpdateService: active receiver: enabled
,11-08 19:53:10.461  3958  4212 I iu.UploadsManager: num queued entries: 0
,11-08 19:53:10.461  3958  4212 I iu.UploadsManager: num updated entries: 0
11-08 19:53:10.461  3958  4212 I iu.SyncManager: NEXT; no task
,11-08 19:53:10.465  3958  3958 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 19:53:10.467  3958  3958 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 19:53:10.468  5385  5385 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 19:53:10.472  5385  5385 D SprintDMHelper: simOperator: 
11-08 19:53:10.472  5385  5385 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 19:53:10.482  3958  5909 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 19:53:10.493   926  5893 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-08 19:53:10.503  3958  5909 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-08 19:53:10.504  3958  5909 I SystemUpdateService: now status is 0 (complete)
11-08 19:53:10.504  3958  5909 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-08 19:53:10.504  3958  5909 I SystemUpdateService: file has been verified
11-08 19:53:10.504  3958  5909 I SystemUpdateService: OTA package size = 21989297
,11-08 19:53:10.510  3958  5909 I SystemUpdateService: showing system update notification
,11-08 19:53:10.518   926   926 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 19:53:10.519  3958  3958 D SystemUpdateService: onDestroy
,11-08 19:53:10.545   926  5893 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 08 Nov 2016 18:53:10 GMT], X-Android-Received-Millis=[1478631190544], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478631190523]}
,11-08 19:53:10.545   926  2946 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-08 19:53:10.546   926  2946 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-08 19:53:10.546   926  2946 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-08 19:53:10.547   926  2946 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-08 19:53:10.620   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:10.867  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-08 19:53:10.867  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 19:53:10.867  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 19:53:10.894  5817  5817 D BtGatt.ScanManager: awakened up at time 118787
,11-08 19:53:10.897  5817  5836 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 19:53:10.923  5817  5833 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-08 19:53:10.923  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 19:53:10.924  5817  5833 D BtGatt.GattService: current time is 118817590526
,11-08 19:53:10.924  5817  5833 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -88, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
11-08 19:53:10.927  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
11-08 19:53:10.929  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-08 19:53:10.934  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,11-08 19:53:10.934  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 19:53:10.935  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-88, mTimestampNanos=118518483703}
11-08 19:53:10.935  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 19:53:10.936  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-79, mTimestampNanos=118618483703}
,11-08 19:53:11.419   926  2946 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,11-08 19:53:11.621   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:12.386   926  2931 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 11 -> obsolete
,11-08 19:53:12.502   926  2931 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 11 -> obsolete
,11-08 19:53:12.622   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:13.380  5585  5632 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-08 19:53:13.405  5585  5632 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,11-08 19:53:13.405  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 19:53:13.406  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-08 19:53:13.407  5585  5632 D BluetoothAdapter: STATE_ON
11-08 19:53:13.408  5817  5846 D BtGatt.GattService: stopScan() - queue size =1
11-08 19:53:13.408  5817  5827 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 19:53:13.409  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 19:53:13.409  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.409  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-08 19:53:13.409  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 19:53:13.410  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.410  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-08 19:53:13.410  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 19:53:13.410  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-08 19:53:13.410  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 19:53:13.410  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.411  5585  5632 D BluetoothAdapter: STATE_ON
,11-08 19:53:13.415  5817  5858 D BtGatt.GattService: registerClient() - UUID=d10b227d-b74f-4bd4-a8c9-8f3bd95354f8
11-08 19:53:13.415  5817  5833 D BtGatt.GattService: onClientRegistered() - UUID=d10b227d-b74f-4bd4-a8c9-8f3bd95354f8, clientIf=5
,11-08 19:53:13.415  5817  5817 D BtGatt.ScanManager: awakened up at time 121309
,11-08 19:53:13.416  5585  5596 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-08 19:53:13.417  5817  5827 D BtGatt.GattService: start scan with filters
11-08 19:53:13.420  5817  5833 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-08 19:53:13.420  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 19:53:13.420  5817  5836 D BtGatt.ScanManager: stopping BLe Batch
11-08 19:53:13.421  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-08 19:53:13.421  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:13.421  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-08 19:53:13.421  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.421  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.421  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-08 19:53:13.421  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-08 19:53:13.422  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.422  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.422  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 19:53:13.422  5585  5632 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-08 19:53:13.423  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-08 19:53:13.423  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 19:53:13.424  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 19:53:13.424  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 19:53:13.425  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 19:53:13.425  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 19:53:13.425  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-08 19:53:13.425  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 19:53:13.425  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-08 19:53:13.425  5585  5917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 19:53:13.425  5585  5917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 19:53:13.426  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 19:53:13.426  5585  5632 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 19:53:13.424  5844  5844 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32272]" dev="sockfs" ino=32272 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 19:53:13.424  5844  5844 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32272]" dev="sockfs" ino=32272 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 19:53:13.428  5817  5833 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-08 19:53:13.428  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 19:53:13.428  5817  5836 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-08 19:53:13.429  5585  5917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-08 19:53:13.435  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.435  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.435  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 19:53:13.435  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 19:53:13.435  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
,11-08 19:53:13.435  5585  5632 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 19:53:13.435  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.436  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.436  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.436  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:13.437  5585  5632 D BluetoothAdapter: STATE_ON
,11-08 19:53:13.439  5817  5833 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-08 19:53:13.439  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 19:53:13.439  5817  5833 D BtGatt.GattService: current time is 121333486931
11-08 19:53:13.440  5817  5833 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -89, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -86, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -87, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
11-08 19:53:13.440  5817  5858 D BtGatt.GattService: registerClient() - UUID=f75f9c31-11af-42cf-9e72-d2d5058b4b6a
11-08 19:53:13.440  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-08 19:53:13.440  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-08 19:53:13.440  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
11-08 19:53:13.441  5817  5833 D BtGatt.GattService: onClientRegistered() - UUID=f75f9c31-11af-42cf-9e72-d2d5058b4b6a, clientIf=6
,11-08 19:53:13.441  5585  5899 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-08 19:53:13.441  5817  5836 D BtGatt.ScanManager: handling starting scan
11-08 19:53:13.442  5817  5835 D BtGatt.AdvertiseManager: message : 0
,11-08 19:53:13.445  5817  5835 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 19:53:13.448  5817  5833 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-08 19:53:13.448  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 19:53:13.448  5817  5836 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-08 19:53:13.457  5817  5833 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-08 19:53:13.461  5817  5833 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-08 19:53:13.462  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 19:53:13.462  5817  5836 D BtGatt.ScanManager: Starting BLE batch scan
11-08 19:53:13.462  5817  5836 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-08 19:53:13.466  5817  5833 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-08 19:53:13.468  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:13.468  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.468  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 19:53:13.468  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.468  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.468  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.468  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.468  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.468  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.468  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.469  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.469  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-08 19:53:13.469  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-08 19:53:13.469  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 19:53:13.470  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 19:53:13.470  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:13.473  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.473  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.473  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:13.473  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-08 19:53:13.473  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 19:53:13.474  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 19:53:13.474  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 19:53:13.474  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 19:53:13.474  5585  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 19:53:13.474  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 19:53:13.474  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-08 19:53:13.474  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-08 19:53:13.474  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 19:53:13.475  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 19:53:13.475  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-08 19:53:13.475  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 19:53:13.477  5817  5833 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-08 19:53:13.477  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 19:53:13.478  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 19:53:13.478  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-08 19:53:13.478  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 19:53:13.478  5585  5585 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 19:53:13.478  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-08 19:53:13.478  5585  5585 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 19:53:13.478  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-08 19:53:13.484  5817  5833 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-08 19:53:13.484  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 19:53:13.623   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:13.980  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-08 19:53:13.980  5585  5585 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-08 19:53:13.980  5585  5585 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 19:53:14.623   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-08 19:53:16.478  5585  5632 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-08 19:53:16.479  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 19:53:16.479  5585  5632 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 19:53:16.479  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 19:53:16.480  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-08 19:53:16.480  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 19:53:16.480  5585  5917 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-08 19:53:16.480  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 19:53:16.480  5585  5917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 19:53:16.481  5585  5632 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 19:53:16.481  5585  5917 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-08 19:53:16.481  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-08 19:53:16.481  5585  5585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-08 19:53:16.481  5585  5632 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166b6bc removed from the list
11-08 19:53:16.481  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 19:53:16.481  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-08 19:53:16.481  5585  5585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 19:53:16.481  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 19:53:16.482  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 19:53:16.482  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-08 19:53:16.482  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.482  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:16.483  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-08 19:53:16.485  5585  5632 D BluetoothAdapter: STATE_ON
11-08 19:53:16.487  5817  5858 D BtGatt.GattService: stopScan() - queue size =1
11-08 19:53:16.488  5817  5828 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 19:53:16.489  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-08 19:53:16.489  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.489  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-08 19:53:16.490  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.490  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.490  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 19:53:16.490  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-08 19:53:16.490  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.491  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.491  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-08 19:53:16.491  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.495  5817  5817 D BtGatt.ScanManager: awakened up at time 124389
,11-08 19:53:16.497  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.498  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 19:53:16.498  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.498  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.498  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.498  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:16.498  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 19:53:16.498  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:16.499  5817  5835 D BtGatt.AdvertiseManager: message : 1
11-08 19:53:16.500  5817  5835 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-08 19:53:16.502  5817  5833 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-08 19:53:16.502  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 19:53:16.502  5817  5836 D BtGatt.ScanManager: stopping BLe Batch
,11-08 19:53:16.508  5817  5833 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-08 19:53:16.508  5817  5833 D BtGatt.GattService: Client app is not null!
,11-08 19:53:16.509  5817  5844 D BtGatt.GattService: unregisterClient() - clientIf=6
11-08 19:53:16.510  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 19:53:16.510  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:16.510  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 19:53:16.510  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.510  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.510  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.510  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 19:53:16.510  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 19:53:16.511  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.511  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.511  5585  5632 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 19:53:16.511  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:16.512  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-08 19:53:16.513  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:53:16.513  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.513  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.513  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.513  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.513  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.513  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-08 19:53:16.513  5585  5632 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 19:53:16.514  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 19:53:16.514  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.515  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.515  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.515  5585  5632 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-08 19:53:16.515  5585  5632 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d14645 removed from the list
11-08 19:53:16.516  5585  5632 D io.jxcore.node.ConnectivityMonitor: stop
,11-08 19:53:16.516  5585  5632 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 19:53:16.516  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:53:16.516  5585  5585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 19:53:16.517  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 19:53:16.517  5585  5585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 19:53:16.518  5585  5632 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-08 19:53:16.518  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-08 19:53:16.518  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-08 19:53:16.519  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 19:53:16.519  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 19:53:16.519  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-08 19:53:16.519  5585  5632 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-08 19:53:16.520  5585  5632 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-08 19:53:16.521  5585  5632 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-08 19:53:16.521  5585  5632 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-08 19:53:16.522  5585  5632 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,11-08 19:53:16.522  5817  5833 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-08 19:53:16.522  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 19:53:16.522  5817  5836 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-08 19:53:16.523  5585  5632 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-08 19:53:16.523  5585  5632 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-08 19:53:16.524  5585  5632 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-08 19:53:16.525  5585  5632 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-08 19:53:16.541  5817  5833 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-08 19:53:16.542  5817  5833 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 19:53:16.542  5817  5833 D BtGatt.GattService: current time is 124435828584
,11-08 19:53:16.542  5817  5833 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -90, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -82, 53, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -84, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -75, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-08 19:53:16.542  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-08 19:53:16.542  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-08 19:53:16.543  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-08 19:53:16.543  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-08 19:53:16.543  5817  5833 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-08 19:53:17.018  5585  5585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 19:53:18.379   926  2946 D ConnectivityService: handlePromptUnvalidated 102
,11-08 19:53:18.529  5585  5632 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-08 19:53:18.683  5585  5919 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 19:53:18.683  5585  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 19:53:19.496  5585  5919 W !!      : call onHalfStreamCopied
,11-08 19:53:19.496  5585  5919 I testCopyDataAndClose: closing input stream
,11-08 19:53:19.624   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 19:53:20.278  5585  5919 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 19:53:20.625   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:21.249   926  2931 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,11-08 19:53:21.445   926  2931 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-08 19:53:21.626   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:22.627   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:23.628   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:24.616  5585  5632 I StreamCopyingThreadTest: Starting test: testRun
,11-08 19:53:24.620  5585  5920 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-08 19:53:24.620  5585  5920 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 19:53:24.629   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-08 19:53:26.612  3625  3811 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-08 19:53:26.612  3625  3811 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-08 19:53:26.640  3572  3572 I ConfigService: onCreate
,11-08 19:53:29.627  5585  5921 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-08 19:53:29.630  5585  5632 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-08 19:53:29.833  5585  5923 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 19:53:29.833  5585  5923 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 19:53:31.467  5585  5923 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 19:53:31.467  5585  5923 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 19:53:31.468  5585  5923 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 19:53:31.468  5585  5923 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 19:53:31.468  5585  5923 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 19:53:31.468  5585  5923 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 19:53:31.468  5585  5923 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 19:53:31.468  5585  5923 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-08 19:53:31.468  5585  5923 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 19:53:31.468  5585  5923 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 19:53:31.468  5585  5923 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 19:53:31.669  3572  3572 I ConfigService: onDestroy
,11-08 19:53:34.630   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:35.632   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:35.870  5585  5632 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-08 19:53:35.873  5585  5924 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-08 19:53:35.873  5585  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 19:53:35.873  5585  5924 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-08 19:53:35.873  5585  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 19:53:35.873  5585  5924 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 19:53:35.873  5585  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 19:53:35.874  5585  5924 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 19:53:35.874  5585  5924 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-08 19:53:35.874  5585  5924 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 19:53:35.874  5585  5924 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 19:53:35.874  5585  5924 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 19:53:35.874  5585  5924 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-08 19:53:35.874  5585  5924 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-08 19:53:35.876  5585  5632 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-08 19:53:35.876  5585  5632 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-08 19:53:35.877  5585  5632 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-08 19:53:35.880  5585  5925 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-08 19:53:35.880  5585  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 19:53:35.880  5585  5925 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
11-08 19:53:35.880  5585  5925 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-08 19:53:35.880  5585  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-08 19:53:35.881  5585  5925 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-08 19:53:35.881  5585  5925 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-08 19:53:35.881  5585  5925 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-08 19:53:35.882  5585  5632 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-08 19:53:35.882  5585  5632 E com.test.thalitest.ThaliTestRunner: 
11-08 19:53:35.882  5585  5632 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 19:53:35.882  5585  5632 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
,11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 19:53:35.883  5585,  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 19:53:35.883  5585  5632 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-08 19:53:35.884  5585  5632 E com.test.t,halitest.ThaliTestRunner: Expected: is <true>
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363,)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:53:35.884  5585  5632 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 19:53:35.886  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG UnitTest_app: 'Running unit tests'
11-08 19:53:35.886  5585  5632 I jxcore-log: 
11-08 19:53:35.886  5585  5632 I jxcore-log: *Native tests were executed*
11-08 19:53:35.886  5585  5632 I jxcore-log: 
11-08 19:53:35.886  5585  5632 I jxcore-log: Total number of executed tests:  82
11-08 19:53:35.886  5585  5632 I jxcore-log: 
11-08 19:53:35.886  5585  5632 I jxcore-log: Number of passed tests:  80
11-08 19:53:35.886  5585  5632 I jxcore-log: 
11-08 19:53:35.886  5585  5632 I jxcore-log: Number of failed tests:  2
11-08 19:53:35.886  5585  5632 I jxcore-log: 
11-08 19:53:35.886  5585  5632 I jxcore-log: Number of ignored tests:  0
11-08 19:53:35.886  5585  5632 I jxcore-log: 
,11-08 19:53:35.887  5585  5632 I jxcore-log: Total duration:  46843
11-08 19:53:35.887  5585  5632 I jxcore-log: 
11-08 19:53:35.887  5585  5632 I jxcore-log: Failed to execute UT.
11-08 19:53:35.887  5585  5632 I jxcore-log: 
11-08 19:53:35.888  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-08 19:53:35.888  5585  5632 I jxcore-log: 
11-08 19:53:35.889  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-08 19:53:35.889  5585  5632 I jxcore-log: 
11-08 19:53:35.893  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.893  5585  5632 I jxcore-log: 
,11-08 19:53:35.894  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.894  5585  5632 I jxcore-log: 
11-08 19:53:35.895  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.895  5585  5632 I jxcore-log: 
,11-08 19:53:35.896  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.896  5585  5632 I jxcore-log: 
11-08 19:53:35.896  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.896  5585  5632 I jxcore-log: 
11-08 19:53:35.897  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.897  5585  5632 I jxcore-log: 
11-08 19:53:35.897  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 19:53:35.897  5585  5632 I jxcore-log: 
11-08 19:53:35.897  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 19:53:35.897  5585  5632 I jxcore-log: 
,11-08 19:53:35.898  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 19:53:35.898  5585  5632 I jxcore-log: 
11-08 19:53:35.898  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 19:53:35.898  5585  5632 I jxcore-log: 
11-08 19:53:35.898  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.898  5585  5632 I jxcore-log: 
11-08 19:53:35.898  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.898  5585  5632 I jxcore-log: 
11-08 19:53:35.899  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.899  5585  5632 I jxcore-log: 
,11-08 19:53:35.899  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.899  5585  5632 I jxcore-log: 
11-08 19:53:35.899  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 19:53:35.899  5585  5632 I jxcore-log: 
11-08 19:53:35.899  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.899  5585  5632 I jxcore-log: 
11-08 19:53:35.900  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 19:53:35.900  5585  5632 I jxcore-log: 
11-08 19:53:35.900  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.900  5585  5632 I jxcore-log: 
11-08 19:53:35.900  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 19:53:35.900  5585  5632 I jxcore-log: 
11-08 19:53:35.900  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.900  5585  5632 I jxcore-log: 
,11-08 19:53:35.900  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 19:53:35.900  5585  5632 I jxcore-log: 
11-08 19:53:35.901  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.901  5585  5632 I jxcore-log: 
11-08 19:53:35.901  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.901  5585  5632 I jxcore-log: 
11-08 19:53:35.901  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.901  5585  5632 I jxcore-log: 
,11-08 19:53:35.901  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.901  5585  5632 I jxcore-log: 
11-08 19:53:35.902  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.902  5585  5632 I jxcore-log: 
11-08 19:53:35.902  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.902  5585  5632 I jxcore-log: 
11-08 19:53:35.902  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.902  5585  5632 I jxcore-log: 
11-08 19:53:35.902  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.902  5585  5632 I jxcore-log: 
,11-08 19:53:35.904  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.904  5585  5632 I jxcore-log: 
11-08 19:53:35.904  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.904  5585  5632 I jxcore-log: 
,11-08 19:53:35.904  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.904  5585  5632 I jxcore-log: 
11-08 19:53:35.904  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.904  5585  5632 I jxcore-log: 
11-08 19:53:35.905  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.905  5585  5632 I jxcore-log: 
11-08 19:53:35.905  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.905  5585  5632 I jxcore-log: 
11-08 19:53:35.905  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.905  5585  5632 I jxcore-log: 
11-08 19:53:35.905  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.905  5585  5632 I jxcore-log: 
,11-08 19:53:35.905  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.905  5585  5632 I jxcore-log: 
11-08 19:53:35.905  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.905  5585  5632 I jxcore-log: 
11-08 19:53:35.906  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.906  5585  5632 I jxcore-log: 
11-08 19:53:35.906  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.906  5585  5632 I jxcore-log: 
11-08 19:53:35.906  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.906  5585  5632 I jxcore-log: 
11-08 19:53:35.906  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.906  5585  5632 I jxcore-log: 
,11-08 19:53:35.907  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.907  5585  5632 I jxcore-log: 
11-08 19:53:35.907  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.907  5585  5632 I jxcore-log: 
11-08 19:53:35.907  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.907  5585  5632 I jxcore-log: 
11-08 19:53:35.907  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.907  5585  5632 I jxcore-log: 
11-08 19:53:35.907  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.907  5585  5632 I jxcore-log: 
11-08 19:53:35.907  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.907  5585  5632 I jxcore-log: 
11-08 19:53:35.908  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.908  5585  5632 I jxcore-log: 
11-08 19:53:35.908  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.908  5585  5632 I jxcore-log: 
11-08 19:53:35.908  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.908  5585  5632 I jxcore-log: 
11-08 19:53:35.908  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.908  5585  5632 I jxcore-log: 
11-08 19:53:35.908  5585  5585 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-08 19:53:35.908  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.908  5585  5632 I jxcore-log: 
11-08 19:53:35.909  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.909  5585  5632 I jxcore-log: 
11-08 19:53:35.909  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.909  5585  5632 I jxcore-log: 
11-08 19:53:35.909  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.909  5585  5632 I jxcore-log: 
11-08 19:53:35.909  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.909  5585  5632 I jxcore-log: 
11-08 19:53:35.909  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.909  5585  5632 I jxcore-log: 
11-08 19:53:35.910  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.910  5585  5632 I jxcore-log: 
11-08 19:53:35.910  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.910  5585  5632 I jxcore-log: 
11-08 19:53:35.910  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 19:53:35.910  5585  5632 I jxcore-log: 
11-08 19:53:35.910  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.910  5585  5632 I jxcore-log: 
11-08 19:53:35.910  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 19:53:35.910  5585  5632 I jxcore-log: 
11-08 19:53:35.910  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.910  5585  5632 I jxcore-log: 
,11-08 19:53:35.911  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 19:53:35.911  5585  5632 I jxcore-log: 
11-08 19:53:35.911  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.911  5585  5632 I jxcore-log: 
11-08 19:53:35.911  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.911  5585  5632 I jxcore-log: 
11-08 19:53:35.911  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.911  5585  5632 I jxcore-log: 
11-08 19:53:35.911  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.911  5585  5632 I jxcore-log: 
11-08 19:53:35.912  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.912  5585  5632 I jxcore-log: 
,11-08 19:53:35.912  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.912  5585  5632 I jxcore-log: 
11-08 19:53:35.912  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.912  5585  5632 I jxcore-log: 
11-08 19:53:35.912  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 19:53:35.912  5585  5632 I jxcore-log: 
11-08 19:53:35.912  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.912  5585  5632 I jxcore-log: 
11-08 19:53:35.913  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 19:53:35.913  5585  5632 I jxcore-log: 
,11-08 19:53:35.913  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.913  5585  5632 I jxcore-log: 
11-08 19:53:35.913  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.913  5585  5632 I jxcore-log: 
11-08 19:53:35.913  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.913  5585  5632 I jxcore-log: 
11-08 19:53:35.913  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.913  5585  5632 I jxcore-log: 
11-08 19:53:35.914  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 19:53:35.914  5585  5632 I jxcore-log: 
11-08 19:53:35.914  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 19:53:35.914  5585  5632 I jxcore-log: 
,11-08 19:53:35.914  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-08 19:53:35.914  5585  5632 I jxcore-log: 
11-08 19:53:35.914  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-08 19:53:35.914  5585  5632 I jxcore-log: 
11-08 19:53:35.914  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 19:53:35.914  5585  5632 I jxcore-log: 
,11-08 19:53:35.919  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-08 19:53:35.919  5585  5632 I jxcore-log: 
11-08 19:53:35.920  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - WARN testUtils: 'myNameCallback not set!'
11-08 19:53:35.920  5585  5632 I jxcore-log: 
,11-08 19:53:35.921  5585  5632 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,11-08 19:53:35.921  5585  5632 I jxcore-log: 2016-11-08 18:53:35 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-08 19:53:35.921  5585  5632 I jxcore-log: 
,11-08 19:53:36.633   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:37.634   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:38.013  5585  5632 I jxcore-log: 2016-11-08 18:53:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-08 19:53:38.013  5585  5632 I jxcore-log: 
,11-08 19:53:38.044   926  5894 D NetlinkSocketObserver: NeighborEvent{elapsedMs=145937, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-08 19:53:38.351  5585  5632 I jxcore-log: 2016-11-08 18:53:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-08 19:53:38.351  5585  5632 I jxcore-log: 
,11-08 19:53:38.365  5585  5632 I jxcore-log: 2016-11-08 18:53:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-08 19:53:38.365  5585  5632 I jxcore-log: 
,11-08 19:53:38.635   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:39.469  5585  5632 I jxcore-log: 2016-11-08 18:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-08 19:53:39.469  5585  5632 I jxcore-log: 
,11-08 19:53:39.636   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-08 19:53:39.644  5585  5632 I jxcore-log: 2016-11-08 18:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-08 19:53:39.644  5585  5632 I jxcore-log: 
,11-08 19:53:39.649  5585  5632 I jxcore-log: 2016-11-08 18:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-08 19:53:39.649  5585  5632 I jxcore-log: 
,11-08 19:53:39.654  5585  5632 I jxcore-log: 2016-11-08 18:53:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-08 19:53:39.654  5585  5632 I jxcore-log: 
,11-08 19:53:40.142  5585  5632 I jxcore-log: 2016-11-08 18:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-08 19:53:40.142  5585  5632 I jxcore-log: 
,11-08 19:53:40.186  5585  5632 I jxcore-log: 2016-11-08 18:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-08 19:53:40.186  5585  5632 I jxcore-log: 
,11-08 19:53:40.199  5585  5632 I jxcore-log: 2016-11-08 18:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-08 19:53:40.199  5585  5632 I jxcore-log: 
,11-08 19:53:40.203  5585  5632 I jxcore-log: 2016-11-08 18:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-08 19:53:40.203  5585  5632 I jxcore-log: 
,11-08 19:53:40.494  5585  5632 I jxcore-log: 2016-11-08 18:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-08 19:53:40.494  5585  5632 I jxcore-log: 
,11-08 19:53:40.638  5585  5632 I jxcore-log: 2016-11-08 18:53:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-08 19:53:40.638  5585  5632 I jxcore-log: 
,11-08 19:53:41.010  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-08 19:53:41.010  5585  5632 I jxcore-log: 
,11-08 19:53:41.044  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-08 19:53:41.044  5585  5632 I jxcore-log: 
,11-08 19:53:41.051  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-08 19:53:41.051  5585  5632 I jxcore-log: 
,11-08 19:53:41.056  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-08 19:53:41.056  5585  5632 I jxcore-log: 
,11-08 19:53:41.063  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-08 19:53:41.063  5585  5632 I jxcore-log: 
,11-08 19:53:41.076  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-08 19:53:41.076  5585  5632 I jxcore-log: 
,11-08 19:53:41.081  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-08 19:53:41.081  5585  5632 I jxcore-log: 
,11-08 19:53:41.108  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-08 19:53:41.108  5585  5632 I jxcore-log: 
,11-08 19:53:41.145  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-08 19:53:41.145  5585  5632 I jxcore-log: 
,11-08 19:53:41.153  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-08 19:53:41.153  5585  5632 I jxcore-log: 
,11-08 19:53:41.159  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-08 19:53:41.159  5585  5632 I jxcore-log: 
,11-08 19:53:41.174  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-08 19:53:41.174  5585  5632 I jxcore-log: 
,11-08 19:53:41.179  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-08 19:53:41.179  5585  5632 I jxcore-log: 
,11-08 19:53:41.185  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-08 19:53:41.185  5585  5632 I jxcore-log: 
,11-08 19:53:41.190  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-08 19:53:41.190  5585  5632 I jxcore-log: 
,11-08 19:53:41.203  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-08 19:53:41.203  5585  5632 I jxcore-log: 
,11-08 19:53:41.210  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-08 19:53:41.210  5585  5632 I jxcore-log: 
,11-08 19:53:41.232  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-08 19:53:41.232  5585  5632 I jxcore-log: 
,11-08 19:53:41.243  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-08 19:53:41.243  5585  5632 I jxcore-log: 
,11-08 19:53:41.255  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-08 19:53:41.255  5585  5632 I jxcore-log: 
,11-08 19:53:41.265  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-08 19:53:41.265  5585  5632 I jxcore-log: 
,11-08 19:53:41.278  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-08 19:53:41.278  5585  5632 I jxcore-log: 
,11-08 19:53:41.288  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-08 19:53:41.288  5585  5632 I jxcore-log: 
,11-08 19:53:41.295  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-08 19:53:41.295  5585  5632 I jxcore-log: 
,11-08 19:53:41.300  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-08 19:53:41.300  5585  5632 I jxcore-log: 
,11-08 19:53:41.306  5585  5632 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-08 19:53:41.307  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - INFO testUtils: 'BLE multiple advertisement supported'
11-08 19:53:41.307  5585  5632 I jxcore-log: 
,11-08 19:53:41.381  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:41.381  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:41.381  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:41.381  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:41.381  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:41.381  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:41.381  5585  5632 I jxcore-log: 
,11-08 19:53:41.617  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:41.617  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:41.617  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:41.617  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:41.617  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:41.617  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:41.617  5585  5632 I jxcore-log: 
,11-08 19:53:41.621  5585  5632 I jxcore-log: 2016-11-08 18:53:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:41.621  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:41.621  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:41.621  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:41.621  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:41.621  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:41.621  5585  5632 I jxcore-log: 
,11-08 19:53:42.382  5585  5632 I jxcore-log: 2016-11-08 18:53:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:42.382  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:42.382  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:42.382  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:42.382  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:42.382  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:42.382  5585  5632 I jxcore-log: 
,11-08 19:53:42.387  5585  5632 I jxcore-log: 2016-11-08 18:53:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:42.387  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:42.387  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:42.387  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:42.387  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:42.387  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:42.387  5585  5632 I jxcore-log: 
,11-08 19:53:43.415  5585  5632 I jxcore-log: 2016-11-08 18:53:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:43.415  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:43.415  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:43.415  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:43.415  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:43.415  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:43.415  5585  5632 I jxcore-log: 
,11-08 19:53:43.419  5585  5632 I jxcore-log: 2016-11-08 18:53:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:43.419  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:43.419  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:43.419  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:43.419  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:43.419  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:43.419  5585  5632 I jxcore-log: 
,11-08 19:53:43.833   926   946 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-08 19:53:43.841   936   936 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33086]" dev="sockfs" ino=33086 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:43.841   936   936 W Binder_1: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[33086]" dev="sockfs" ino=33086 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 19:53:43.845  3625  3625 I Keyboard.Facilitator: onFinishInput()
,11-08 19:53:43.857   926   946 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 19:53:43.857   926   946 I Adreno  : Build Date                       : 12/06/15
11-08 19:53:43.857   926   946 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 19:53:43.857   926   946 I Adreno  : Local Branch                     : mybranch17112971
11-08 19:53:43.857   926   946 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 19:53:43.857   926   946 I Adreno  : Remote Branch                    : NONE
11-08 19:53:43.857   926   946 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 19:53:43.893   382   495 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (303 us)
,11-08 19:53:44.585  5585  5585 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-08 19:53:44.586  5585  5585 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-08 19:53:44.616   926   946 I sensors : batch
,11-08 19:53:44.617   926   946 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-08 19:53:44.619   926   946 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,11-08 19:53:44.618  5585  5585 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9345e67 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ba727f9, 16908290=android.view.AbsSavedState$1@ba727f9}, android:focusedViewId=100}]}]
11-08 19:53:44.619  5585  5585 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-08 19:53:44.619   926   946 I sensors : activate
11-08 19:53:44.620   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f8fcc3c00
,11-08 19:53:44.620   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-08 19:53:44.620   926   944 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-08 19:53:44.621  5585  5585 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-08 19:53:44.621  5585  5585 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,11-08 19:53:44.627   926  2767 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,11-08 19:53:44.629   926  2767 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-08 19:53:44.832   507   919 D TetherController: Setting IP forward enable = 1
,11-08 19:53:44.914   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-08 19:53:44.915   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-08 19:53:44.915   926  3066 D SurfaceControl: Excessive delay in setPowerMode(): 295ms
,11-08 19:53:44.921   926   946 I DreamManagerService: Entering dreamland.
,11-08 19:53:44.921   926   946 I PowerManagerService: Dozing...
11-08 19:53:44.921   926   941 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-08 19:53:44.934   937   937 W Binder_2: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[31451]" dev="sockfs" ino=31451 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 19:53:44.934   937   937 W Binder_2: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[31451]" dev="sockfs" ino=31451 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:44.939   926  3794 I sensors : batch
,11-08 19:53:44.940   926  3794 I sensors : activate
,11-08 19:53:44.943   926  2767 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
11-08 19:53:44.943   926  2767 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-08 19:53:44.947   512  2986 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-08 19:53:44.951   926  2931 E native  : do suspend false
,11-08 19:53:44.956   926  2931 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 19:53:44.966  3765  4735 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-08 19:53:44.966  3765  4735 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-08 19:53:44.966  3765  4735 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 19:53:44.967   525  1266 D         : oem-qmi: Connection accepted
11-08 19:53:44.967   525  1266 D         : oem-qmi: Waiting to accept connection
,11-08 19:53:44.968   926   926 I sensors : activate
11-08 19:53:44.969  3765  4735 D         : oem_qmi_lib:output 0
,11-08 19:53:44.969  3765  4735 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
11-08 19:53:44.969   512   512 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,11-08 19:53:44.971   926  2931 E native  : do suspend true
,11-08 19:53:44.971   926  2767 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-08 19:53:44.986  3765  4735 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
11-08 19:53:44.986  3765  4735 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
,11-08 19:53:44.986  3765  4735 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 19:53:44.987   525  1266 D         : oem-qmi: Connection accepted
11-08 19:53:44.987   525  1266 D         : oem-qmi: Waiting to accept connection
,11-08 19:53:44.988  3765  4735 D         : oem_qmi_lib:output 0
,11-08 19:53:44.989  3765  4735 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-08 19:53:45.350  5585  5632 I jxcore-log: 2016-11-08 18:53:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:45.350  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:45.350  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:45.350  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:45.350  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:45.350  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:45.350  5585  5632 I jxcore-log: 
,11-08 19:53:45.362  5585  5632 I jxcore-log: 2016-11-08 18:53:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:45.362  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:45.362  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:45.362  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:45.362  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:45.362  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:45.362  5585  5632 I jxcore-log: 
,11-08 19:53:45.449   926  2931 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-08 19:53:46.370   926  5894 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-08 19:53:46.398  5585  5632 I jxcore-log: 2016-11-08 18:53:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:46.398  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:46.398  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:46.398  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:46.398  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:46.398  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:46.398  5585  5632 I jxcore-log: 
,11-08 19:53:46.403  5585  5632 I jxcore-log: 2016-11-08 18:53:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:46.403  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:46.403  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:46.403  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:46.403  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:46.403  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:46.403  5585  5632 I jxcore-log: 
,11-08 19:53:47.438  5585  5632 I jxcore-log: 2016-11-08 18:53:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:47.438  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:47.438  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:47.438  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:47.438  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:47.438  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:47.438  5585  5632 I jxcore-log: 
,11-08 19:53:47.443  5585  5632 I jxcore-log: 2016-11-08 18:53:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:47.443  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:47.443  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:47.443  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:47.443  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:47.443  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:47.443  5585  5632 I jxcore-log: 
,11-08 19:53:48.465  3728  4425 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-08 19:53:48.480  5585  5632 I jxcore-log: 2016-11-08 18:53:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:48.480  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:48.480  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:48.480  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:48.480  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:48.480  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:48.480  5585  5632 I jxcore-log: 
,11-08 19:53:48.484  5585  5632 I jxcore-log: 2016-11-08 18:53:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:48.484  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:48.484  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:48.484  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:48.484  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:48.484  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:48.484  5585  5632 I jxcore-log: 
,11-08 19:53:49.524  5585  5632 I jxcore-log: 2016-11-08 18:53:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:49.524  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:49.524  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:49.524  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:49.524  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:49.524  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:49.524  5585  5632 I jxcore-log: 
,11-08 19:53:49.528  5585  5632 I jxcore-log: 2016-11-08 18:53:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:49.528  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:49.528  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:49.528  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:49.528  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:49.528  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:49.528  5585  5632 I jxcore-log: 
,11-08 19:53:50.354   926  2931 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,11-08 19:53:50.562  5585  5632 I jxcore-log: 2016-11-08 18:53:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:50.562  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:50.562  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:50.562  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:50.562  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:50.562  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:50.562  5585  5632 I jxcore-log: 
,11-08 19:53:50.566  5585  5632 I jxcore-log: 2016-11-08 18:53:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:50.566  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:50.566  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:50.566  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:50.566  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:50.566  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:50.566  5585  5632 I jxcore-log: 
,11-08 19:53:51.643  5585  5632 I jxcore-log: 2016-11-08 18:53:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:51.643  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:51.643  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:51.643  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:51.643  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:51.643  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:51.643  5585  5632 I jxcore-log: 
,11-08 19:53:51.647  5585  5632 I jxcore-log: 2016-11-08 18:53:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:51.647  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:51.647  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:51.647  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:51.647  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:51.647  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:51.647  5585  5632 I jxcore-log: 
,11-08 19:53:52.683  5585  5632 I jxcore-log: 2016-11-08 18:53:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:52.683  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:52.683  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:52.683  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:52.683  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:52.683  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:52.683  5585  5632 I jxcore-log: 
,11-08 19:53:52.689  5585  5632 I jxcore-log: 2016-11-08 18:53:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:52.689  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:52.689  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:52.689  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:52.689  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:52.689  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:52.689  5585  5632 I jxcore-log: 
,11-08 19:53:53.748  5585  5632 I jxcore-log: 2016-11-08 18:53:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:53.748  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:53.748  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:53.748  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:53.748  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:53.748  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:53.748  5585  5632 I jxcore-log: 
,11-08 19:53:53.754  5585  5632 I jxcore-log: 2016-11-08 18:53:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:53.754  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:53.754  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:53.754  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:53.754  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:53.754  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:53.754  5585  5632 I jxcore-log: 
,11-08 19:53:54.637   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:54.784  5585  5632 I jxcore-log: 2016-11-08 18:53:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:54.784  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:54.784  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:54.784  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:54.784  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:54.784  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:54.784  5585  5632 I jxcore-log: 
,11-08 19:53:54.790  5585  5632 I jxcore-log: 2016-11-08 18:53:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:54.790  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:54.790  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:54.790  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:54.790  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:54.790  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:54.790  5585  5632 I jxcore-log: 
,11-08 19:53:55.638   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:55.821  5585  5632 I jxcore-log: 2016-11-08 18:53:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:55.821  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:55.821  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:55.821  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:55.821  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:55.821  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:55.821  5585  5632 I jxcore-log: 
,11-08 19:53:55.828  5585  5632 I jxcore-log: 2016-11-08 18:53:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:55.828  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:55.828  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:55.828  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:55.828  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:55.828  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:55.828  5585  5632 I jxcore-log: 
,11-08 19:53:56.639   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 19:53:56.870  5585  5632 I jxcore-log: 2016-11-08 18:53:56 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 19:53:56.870  5585  5632 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 19:53:56.870  5585  5632 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 19:53:56.870  5585  5632 I jxcore-log: emit@events.js:82:1
11-08 19:53:56.870  5585  5632 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 19:53:56.870  5585  5632 I jxcore-log: emit@events.js:82:1'
11-08 19:53:56.870  5585  5632 I jxcore-log: 
,11-08 19:53:56.883  5585  5632 E jxcore  : Error!: error is undefined
11-08 19:53:56.883  5585  5632 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-08 19:53:56.887  5585  5632 I jxcore-log: 2016-11-08 18:53:56 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-08 19:53:56.887  5585  5632 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-08 19:53:56.887  5585  5632 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-08 19:53:56.887  5585  5632 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-08 19:53:56.887  5585  5632 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-08 19:53:56.887  5585  5632 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-08 19:53:56.887  5585  5632 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-08 19:53:56.887  5585  5632 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
11-08 19:53:56.888  5585  5632 I jxcore-log: 2016-11-08 18:53:56 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-08 19:53:56.888  5585  5632 I jxcore-log: 
,11-08 19:53:56.891  5585  5632 E jxcore-log: TypeError: 
11-08 19:53:56.892  5585  5632 E jxcore-log: error is undefined
11-08 19:53:56.892  5585  5632 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-08 19:53:56.892  5585  5632 E jxcore-log: 
,11-08 19:53:56.982   926   937 I WindowState: WIN DEATH: Window{8feb98e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-08 19:53:56.983   926  2942 D WifiService: Client connection lost with reason: 4
11-08 19:53:56.983   926  3132 D GraphicsStats: Buffer count: 2
,11-08 19:53:56.990   527   527 I Zygote  : Process 5585 exited cleanly (139)
,11-08 19:53:56.993   926  3548 I ActivityManager: Process com.test.thalitest (pid 5585) has died
,11-08 19:53:57.010   926  3548 I ActivityManager: Start proc 5971:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-08 19:53:57.079  5971  5971 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-08 19:53:57.098  5971  5971 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-08 19:53:57.103  5971  5971 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4995-4997)
,11-08 19:53:57.104  5971  5971 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 19:53:57.113  5971  5971 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9e0f050}
,11-08 19:53:57.113  5971  5971 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-08 19:53:57.114  5971  5971 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-08 19:53:57.117  5971  5971 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-08 19:53:57.118  5971  5971 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 19:53:57.128  5971  5971 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 19:53:57.136  5971  5971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-08 19:53:57.136  5971  5971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 19:53:57.136  5971  5971 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 19:53:57.136  5971  5971 I Adreno  : Build Date                       : 12/06/15
11-08 19:53:57.136  5971  5971 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 19:53:57.136  5971  5971 I Adreno  : Local Branch                     : mybranch17112971
11-08 19:53:57.136  5971  5971 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 19:53:57.136  5971  5971 I Adreno  : Remote Branch                    : NONE
11-08 19:53:57.136  5971  5971 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 19:53:57.197   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9e52474:true
,11-08 19:53:57.204   403   403 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[16785]" dev="sockfs" ino=16785 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-08 19:53:57.204   403   403 W Binder_1: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[16785]" dev="sockfs" ino=16785 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:57.217  5971  5971 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 19:53:57.225  5971  5971 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 19:53:57.261  2920  2920 W Binder_4: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[32322]" dev="sockfs" ino=32322 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:57.265  5971  6007 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-08 19:53:57.261  2920  2920 W Binder_4: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[32322]" dev="sockfs" ino=32322 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:57.264  3785  3785 W Binder_9: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[16791]" dev="sockfs" ino=16791 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:57.264  3785  3785 W Binder_9: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[16791]" dev="sockfs" ino=16791 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:57.271  5971  5994 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 19:53:57.311  5971  6007 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 19:53:57.325  5969  5969 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-08 19:53:57.336   926  3132 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5585 uid 10077
,11-08 19:53:57.338  5969  5969 D AndroidRuntime: CheckJNI is OFF
11-08 19:53:57.334  3132  3132 W Binder_3: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[31497]" dev="sockfs" ino=31497 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:57.334  3132  3132 W Binder_3: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[31497]" dev="sockfs" ino=31497 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:57.334  3784  3784 W Binder_8: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[31496]" dev="sockfs" ino=31496 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 19:53:57.341  3625  3625 I Keyboard.Facilitator: onFinishInput()
11-08 19:53:57.334  3784  3784 W Binder_8: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[31496]" dev="sockfs" ino=31496 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 19:53:57.360  5969  5969 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-08 19:53:57.363   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +334ms (total +367ms)
,11-08 19:53:57.363  5971  5971 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5971
,11-08 19:53:57.382  5969  5969 I Radio-JNI: register_android_hardware_Radio DONE
,11-08 19:53:57.396  5969  5969 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-08 19:53:57.406   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-08 19:53:57.407   926   939 I ActivityManager: Killing 5971:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-08 19:53:57.438   926  3784 D GraphicsStats: Buffer count: 2
,11-08 19:53:57.438   926  3785 I WindowState: WIN DEATH: Window{19445d3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-08 19:53:57.509   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-08 19:53:57.509   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-08 19:53:57.510   926   939 E ActivityManager: Failure starting process com.test.thalitest
11-08 19:53:57.510   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-08 19:53:57.510   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:53:57.510   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:53:57.510   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 19:53:57.510   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-08 19:53:57.511   926   939 I ActivityManager:   Force finishing activity ActivityRecord{e3dc856 u0 com.test.thalitest/.MainActivity t68}
,11-08 19:53:57.512   926   949 I art     : Starting a blocking GC Explicit
,11-08 19:53:57.517   926  3548 W ActivityManager: Spurious death for ProcessRecord{133a809 0:com.test.thalitest/u0a77}, curProc for 5971: null
,11-08 19:53:57.594   926   949 I art     : Explicit concurrent mark sweep GC freed 16871(1134KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 1.638ms total 82.238ms
,11-08 19:53:57.614   926   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-08 19:53:57.617  5969  5969 I art     : System.exit called, status: 0
,11-08 19:53:57.617  5969  5969 I AndroidRuntime: VM exiting with result code 0.
,11-08 19:53:57.624   926   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-08 19:53:57.632   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-08 19:53:57.635  3625  3625 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-08 19:53:57.636  5817  5817 D BluetoothMapAppObserver: onReceive
11-08 19:53:57.636  5817  5817 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-08 19:53:57.641   541   541 I ServiceManager: Waiting for service AtCmdFwd...
11-08 19:53:57.644  3728  4056 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-08 19:53:57.646   926  2919 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-08 19:53:57.665  3388  6022 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-08 19:53:57.667  3625  6021 I Keyboard.Facilitator.DecoderInitializer: run()
,11-08 19:53:57.680  3625  6021 I Decoder : createOrResetDecoder
,11-08 19:53:57.704  3765  3765 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-08 19:53:57.726   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-08 19:53:57.727  3572  3572 I ConfigService: onCreate
,11-08 19:53:57.736  3572  3572 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-08 19:53:57.737  3572  3572 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-08 19:53:57.741    17    17 W kworker/2:0: type=1400 audit(0.0:141): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 19:53:57.748  3625  6021 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-08 19:53:57.748    17    17 W kworker/2:0: type=1400 audit(0.0:142): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 19:53:57.764    17    17 W kworker/2:0: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 19:53:57.773  3958  6029 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-08 19:53:57.773  3958  6029 D AccountUtils: Clearing selected account for com.test.thalitest
,11-08 19:53:57.785  3572  3572 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/ns.db'.
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:53:57.785  3572  3572 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 19:53:57.786  3572  3572 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
11-08 19:53:57.786  3572  3572 E AndroidRuntime: FATAL EXCEPTION: main
11-08 19:53:57.786  3572  3572 E AndroidRuntime: Process: com.google.process.gapps, PID: 3572
11-08 19:53:57.786  3572  3572 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 19:53:57.786  3572  3572 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 19:53:57.788  3388  6022 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-08 19:53:57.789  3388  6022 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-08 19:53:57.789  3388  6022 E AndroidRuntime: Process: android.process.acore, PID: 3388
11-08 19:53:57.789  3388  6022 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:53:57.789  3388  6022 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-08 19:53:57.792   926  6031 E DropBoxManagerService: Can't write: system_app_crash
11-08 19:53:57.792   926  6031 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 19:53:57.792   926  6031 E DropBoxManagerService: 	... 5 more
,11-08 19:53:57.794  3572  3572 I Process : Sending signal. PID: 3572 SIG: 9
,11-08 19:53:57.794   926  6032 E DropBoxManagerService: Can't write: system_app_crash
11-08 19:53:57.794   926  6032 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 19:53:57.794   926  6032 E DropBoxManagerService: 	... 5 more
,11-08 19:53:57.798  3388  6022 I Process : Sending signal. PID: 3388 SIG: 9
,11-08 19:53:57.821  3958  6029 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-08 19:53:57.827   926  2942 D WifiService: Client connection lost with reason: 4
11-08 19:53:57.827  3625  3625 W GmsClient: service died
,11-08 19:53:57.828   926  3588 I ActivityManager: Process com.google.process.gapps (pid 3572) has died
11-08 19:53:57.828   926  3588 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 1000ms
,11-08 19:53:57.828   926  3588 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
11-08 19:53:57.828   926  3588 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
11-08 19:53:57.828   926  3588 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
,11-08 19:53:57.841  3958  6029 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:53:57.841  3958  6029 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-08 19:53:57.841  3958  6029 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 19:53:57.842  3958  6029 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-08 19:53:57.849   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
11-08 19:53:57.849   926  3132 I ActivityManager: Start proc 6036:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService

```
