#### Test 92339050883a779_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-04 14:45:54.574  3939  4167 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
11-04 14:45:54.656  3939  4167 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-04 14:45:55.077  5590  5590 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-04 14:45:55.082  5590  5590 D AndroidRuntime: CheckJNI is OFF
11-04 14:45:55.110  5590  5590 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-04 14:45:55.143  5590  5590 I Radio-JNI: register_android_hardware_Radio DONE
11-04 14:45:55.158  5590  5590 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-04 14:45:55.161   930  4983 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-04 14:45:55.179  5590  5590 D AndroidRuntime: Shutting down VM
11-04 14:45:55.184  3926  3936 W SearchService: Abort, client detached.
11-04 14:45:55.193  3926  3926 I HotwordDetector: Closing mic
11-04 14:45:55.193  3926  4154 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e895839
11-04 14:45:55.194  3926  4157 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-04 14:45:55.209   930  3888 I ActivityManager: Start proc 5599:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-04 14:45:55.267   511  4159 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-04 14:45:55.268   511  4159 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-04 14:45:55.273   511  4159 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-04 14:45:55.273   511  4159 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-04 14:45:55.274   511  3014 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-04 14:45:55.277  3926  4156 I MicroRecognitionRnrImpl: Detection finished
11-04 14:45:55.278  3926  4155 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-04 14:45:55.298  5599  5599 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-04 14:45:55.322  5599  5599 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-04 14:45:55.380  5599  5599 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 5966-6022)
11-04 14:45:55.381  5599  5599 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 14:45:55.417  5599  5599 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4723e71}
,11-04 14:45:55.417  5599  5599 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 14:45:55.418  5599  5599 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 14:45:55.423  5599  5599 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 14:45:55.424  5599  5599 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 14:45:55.472  5599  5599 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 14:45:55.485  5599  5599 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 14:45:55.485  5599  5599 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 14:45:55.485  5599  5599 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 14:45:55.485  5599  5599 I Adreno  : Build Date                       : 12/06/15
11-04 14:45:55.485  5599  5599 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 14:45:55.485  5599  5599 I Adreno  : Local Branch                     : mybranch17112971
11-04 14:45:55.485  5599  5599 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 14:45:55.485  5599  5599 I Adreno  : Remote Branch                    : NONE
11-04 14:45:55.485  5599  5599 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 14:45:55.546   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4edc472:true
,11-04 14:45:55.582   747   747 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[22252]" dev="sockfs" ino=22252 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:45:55.582   747   747 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22252]" dev="sockfs" ino=22252 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:45:55.596  5599  5599 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 14:45:55.605  5599  5599 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 14:45:55.631  5599  5636 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 14:45:55.625   405   405 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[29466]" dev="sockfs" ino=29466 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:45:55.625   405   405 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[29466]" dev="sockfs" ino=29466 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:45:55.632  3884  3884 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[22263]" dev="sockfs" ino=22263 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:45:55.632  3884  3884 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22263]" dev="sockfs" ino=22263 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:45:55.638  5599  5623 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 14:45:55.670  5599  5636 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 14:45:55.754   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +567ms
,11-04 14:45:55.749  3179  3179 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33057]" dev="sockfs" ino=33057 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:45:55.749  3179  3179 W Binder_4: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33057]" dev="sockfs" ino=33057 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:45:55.749  3401  3401 W Binder_5: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33056]" dev="sockfs" ino=33056 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:45:55.752  3401  3401 W Binder_5: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33056]" dev="sockfs" ino=33056 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:45:55.757  3632  3632 I Keyboard.Facilitator: onFinishInput()
,11-04 14:45:55.793  5599  5599 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5599
,11-04 14:45:55.893  5599  5599 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 14:45:56.090  5599  5638 D jxcore_app_log: JniHelper::setJavaVM(0xf543c000), pthread_self() = -579864272
,11-04 14:45:56.094  5599  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-04 14:45:56.094  5599  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-04 14:45:56.094  5599  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-04 14:45:56.094  5599  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-04 14:45:56.094  5599  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-04 14:45:56.094  5599  5638 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5f761c added. We now have 1 listener(s)
,11-04 14:45:56.096  5599  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-04 14:45:56.097  5599  5638 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 14:45:56.097  5599  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 14:45:56.098  5599  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-04 14:45:56.100  5599  5638 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceb39ab added. We now have 1 listener(s)
11-04 14:45:56.100  5599  5638 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 14:45:56.105   930  2940 D WifiService: New client listening to asynchronous messages
,11-04 14:45:56.105  5599  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 14:45:56.105  5599  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-04 14:45:56.105  5599  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-04 14:45:56.105  5599  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-04 14:45:56.105  5599  5638 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-04 14:45:56.107  5599  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:45:56.107  5599  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 14:45:56.111  5599  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-04 14:45:56.111  5599  5638 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:45:56.111  5599  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:45:56.111  5599  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:45:56.111  5599  5638 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:45:56.111  5599  5638 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:45:56.111  5599  5638 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:45:56.111  5599  5638 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:45:56.111  5599  5638 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:45:56.111  5599  5638 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-04 14:45:56.111  5599  5638 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 14:45:56.112  5599  5638 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 14:45:56.214  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:45:56.217  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:45:56.222  5599  5599 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-04 14:45:56.489  5599  5647 W jxcore-log: Initializing JXcore engine
,11-04 14:45:56.489  5599  5647 W jxcore-log: JXcore engine is ready
,11-04 14:45:56.515  5647  5647 W Thread-66: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12575 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-04 14:45:56.515  5647  5647 W Thread-66: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13356]" dev="sockfs" ino=13356 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-04 14:45:56.515  5647  5647 W Thread-66: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-04 14:45:56.515  5647  5647 W Thread-66: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33040]" dev="sockfs" ino=33040 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-04 14:45:56.526  5599  5647 W jxcore-log: Starting JXcore engine
,11-04 14:45:56.581  5599  5647 W jxcore-log: Platform android
11-04 14:45:56.581  5599  5647 W jxcore-log: 
,11-04 14:45:56.581  5599  5647 W jxcore-log: Process ARCH arm
11-04 14:45:56.581  5599  5647 W jxcore-log: 
,11-04 14:45:56.723  5599  5647 I jxcore-log: JXcore Cordova bridge is ready!
11-04 14:45:56.723  5599  5647 I jxcore-log: 
,11-04 14:45:56.724  5599  5647 W jxcore-log: JXcore engine is started
,11-04 14:45:56.728  5599  5638 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-04 14:45:56.732  5599  5599 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-04 14:45:58.710  3560  3560 I ConfigService: onDestroy
,11-04 14:46:00.196   930  3179 I ActivityManager: Killing 5240:org.codeaurora.ims/1001 (adj 15): empty #17
,11-04 14:46:00.666   930  2933 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 14:46:03.735   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:04.736   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:05.738   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:06.687  5599  5647 I jxcore-log: 2016-11-04 13:46:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-04 14:46:06.687  5599  5647 I jxcore-log: 
,11-04 14:46:06.689  5599  5647 I jxcore-log: 2016-11-04 13:46:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-04 14:46:06.689  5599  5647 I jxcore-log: 
,11-04 14:46:06.694  5599  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:46:06.694  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:06.694  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:06.694  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:06.694  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:06.694  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:06.694  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:06.694  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:46:06.696  5599  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:06.699  5599  5647 I jxcore-log: 2016-11-04 13:46:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-04 14:46:06.699  5599  5647 I jxcore-log: 
11-04 14:46:06.700  5599  5647 I jxcore-log: 2016-11-04 13:46:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-04 14:46:06.700  5599  5647 I jxcore-log: 
,11-04 14:46:06.739   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:06.961  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 14:46:06.961  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4117c8 added. We now have 2 listener(s)
11-04 14:46:06.962  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:46:06.962  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 14:46:06.962  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 14:46:06.962  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 14:46:06.962  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa64061 added. We now have 2 listener(s)
11-04 14:46:06.962  5599  5647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 14:46:06.963  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 14:46:06.965  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:46:06.968  5599  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:46:06.968  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:06.968  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:06.968  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:06.968  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:06.968  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:06.968  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:06.968  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:46:06.969  5599  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:06.969  5599  5647 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 14:46:06.970  5599  5647 D ExecuteNativeTests: Running unit tests
,11-04 14:46:06.970  5599  5647 D BluetoothAdapter: enable(): BT is already enabled..!
,11-04 14:46:06.970   930  3812 D WifiService: setWifiEnabled: true pid=5599, uid=10077
11-04 14:46:06.970   930  3812 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:06.975  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:06.980  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:07.740   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:08.351   930  2940 D WifiService: New client listening to asynchronous messages
,11-04 14:46:08.354  3926  5649 W CronetSyncConnectionRcs: Upload content type not set.
,11-04 14:46:08.428  4858  4903 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-04 14:46:08.429  4858  4858 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-04 14:46:08.432   930  3402 I ActivityManager: Killing 5280:com.android.settings/1000 (adj 15): empty #17
,11-04 14:46:08.740   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 14:46:16.975  5599  5647 I com.test.thalitest.ThaliTestRunner: Running UT
,11-04 14:46:17.042  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 14:46:17.042  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec0b04b added. We now have 3 listener(s)
11-04 14:46:17.043  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 14:46:17.043  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 14:46:17.043  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 14:46:17.043  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 14:46:17.044  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c41a28 added. We now have 3 listener(s)
11-04 14:46:17.044  5599  5647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 14:46:17.044  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 14:46:17.046  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:46:17.050  5599  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:46:17.050  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:17.050  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:17.050  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:17.050  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:17.050  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:17.050  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:17.050  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:46:17.051  5599  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:17.052  5599  5647 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 14:46:17.057  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-04 14:46:17.058  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-04 14:46:17.058  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:46:17.058  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:46:17.058  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:46:17.059  5599  5647 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-04 14:46:17.059  5599  5647 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 14:46:17.059  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-04 14:46:17.059  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 14:46:17.059  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:46:17.059  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:46:17.060  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-04 14:46:17.061  5599  5647 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-04 14:46:17.061  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:17.062  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-04 14:46:17.063  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-04 14:46:17.064  5599  5647 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 14:46:17.067  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:17.068  5599  5647 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-04 14:46:17.068  5599  5647 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-04 14:46:17.068  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-04 14:46:17.068  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:17.069  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:46:17.069  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 14:46:17.069  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:46:17.070  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 14:46:17.072  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:46:17.072  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:46:17.073  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:46:17.073  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:46:17.073  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 14:46:17.073  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:46:17.073  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 14:46:17.073  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:46:17.073  5599  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:46:17.075  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:46:17.075  5599  5647 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:46:17.075  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 14:46:17.077  5599  5661 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:17.078  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 14:46:17.079  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:46:17.079  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:46:17.080  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.080  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-04 14:46:17.080  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 14:46:17.081  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
,11-04 14:46:17.081  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:46:17.081  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.081  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.075  4881  4881 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33200]" dev="sockfs" ino=33200 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 14:46:17.081  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.081  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.081  5599  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 14:46:17.082  5599  5647 D BluetoothAdapter: STATE_ON
11-04 14:46:17.084  4651  4663 D BtGatt.GattService: registerClient() - UUID=80d8b213-4355-4dbe-9285-ed6818d60a00
11-04 14:46:17.075  4881  4881 W Binder_5: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33200]" dev="sockfs" ino=33200 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:46:17.086  4651  4710 D BtGatt.GattService: onClientRegistered() - UUID=80d8b213-4355-4dbe-9285-ed6818d60a00, clientIf=5
,11-04 14:46:17.089  5599  5610 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-04 14:46:17.091  4651  4712 D BtGatt.AdvertiseManager: message : 0
,11-04 14:46:17.094  4651  4712 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:46:17.107  4651  4710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 14:46:17.116  4651  4710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 14:46:17.117  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:17.118  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.118  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:46:17.118  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:17.118  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.118  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.118  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:17.118  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.118  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 14:46:17.119  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-04 14:46:17.119  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.120  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.120  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:17.120  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.120  5599  5647 I io.jxcore.node.ConnectionHelper: start: OK
,11-04 14:46:17.120  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-04 14:46:17.121  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.121  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-04 14:46:17.121  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 14:46:17.121  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.121  5599  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:17.121  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 14:46:17.122  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:46:17.122  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 14:46:17.122  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.122  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.122  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-04 14:46:17.122  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.125  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.125  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:46:17.126  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.126  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-04 14:46:17.126  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.126  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:17.126  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 14:46:17.623  5599  5647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 14:46:17.624  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-04 14:46:17.624  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 14:46:17.624  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 14:46:17.624  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 14:46:17.624  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 14:46:17.624  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 14:46:17.624  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 14:46:17.624  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 14:46:17.624  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 14:46:17.625  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 14:46:17.625  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 14:46:17.625  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 14:46:17.625  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 14:46:17.625  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 14:46:17.625  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 14:46:17.625  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 14:46:17.625  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 14:46:17.626  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 14:46:17.627  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 14:46:17.627  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 14:46:17.627  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 14:46:17.627  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 14:46:17.627  5599  5647 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 14:46:17.627  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-04 14:46:17.627  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 14:46:17.627  5599  5599 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-04 14:46:17.628  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:46:17.628  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:46:17.628  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 14:46:17.628  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:46:17.628  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 14:46:17.628  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:46:17.629  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 14:46:17.629  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 14:46:17.629  5599  5661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
11-04 14:46:17.629  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 14:46:17.629  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 14:46:17.629  5599  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 14:46:17.629  5599  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:46:17.630  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.630  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.631  5599  5647 D BluetoothAdapter: STATE_ON
,11-04 14:46:17.632  5599  5647 D BluetoothLeScanner: could not find callback wrapper
11-04 14:46:17.632  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 14:46:17.632  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.632  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.632  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...,
11-04 14:46:17.633  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.634  4651  4712 D BtGatt.AdvertiseManager: message : 1
11-04 14:46:17.635  4651  4712 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 14:46:17.648  4651  4710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-04 14:46:17.648  4651  4710 D BtGatt.GattService: Client app is not null!
,11-04 14:46:17.649  4651  4881 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 14:46:17.650  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 14:46:17.650  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.651  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-04 14:46:17.651  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.651  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.651  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.651  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-04 14:46:17.651  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:46:17.651  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.651  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.652  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-04 14:46:17.652  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:17.655  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:17.655  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:17.655  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.655  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.655  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.655  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.656  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:17.656  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:46:17.656  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 14:46:17.657  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:46:17.657  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.658  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.658  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.658  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:17.659  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 14:46:17.659  5599  5599 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 14:46:17.660  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:46:17.660  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:46:17.660  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:46:17.660  5599  5647 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 14:46:17.660  5599  5647 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 14:46:17.660  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 14:46:17.661  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:46:17.661  5599  5647 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-04 14:46:17.661  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:17.661  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-04 14:46:17.661  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:17.661  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:46:17.662  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 14:46:17.662  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:46:17.663  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 14:46:17.663  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:46:17.663  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:46:17.663  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:46:17.664  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:46:17.664  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 14:46:17.664  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:46:17.664  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:46:17.664  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 14:46:17.669  5599  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:46:17.670  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:46:17.669  4881  4881 W Binder_5: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[29483]" dev="sockfs" ino=29483 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:46:17.670  5599  5647 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:46:17.670  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 14:46:17.670  5599  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:17.673  5599  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 14:46:17.669  4881  4881 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29483]" dev="sockfs" ino=29483 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:46:17.677  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:46:17.678  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:46:17.678  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:46:17.680  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.680  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 14:46:17.681  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:46:17.681  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-04 14:46:17.681  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:46:17.681  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.681  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.681  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.682  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.683  5599  5647 D BluetoothAdapter: STATE_ON
11-04 14:46:17.686  4651  4871 D BtGatt.GattService: registerClient() - UUID=5dd124f9-d6ca-4850-8aab-efb913a708b7
11-04 14:46:17.686  4651  4710 D BtGatt.GattService: onClientRegistered() - UUID=5dd124f9-d6ca-4850-8aab-efb913a708b7, clientIf=5
11-04 14:46:17.687  5599  5609 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-04 14:46:17.688  4651  4712 D BtGatt.AdvertiseManager: message : 0
11-04 14:46:17.691  4651  4712 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:46:17.703  4651  4710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
11-04 14:46:17.710  4651  4710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-04 14:46:17.710  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.711  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.711  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:46:17.711  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.711  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.711  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.711  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.711  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.711  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 14:46:17.714  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 14:46:17.714  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.715  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.716  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.716  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:17.716  5599  5647 I io.jxcore.node.ConnectionHelper: start: OK
11-04 14:46:17.716  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:17.716  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.716  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:17.716  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 14:46:17.717  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.717  5599  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:17.717  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.717  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:46:17.717  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 14:46:17.717  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.717  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.717  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-04 14:46:17.717  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.720  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.720  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:46:17.720  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.721  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.721  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:46:17.721  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:17.721  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 14:46:18.220  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-04 14:46:18.220  5599  5647 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 14:46:18.221  5599  5647 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 14:46:18.221  5599  5647 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 14:46:18.221  5599  5647 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,11-04 14:46:18.221  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-04 14:46:18.222  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-04 14:46:18.222  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-04 14:46:18.222  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-04 14:46:18.222  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-04 14:46:18.222  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-04 14:46:18.222  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-04 14:46:18.222  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-04 14:46:18.222  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-04 14:46:18.222  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-04 14:46:18.222  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.222  5599  5599 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-04 14:46:18.224  4651  4712 D BtGatt.AdvertiseManager: message : 1
,11-04 14:46:18.227  4651  4712 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 14:46:18.248  4651  4710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-04 14:46:18.249  4651  4710 D BtGatt.GattService: Client app is not null!
,11-04 14:46:18.250  4651  4871 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 14:46:18.250  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 14:46:18.251  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.251  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 14:46:18.251  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.251  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.251  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:46:18.251  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.251  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-04 14:46:18.251  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:46:18.251  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-04 14:46:18.252  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:46:18.252  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.252  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.252  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.252  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.253  5599  5647 D BluetoothAdapter: STATE_ON
,11-04 14:46:18.256  4651  4881 D BtGatt.GattService: registerClient() - UUID=783850b6-e8bd-474c-bed0-a9013ba8dec2
,11-04 14:46:18.256  4651  4710 D BtGatt.GattService: onClientRegistered() - UUID=783850b6-e8bd-474c-bed0-a9013ba8dec2, clientIf=5
11-04 14:46:18.257  5599  5609 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-04 14:46:18.258  4651  4712 D BtGatt.AdvertiseManager: message : 0
,11-04 14:46:18.260  4651  4712 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:46:18.270  4651  4710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 14:46:18.276  4651  4710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 14:46:18.277  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.277  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.277  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:46:18.277  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.277  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.277  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.277  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.277  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.277  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:46:18.277  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:46:18.278  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 14:46:18.278  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 14:46:18.278  5599  5647 I io.jxcore.node.ConnectionHelper: start: OK
11-04 14:46:18.278  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.278  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:18.278  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-04 14:46:18.279  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.279  5599  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:18.279  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.279  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:46:18.279  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:46:18.279  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.279  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.279  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-04 14:46:18.280  5599  5647 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 14:46:18.280  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-04 14:46:18.280  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-04 14:46:18.280  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:46:18.280  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:46:18.280  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 14:46:18.280  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:46:18.280  5599  5664 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 14:46:18.280  5599  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-04 14:46:18.280  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 14:46:18.280  5599  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:46:18.280  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:46:18.281  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-04 14:46:18.281  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 14:46:18.281  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 14:46:18.281  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:46:18.281  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 14:46:18.281  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 14:46:18.281  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:46:18.281  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.281  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.282  5599  5647 D BluetoothAdapter: STATE_ON
11-04 14:46:18.282  5599  5647 D BluetoothLeScanner: could not find callback wrapper
11-04 14:46:18.282  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 14:46:18.282  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.282  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.282  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-04 14:46:18.282  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.283  4651  4712 D BtGatt.AdvertiseManager: message : 1
11-04 14:46:18.284  4651  4712 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 14:46:18.290  4651  4710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-04 14:46:18.290  4651  4710 D BtGatt.GattService: Client app is not null!
11-04 14:46:18.291  4651  4871 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 14:46:18.291  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 14:46:18.291  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.291  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-04 14:46:18.291  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.292  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.292  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.292  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 14:46:18.292  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:46:18.292  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.292  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.292  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 14:46:18.292  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.293  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.293  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:18.293  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.293  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.293  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.293  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.294  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.294  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:46:18.294  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-04 14:46:18.294  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:46:18.294  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.296  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.296  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.296  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.297  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 14:46:18.297  5599  5599 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 14:46:18.297  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:46:18.297  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:46:18.297  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:18.298  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-04 14:46:18.299  5599  5647 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-04 14:46:18.300  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-04 14:46:18.300  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-04 14:46:18.301  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,11-04 14:46:18.301  5599  5647 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-04 14:46:18.302  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-04 14:46:18.302  5599  5647 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-04 14:46:18.302  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-04 14:46:18.302  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 14:46:18.303  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:46:18.303  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:46:18.303  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:46:18.303  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-04 14:46:18.303  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:46:18.303  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:46:18.303  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:46:18.303  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 14:46:18.303  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:46:18.303  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:46:18.303  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:46:18.304  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-04 14:46:18.304  5599  5647 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-04 14:46:18.305  5599  5647 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-04 14:46:18.309  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-04 14:46:18.310  5599  5647 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-04 14:46:18.312  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-04 14:46:18.313  5599  5647 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-04 14:46:18.313  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-04 14:46:18.314  5599  5647 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-04 14:46:18.314  5599  5647 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,11-04 14:46:18.314  5599  5647 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-04 14:46:18.314  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 14:46:18.315  5599  5647 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-04 14:46:18.316  5599  5647 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-04 14:46:18.316  5599  5647 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-04 14:46:18.316  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 14:46:18.316  5599  5647 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-04 14:46:18.316  5599  5647 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 14:46:18.316  5599  5647 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 14:46:18.316  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 14:46:18.316  5599  5647 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-04 14:46:18.318  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
,11-04 14:46:18.318  5599  5647 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 14:46:18.318  5599  5647 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 14:46:18.318  5599  5647 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-04 14:46:18.318  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-04 14:46:18.318  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:18.319  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:46:18.319  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 14:46:18.319  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:46:18.320  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 14:46:18.320  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:46:18.320  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:46:18.320  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:46:18.320  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:46:18.320  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:46:18.320  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 14:46:18.321  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:46:18.321  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 14:46:18.321  5599  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:46:18.321  5599  5668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:18.324  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:46:18.324  5599  5647 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:46:18.324  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 14:46:18.319  4662  4662 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32149]" dev="sockfs" ino=32149 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:46:18.325  5599  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 14:46:18.319  4662  4662 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32149]" dev="sockfs" ino=32149 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:46:18.328  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:46:18.329  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:46:18.329  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:46:18.331  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.331  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 14:46:18.332  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:46:18.332  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-04 14:46:18.332  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:46:18.332  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.332  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.332  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.332  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.333  5599  5647 D BluetoothAdapter: STATE_ON
11-04 14:46:18.336  4651  4881 D BtGatt.GattService: registerClient() - UUID=383490b5-130c-4ce2-b7b5-f14ee71c267c
11-04 14:46:18.337  4651  4710 D BtGatt.GattService: onClientRegistered() - UUID=383490b5-130c-4ce2-b7b5-f14ee71c267c, clientIf=5
11-04 14:46:18.337  5599  5639 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-04 14:46:18.338  4651  4712 D BtGatt.AdvertiseManager: message : 0
,11-04 14:46:18.339  4651  4712 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:46:18.348  4651  4710 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 14:46:18.353  4651  4710 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 14:46:18.354  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.354  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.354  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:46:18.354  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.354  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.354  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.354  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.354  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.354  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 14:46:18.355  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 14:46:18.356  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.357  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.357  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.357  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.357  5599  5647 I io.jxcore.node.ConnectionHelper: start: OK
11-04 14:46:18.357  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:18.357  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.357  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:18.357  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 14:46:18.357  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.357  5599  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:18.357  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.358  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-04 14:46:18.358  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 14:46:18.358  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.358  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.358  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-04 14:46:18.358  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 14:46:18.360  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 14:46:18.360  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:46:18.361  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.361  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.361  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:46:18.361  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:18.361  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 14:46:18.858  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 14:46:18.859  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:46:18.859  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:46:18.859  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-04 14:46:18.859  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:46:18.859  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 14:46:18.860  5599  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-04 14:46:18.860  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:46:18.860  5599  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 14:46:18.860  5599  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:46:18.860  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-04 14:46:18.860  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec0b04b removed from the list
11-04 14:46:18.860  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-04 14:46:18.861  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 14:46:18.861  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 14:46:18.861  5599  5599 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-04 14:46:18.861  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 14:46:18.861  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 14:46:18.861  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 14:46:18.861  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:46:18.863  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.863  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.865  5599  5647 D BluetoothAdapter: STATE_ON
11-04 14:46:18.866  5599  5647 D BluetoothLeScanner: could not find callback wrapper
,11-04 14:46:18.866  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 14:46:18.866  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.866  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.866  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 14:46:18.867  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.869  4651  4712 D BtGatt.AdvertiseManager: message : 1
,11-04 14:46:18.870  4651  4712 D BtGatt.AdvertiseManager: stop advertise for client 5
11-04 14:46:18.885  4651  4710 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-04 14:46:18.885  4651  4710 D BtGatt.GattService: Client app is not null!
11-04 14:46:18.886  4651  4880 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 14:46:18.887  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 14:46:18.887  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.887  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 14:46:18.887  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.887  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.888  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.888  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 14:46:18.888  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:46:18.888  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.888  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.888  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 14:46:18.888  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.890  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.891  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:18.891  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.891  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:18.891  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.891  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.891  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.891  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:46:18.892  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-04 14:46:18.893  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:46:18.893  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.894  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.895  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.895  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:18.895  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c41a28 removed from the list
11-04 14:46:18.895  5599  5647 D io.jxcore.node.ConnectivityMonitor: stop
11-04 14:46:18.895  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:46:18.895  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:46:18.896  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:46:18.896  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 14:46:19.397  5599  5599 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 14:46:23.900  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-04 14:46:23.902  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-04 14:46:23.902  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:46:23.904  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 14:46:23.907  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:46:23.907  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:46:23.907  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:46:23.907  5599  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:46:23.908  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:46:23.908  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 14:46:23.908  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:46:23.909  5599  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 14:46:23.910  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-04 14:46:23.909  4663  4663 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[33926]" dev="sockfs" ino=33926 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 14:46:23.912  5599  5647 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-04 14:46:23.912  5599  5647 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 14:46:23.913  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 14:46:23.913  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:46:23.913  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 14:46:23.915  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
11-04 14:46:23.918  5599  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-04 14:46:23.915  4663  4663 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[33926]" dev="sockfs" ino=33926 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 14:46:23.923  5599  5647 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-04 14:46:23.924  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 14:46:23.924  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-04 14:46:23.924  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:46:23.924  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 14:46:23.924  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:46:23.924  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 14:46:23.924  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:46:23.924  5599  5669 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 14:46:23.924  5599  5647 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec0b04b not in the list
,11-04 14:46:23.924  5599  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 14:46:23.924  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 14:46:23.924  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:46:23.924  5599  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:46:23.925  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 14:46:23.925  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 14:46:23.925  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 14:46:23.925  5599  5647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 14:46:23.925  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 14:46:23.925  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:46:23.925  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 14:46:23.925  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:23.926  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:23.926  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 14:46:23.926  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:23.927  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:23.927  5599  5647 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c41a28 not in the list
11-04 14:46:23.927  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:46:23.927  5599  5647 D io.jxcore.node.ConnectivityMonitor: stop
11-04 14:46:23.927  5599  5647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 14:46:23.927  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 14:46:23.927  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:46:23.927  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:23.928  5599  5647 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-04 14:46:23.929  5599  5647 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-04 14:46:23.929  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 14:46:23.929  5599  5647 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-04 14:46:23.929  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-04 14:46:23.929  5599  5647 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-04 14:46:23.929  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 14:46:23.930  5599  5647 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-04 14:46:23.931  5599  5647 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-04 14:46:23.932  5599  5647 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-04 14:46:23.933  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-04 14:46:23.933  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-04 14:46:23.934  5599  5647 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-04 14:46:23.934  5599  5647 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-04 14:46:23.934  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-04 14:46:23.935  5599  5647 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-04 14:46:23.935  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-04 14:46:23.935  5599  5647 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-04 14:46:23.935  5599  5647 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-04 14:46:23.936  5599  5647 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-04 14:46:23.936  5599  5647 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-04 14:46:23.936  5599  5647 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-04 14:46:23.937  5599  5647 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-04 14:46:23.937  5599  5647 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-04 14:46:23.937  5599  5647 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-04 14:46:23.937  5599  5647 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-04 14:46:23.937  5599  5647 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-04 14:46:23.938  5599  5647 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-04 14:46:23.938  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 14:46:23.938  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@465d58 added. We now have 3 listener(s)
,11-04 14:46:23.940  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 14:46:23.940  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 14:46:23.940  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 14:46:23.940  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 14:46:23.940  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@876beb1 added. We now have 3 listener(s)
11-04 14:46:23.940  5599  5647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 14:46:23.941  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 14:46:23.943  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:46:23.947  5599  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:46:23.947  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:23.947  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:23.947  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:23.947  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:23.947  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:23.947  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:23.947  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:46:23.948  5599  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:23.948  5599  5647 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 14:46:23.950  5599  5647 D BluetoothAdapter: enable(): BT is already enabled..!
,11-04 14:46:23.950   930  3402 D WifiService: setWifiEnabled: true pid=5599, uid=10077
11-04 14:46:23.950   930  3402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:23.951  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:23.952  5599  5647 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-04 14:46:23.954  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:23.954  5599  5647 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-04 14:46:23.955  5599  5647 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-04 14:46:23.958   930   941 D WifiService: setWifiEnabled: false pid=5599, uid=10077
,11-04 14:46:23.958   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:23.961   930  2933 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-04 14:46:23.961   930  2933 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 14:46:23.961   930  2933 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 14:46:23.961   930  2933 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:46:23.968   930  5371 D DhcpClient: Clearing IP address
,11-04 14:46:23.968   506   924 D CommandListener: Clearing all IP addresses on wlan0
,11-04 14:46:23.975   506   924 D CommandListener: Setting iface cfg
,11-04 14:46:23.977   930  5372 D DhcpClient: Receive thread stopped
,11-04 14:46:23.982  3560  5443 V NativeCrypto: Read error: ssl=0x7f890d9300: I/O error during system call, Connection timed out
,11-04 14:46:23.983  3560  5443 V NativeCrypto: SSL shutdown failed: ssl=0x7f890d9300: I/O error during system call, Broken pipe
,11-04 14:46:23.986   930   941 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-04 14:46:23.987   930  5369 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-04 14:46:23.987   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-04 14:46:23.987   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-04 14:46:23.989   532   532 E Parcel  : Reading a NULL string not supported here.
11-04 14:46:23.990   930  5369 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-04 14:46:23.993   930  2944 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-04 14:46:23.995  3707  3849 W QCNEJ   : |CORE| network lost: 100
,11-04 14:46:23.996   930   930 D RttService: SCAN_AVAILABLE : 1
11-04 14:46:23.997   930  3052 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 14:46:23.999  3707  3849 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-04 14:46:24.001   930   941 I ActivityManager: Killing 5056:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-04 14:46:24.019   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:46:24.022   930  2933 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-04 14:46:24.040   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:46:24.041   506   924 D TetherController: Setting IP forward enable = 0
,11-04 14:46:24.042   930  2944 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-04 14:46:24.042   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:46:24.047   930  2933 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 14:46:24.050   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-04 14:46:24.059  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:24.059  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:24.059  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:24.059  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:24.059  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:24.059  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:24.059  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:24.059  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:24.061  5256  5256 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ee7f26d and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-04 14:46:24.061  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:46:24.064  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:24.064  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:24.064  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:24.064  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:24.064  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:24.064  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:24.064  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:24.064  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:24.066  3926  3926 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-04 14:46:24.066  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:24.070  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:24.070  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:24.070  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:24.070  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:24.070  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:24.070  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:24.070  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:24.070  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:24.072  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:24.076  3939  3939 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 14:46:24.081  3939  3939 D SystemUpdateService: onCreate
,11-04 14:46:24.090  3939  3939 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 14:46:24.097  3939  5689 I SystemUpdateService: active receiver: enabled
,11-04 14:46:24.099  3939  3939 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 14:46:24.099  3560  5690 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-04 14:46:24.104  3939  4287 I iu.UploadsManager: num queued entries: 0
11-04 14:46:24.104  3939  4287 I iu.UploadsManager: num updated entries: 0
,11-04 14:46:24.107  3939  3939 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 14:46:24.110  3939  3939 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 14:46:24.113  5397  5397 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:46:24.118  5397  5397 D SprintDMHelper: simOperator: 
11-04 14:46:24.118  5397  5397 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 14:46:24.128  3939  5689 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 14:46:24.140  3560  5687 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-04 14:46:24.141  3939  4287 I iu.SyncManager: NEXT; no task
11-04 14:46:24.143  3560  5687 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-04 14:46:24.144  3939  5689 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 14:46:24.144  3939  5689 I SystemUpdateService: now status is 0 (complete)
,11-04 14:46:24.146  3939  5689 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 14:46:24.146  3939  5689 I SystemUpdateService: file has been verified
,11-04 14:46:24.147  3939  5689 I SystemUpdateService: OTA package size = 21989297
,11-04 14:46:24.152  3939  5689 I SystemUpdateService: showing system update notification
,11-04 14:46:24.161   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 14:46:24.163  3939  3939 D SystemUpdateService: onDestroy
,11-04 14:46:24.171  3560  5687 W Uploader:  no longer exists, so no auth token.
,11-04 14:46:24.177  3560  5690 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-04 14:46:24.429  5599  5599 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 14:46:24.463   930  3884 D WifiService: setWifiEnabled: false pid=5599, uid=10077
,11-04 14:46:24.463   930  3884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:24.967   930  3884 D WifiService: setWifiEnabled: false pid=5599, uid=10077
,11-04 14:46:24.967   930  3884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:25.151   506   924 E Netd    : netlink response contains error (No such file or directory)
,11-04 14:46:25.153   930  2944 E NetdConnector: NDC Command {106 network destroy 100} took too long (1104ms)
11-04 14:46:25.153   930  2944 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-04 14:46:25.154   930  2944 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 14:46:25.154   506   924 D CommandListener: Clearing all IP addresses on wlan0
,11-04 14:46:25.155  3560  5687 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
11-04 14:46:25.156   930  2933 E NetdConnector: NDC Command {107 interface clearaddrs wlan0} took too long (1106ms)
11-04 14:46:25.157   930  2931 E NetdConnector: NDC Command {108 bandwidth setglobalalert 2097152} took too long (1101ms)
,11-04 14:46:25.158   506   924 D TetherController: Setting IP forward enable = 0
11-04 14:46:25.161   930  2933 D DhcpClient: doQuit
11-04 14:46:25.163   930  2933 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 14:46:25.164   930  5371 D DhcpClient: onQuitting
,11-04 14:46:25.166  3436  3436 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-04 14:46:25.179  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:25.179  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:25.179  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:25.179  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:46:25.179  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:25.179  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:25.179  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:25.179  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:25.180  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:25.184  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:25.184  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:25.184  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:25.184  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:46:25.184  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:25.184  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:25.184  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:25.184  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:25.186  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:25.190  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:25.190  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:25.190  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:25.190  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:46:25.190  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:25.190  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:25.190  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:25.190  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:25.191  3436  3436 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 14:46:25.193  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:25.198  3436  3436 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-04 14:46:25.199   930   943 I ActivityManager: Start proc 5703:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-04 14:46:25.244  5703  5703 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-04 14:46:25.249  3436  3436 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 14:46:25.251   930   940 I ActivityManager: Killing 5256:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-04 14:46:25.252  3436  3436 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 14:46:25.355   930  2933 D wifi    : In wifi stop Hal
,11-04 14:46:25.355   930  2933 D wifi    : halHandle = 0x7f87730300, mVM = 0x7fa3d4d140, mCls = 0x100a02
11-04 14:46:25.355  5019  5019 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 14:46:25.356   930  3435 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 14:46:25.356   930  3435 D WifiHAL : Got a signal to exit!!!
11-04 14:46:25.356   930  3435 I WifiHAL : Exit wifi_event_loop
,11-04 14:46:25.357   930  2933 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-04 14:46:25.357   930  2933 E WifiHAL : Event processing terminated
11-04 14:46:25.358   930  2933 D wifi    : In wifi cleaned up handler
11-04 14:46:25.358   930  2933 I WifiHAL : Internal cleanup completed
,11-04 14:46:25.360  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:25.364  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:25.365  4071  4195 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 14:46:25.368  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:25.388   930  3435 D wifi    : set interface wlan0 flags (DOWN)
,11-04 14:46:25.388   930  2933 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 14:46:25.470  5599  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:25.472   930   941 D WifiService: setWifiEnabled: true pid=5599, uid=10077
,11-04 14:46:25.472   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:25.591   930   947 D Tethering: InitialState.processMessage what=4
,11-04 14:46:25.594   506   924 D SoftapController: Softap fwReload - Ok
,11-04 14:46:25.598   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 14:46:25.598   506   924 D CommandListener: Setting iface cfg
,11-04 14:46:25.599   506   924 D CommandListener: Trying to bring down wlan0
11-04 14:46:25.600   506   924 D CommandListener: Clearing all IP addresses on wlan0
,11-04 14:46:25.604   930  2933 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 14:46:25.976   930  3179 D WifiService: setWifiEnabled: true pid=5599, uid=10077
11-04 14:46:25.978   930  3179 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:26.214   930  2933 D wifi    : set interface wlan0 flags (UP)
,11-04 14:46:26.214   930  2933 I WifiHAL : Initializing wifi
,11-04 14:46:26.215   930  2933 I WifiHAL : Creating socket
,11-04 14:46:26.221   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 14:46:26.226   930  2933 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-04 14:46:26.227   930  2933 D wifi    : Did set static halHandle = 0x7f87730300
11-04 14:46:26.227   930  2933 D wifi    : halHandle = 0x7f87730300, mVM = 0x7fa3d4d140, mCls = 0x2019aa
11-04 14:46:26.227   930  2933 D wifi    : array field set
11-04 14:46:26.227   930  2933 I WifiNative-HAL: interface[0] = wlan0
11-04 14:46:26.229   930  5717 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547733308160
11-04 14:46:26.229   930  5717 D wifi    : waitForHalEvents called, vm = 0x7fa3d4d140, obj = 0x2019aa, env = 0x7f8bf71500
,11-04 14:46:26.301  5718  5718 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 14:46:26.330   930  2933 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 14:46:26.340  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:26.343  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:26.345  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:26.370  5718  5718 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 14:46:26.375  5718  5718 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 14:46:26.375  5718  5718 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 14:46:26.386   930  2933 D WifiConfigStore: Loading config and enabling all networks 
,11-04 14:46:26.392  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:26.392  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:26.392  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:26.392  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:26.392  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:26.392  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:26.392  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:26.392  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:26.394  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:26.397  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:26.397  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:26.397  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:26.397  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:26.397  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:26.397  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:26.397  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:26.397  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:26.400   930  2933 D WifiConfigStore: loaded 0 passpoint configs
,11-04 14:46:26.400  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:26.400   930  2933 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-04 14:46:26.401   930  2933 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 14:46:26.401   930  2933 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-04 14:46:26.401   930  2933 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-04 14:46:26.401   930  2933 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-04 14:46:26.402   930  2933 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-04 14:46:26.402   930  2933 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 14:46:26.402   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 14:46:26.402   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 14:46:26.402   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-04 14:46:26.402   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 14:46:26.402   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
11-04 14:46:26.403  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:26.403  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:26.403  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:26.403  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:26.403  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:26.403  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:26.403  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:26.403  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:26.404   930  2933 D WifiNative-HAL: Setting external_sim to 1
11-04 14:46:26.404   930  2933 D wifi    : setting dfs flag to true, 0x7f8c17fb00
11-04 14:46:26.404   930  2933 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 14:46:26.404   930  2933 D wifi    : setting scan oui 0x7f8c17fb00
11-04 14:46:26.404   930  2933 D WifiHAL : Sending mac address OUI
11-04 14:46:26.406  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:46:26.407   930  2933 E native  : do suspend false
11-04 14:46:26.407  5019  5019 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 14:46:26.413   930  2933 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-04 14:46:26.414   930   930 D RttService: SCAN_AVAILABLE : 3
11-04 14:46:26.414   930  3052 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-04 14:46:26.417   506   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 14:46:26.419   506   924 D CommandListener: Setting iface cfg
11-04 14:46:26.422   930  2932 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
11-04 14:46:26.422   930  2932 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
11-04 14:46:26.427   930  2932 D WifiNative-HAL: p2pGetDeviceAddress
11-04 14:46:26.428   930  2932 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
11-04 14:46:26.432   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=107074 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-04 14:46:26.481  5599  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.486  4651  4706 D BluetoothAdapterState: Current state: ON, message: 23
11-04 14:46:26.486  4651  4706 D BluetoothAdapterProperties: Setting state to 13
11-04 14:46:26.486  4651  4706 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 14:46:26.487  4651  4706 D BluetoothAdapterProperties: onBluetoothDisable()
,11-04 14:46:26.488  4651  4651 D BluetoothMapService: onReceive
,11-04 14:46:26.488  4651  4651 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 14:46:26.488  4651  4651 D BluetoothMapService: STATE_TURNING_OFF
11-04 14:46:26.489  4651  4651 D BluetoothMapService: MAP Service closeService in
11-04 14:46:26.489  4651  4651 D BluetoothMapMasInstance0: MAP Service shutdown
,11-04 14:46:26.489  4651  4651 D ObexServerSockets0: shutdown(block = true)
11-04 14:46:26.490  4651  4651 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-04 14:46:26.490  4651  4883 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-04 14:46:26.490  4651  4651 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 14:46:26.490  4651  4864 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 14:46:26.490  4651  4706 I BluetoothAdapterState: Entering PendingCommandState
11-04 14:46:26.491  4651  4884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 14:46:26.492  4651  4651 I BtOppRfcommListener: stopping Accept Thread
11-04 14:46:26.493  4651  5302 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 14:46:26.493  4651  5302 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-04 14:46:26.496  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:26.496  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:26.496  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:26.496  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:26.496  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:26.496  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:46:26.496  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:26.496  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:26.496  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:26.497  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:26.497  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:26.499  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:26.500  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:26.500  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:26.500  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:26.500  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:26.500  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:46:26.500  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:26.500  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:26.500  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:26.500  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:26.500  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:46:26.503  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:26.503  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:26.503  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:26.503  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:26.503  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:26.503  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:46:26.503  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:26.503  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:26.503  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:26.504  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:26.504  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:46:26.506   930   943 I ActivityManager: Start proc 5722:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-04 14:46:26.507  4651  4710 D BluetoothAdapterProperties: Scan Mode:20
11-04 14:46:26.507  4651  4706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 14:46:26.509  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.511  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.512  4651  4651 D HeadsetService: Received stop request...Stopping profile...
11-04 14:46:26.513  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.513  3116  3347 D BluetoothHeadset: Proxy object disconnected
11-04 14:46:26.514  3733  3956 D BluetoothHeadset: Proxy object disconnected
11-04 14:46:26.514   930   930 D BluetoothHeadset: Proxy object disconnected
11-04 14:46:26.514   930   930 D BluetoothHeadset: Proxy object disconnected
11-04 14:46:26.514   930   930 D BluetoothHeadset: Proxy object disconnected
11-04 14:46:26.514  3116  3116 D HeadsetProfile: Bluetooth service disconnected
11-04 14:46:26.515  4651  4651 D A2dpService: Received stop request...Stopping profile...
11-04 14:46:26.515  4651  4875 D A2dpStateMachine: Exit Disconnected: -1
11-04 14:46:26.517   930   930 D BluetoothA2dp: Proxy object disconnected
11-04 14:46:26.518  4651  4651 D HidService: Received stop request...Stopping profile...
11-04 14:46:26.518  4651  4651 D HidService: Stopping Bluetooth HidService
11-04 14:46:26.520  4651  4651 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:26.520  4651  4651 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:26.520  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:26.520  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:26.520  3116  3116 D BluetoothA2dp: Proxy object disconnected
11-04 14:46:26.520  3116  3116 D BluetoothInputDevice: Proxy object disconnected
11-04 14:46:26.521  3116  3116 D HidProfile: Bluetooth service disconnected
11-04 14:46:26.522  4651  4651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 14:46:26.522  4651  4651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 14:46:26.523  4651  4856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:26.523  4651  4856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:26.523  4651  4856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:26.523  4651  4710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 14:46:26.523  4651  4710 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 14:46:26.523  4651  4651 D HealthService: Received stop request...Stopping profile...
11-04 14:46:26.524  4651  4651 D PanService: Received stop request...Stopping profile...
11-04 14:46:26.525  3116  3116 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 14:46:26.525  3116  3116 D PanProfile: Bluetooth service disconnected
11-04 14:46:26.525  4651  4651 D BluetoothMapService: Received stop request...Stopping profile...
11-04 14:46:26.526  4651  4651 D BluetoothMapService: stop()
11-04 14:46:26.526  4651  4651 D BluetoothMapAppObserver: deinitObservers()
11-04 14:46:26.526  4651  4651 D BluetoothMapAppObserver: removeReceiver()
11-04 14:46:26.527  3116  3116 D BluetoothMap: Proxy object disconnected
11-04 14:46:26.528  3116  3116 D MapProfile: Bluetooth service disconnected
11-04 14:46:26.528  4651  4651 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:26.528  4651  4651 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:26.528  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:26.528  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:26.531  4651  4856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:26.531  4651  4856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:26.531  4651  4710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 14:46:26.531  4651  4856 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 14:46:26.531  4651  4651 D SapService: Received stop request...Stopping profile...
11-04 14:46:26.531  4651  4856 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 14:46:26.531  4651  4651 V SapService: stop()
11-04 14:46:26.531  4651  4856 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 14:46:26.531  4651  4856 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 14:46:26.532  4651  4651 V BluetoothAdapterState: isTurningOff()=true
,11-04 14:46:26.533  4651  4651 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:26.533  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:26.533  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:26.533  4651  4651 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 14:46:26.533  4651  4651 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 14:46:26.533  4651  4710 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 14:46:26.533  4651  4651 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:26.534  4651  4651 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:26.534  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:26.534  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:26.535  4651  4651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 14:46:26.535  4651  4710 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 14:46:26.535  4651  4651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 14:46:26.535  4651  4651 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:26.535  4651  4651 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:26.535  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:26.536  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:26.536  4651  4651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 14:46:26.536  4651  4651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 14:46:26.540  4651  4651 D BluetoothMapService: MAP Service closeService in
11-04 14:46:26.540  4651  4651 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:26.540  4651  4651 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:26.540  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:26.540  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:26.540  4651  4651 D BluetoothMapService: cleanup()
11-04 14:46:26.540  4651  4651 D BluetoothMapService: MAP Service closeService in
11-04 14:46:26.540  4651  4651 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:26.540  4651  4651 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:26.541  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:26.541  4651  4651 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:26.541  4651  4706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 14:46:26.541  4651  4706 D BluetoothAdapterProperties: Setting state to 15
11-04 14:46:26.541  4651  4706 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 14:46:26.542  4651  4706 I BluetoothAdapterState: Entering BleOnState
11-04 14:46:26.542  3116  3130 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 14:46:26.543   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:26.543  3733  3753 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:26.544  3116  3958 D BluetoothPan: onBluetoothStateChange on: false
11-04 14:46:26.544   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 14:46:26.545  3116  3347 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 14:46:26.546  3116  3127 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:26.546   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:26.546  3116  3130 D BluetoothMap: onBluetoothStateChange: up=false
11-04 14:46:26.547   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:26.547  3116  3958 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 14:46:26.548  4651  4706 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 14:46:26.548  4651  4706 D BluetoothAdapterProperties: Setting state to 16
11-04 14:46:26.548  4651  4706 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 14:46:26.549  4651  4706 D BluetoothAdapterProperties: onBleDisable
11-04 14:46:26.549  4651  4706 I BluetoothAdapterState: Entering PendingCommandState
11-04 14:46:26.550  4651  4707 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 14:46:26.552  4651  4856 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 14:46:26.552  4651  4856 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:26.552  4651  4710 D BluetoothAdapterProperties: Scan Mode:20
11-04 14:46:26.552  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.552  5722  5722 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-04 14:46:26.553  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.555  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.557  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.558  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.559  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:26.567  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 14:46:26.574   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5f352eb:true
11-04 14:46:26.575  3560  3560 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:46:26.588   930  3402 I ActivityManager: Start proc 5734:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-04 14:46:26.596  5722  5722 D LocalBluetoothProfileManager: Adding local MAP profile
,11-04 14:46:26.600  5722  5722 D BluetoothMap: Create BluetoothMap proxy object
,11-04 14:46:26.614  5722  5722 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-04 14:46:26.621  5734  5734 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-04 14:46:26.631  5722  5722 D DockEventReceiver: finishStartingService: stopping service
,11-04 14:46:26.635   930   941 I ActivityManager: Killing 3857:com.android.providers.calendar/u0a1 (adj 15): empty #17,
,11-04 14:46:26.759  4651  4710 I bt_hci  : shut_down
,11-04 14:46:26.765  4651  4714 D bt_hwcfg: hw_epilog_process
,11-04 14:46:26.765  4651  4714 I bt_vendor: low_power_mode_cb
11-04 14:46:26.767  4651  4714 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-04 14:46:26.767  4651  4714 I bt_vendor: epilog_cb
11-04 14:46:26.767  4651  4714 I bt_hci  : epilog_finished_callback
11-04 14:46:26.771  4651  4710 I bt_hci_h4: hal_close
11-04 14:46:26.772  4651  4710 I bt_userial_vendor: device fd = 54 close
,11-04 14:46:26.835  5734  5734 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:46:26.835  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:46:26.836  5734  5734 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:46:26.836  5734  5734 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:46:26.836  5734  5734 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:46:26.836  5734  5734 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.k.d(PG:583)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:46:26.836  5734  5734 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:46:26.836  5734  5734 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:46:26.836  5734  5734 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:46:26.836  5734  5734 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:46:26.840  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 14:46:26.846  3560  3560 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 14:46:26.851  5722  5722 D DockEventReceiver: finishStartingService: stopping service
11-04 14:46:26.867   930  3179 I ActivityManager: Killing 5148:com.google.android.youtube/u0a75 (adj 15): empty #17
11-04 14:46:26.876  4651  4707 D bt_stack_manager: event_shut_down_stack finished.
11-04 14:46:26.877  4651  4706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 14:46:26.921  4651  4651 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 14:46:26.921  4651  4706 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-04 14:46:26.922  4651  4651 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 14:46:26.922  4651  4651 D BtGatt.GattService: stop()
11-04 14:46:26.922  4651  4651 D BtGatt.AdvertiseManager: advertise clients cleared
,11-04 14:46:26.924  4651  4651 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:46:26.925  4651  4651 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:26.925  4651  4651 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:26.925  4651  4651 V BluetoothAdapterState: isBleTurningOff()=true
11-04 14:46:26.925  4651  4706 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-04 14:46:26.925  4651  4706 D BluetoothAdapterProperties: Setting state to 10
11-04 14:46:26.925  4651  4706 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 14:46:26.926  4651  4706 I BluetoothAdapterState: Entering OffState
,11-04 14:46:26.927   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-04 14:46:26.933  4651  4651 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 14:46:26.933  4651  4651 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-04 14:46:26.933  4651  4651 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-04 14:46:26.935  4651  4707 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 14:46:26.940  4651  4651 I art     : System.exit called, status: 0
,11-04 14:46:26.940  4651  4651 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 14:46:26.986  5599  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:26.988   930   947 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,11-04 14:46:26.988   380   380 E lowmemorykiller: Error writing /proc/4651/oom_score_adj; errno=22
11-04 14:46:26.989   930   947 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
11-04 14:46:26.989   930   947 W ActivityManager: Application dead when creating service ServiceRecord{96bfc53 u0 com.android.bluetooth/.btservice.AdapterService}
,11-04 14:46:26.995   930   947 I ActivityManager: Process com.android.bluetooth (pid 4651) has died
,11-04 14:46:26.996   930   947 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,11-04 14:46:26.997   930   947 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
,11-04 14:46:26.997   930   947 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
11-04 14:46:26.997   930   947 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-04 14:46:26.997   930   947 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
11-04 14:46:26.997   930   947 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
11-04 14:46:26.997   930   947 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
11-04 14:46:26.997   930   947 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
11-04 14:46:26.997   930   947 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
11-04 14:46:26.997   930   947 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
11-04 14:46:26.997   930   947 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
11-04 14:46:26.997   930   947 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
11-04 14:46:26.997   930   947 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
11-04 14:46:26.997   930   947 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
11-04 14:46:26.997   930   947 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
11-04 14:46:26.997   930   947 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
11-04 14:46:26.997   930   947 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
11-04 14:46:26.997   930   947 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:46:26.997   930   947 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:46:26.997   930   947 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 14:46:26.997   930   947 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-04 14:46:26.998   930   941 W ActivityManager: Spurious death for ProcessRecord{f8f7b49 0:com.android.bluetooth/1002}, curProc for 4651: null
,11-04 14:46:27.113  5734  5752 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-04 14:46:27.122   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9768289:true
,11-04 14:46:29.484  5718  5718 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 14:46:29.489  5718  5718 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 14:46:29.494  5718  5718 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 14:46:29.547   930  2933 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 14:46:29.549   930  2933 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-04 14:46:29.549   930  2933 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:46:29.563   930  2933 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 14:46:29.598   930  2933 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 14:46:29.604  5718  5718 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 14:46:29.987   930   947 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,11-04 14:46:30.031  5718  5718 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 14:46:30.033   930   947 I ActivityManager: Start proc 5768:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 14:46:30.063  5718  5718 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 14:46:30.065  5718  5718 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 14:46:30.071   930  2933 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-04 14:46:30.072   930  2933 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:46:30.072   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 14:46:30.083   930  2933 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:46:30.095   506   924 D CommandListener: Setting iface cfg
,11-04 14:46:30.099   930  2933 D WifiStateMachine: Start Dhcp Watchdog 2
,11-04 14:46:30.107   930  2933 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 14:46:30.108   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 14:46:30.108   930  5783 D DhcpClient: Receive thread started
11-04 14:46:30.108   930  2944 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-04 14:46:30.111  5768  5768 D AdapterServiceConfig: Adding HeadsetService
,11-04 14:46:30.111  5768  5768 D AdapterServiceConfig: Adding A2dpService
11-04 14:46:30.111  5768  5768 D AdapterServiceConfig: Adding HidService
11-04 14:46:30.111  5768  5768 D AdapterServiceConfig: Adding HealthService
11-04 14:46:30.111  5768  5768 D AdapterServiceConfig: Adding PanService
11-04 14:46:30.111  5768  5768 D AdapterServiceConfig: Adding GattService
,11-04 14:46:30.112  5768  5768 D AdapterServiceConfig: Adding BluetoothMapService
11-04 14:46:30.112  5768  5768 D AdapterServiceConfig: Adding SapService
,11-04 14:46:30.121   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28bb77f:true
,11-04 14:46:30.122  5768  5768 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 14:46:30.125  5768  5768 I bt_bluedroid: init
11-04 14:46:30.125  5768  5784 I BluetoothAdapterState: Entering OffState
,11-04 14:46:30.127  5768  5785 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 14:46:30.127  5768  5785 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-04 14:46:30.127  5768  5785 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 14:46:30.127  5768  5785 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 14:46:30.127  5768  5768 I bt_bluedroid: get_profile_interface socket
,11-04 14:46:30.129  5768  5768 I bt_bluedroid: get_profile_interface sdp
11-04 14:46:30.129  5768  5788 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 14:46:30.130  5768  5788 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 14:46:30.133  5768  5779 I bt_bluedroid: config_hci_snoop_log
,11-04 14:46:30.134   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 14:46:30.137  5768  5784 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 14:46:30.137  5768  5784 D BluetoothAdapterProperties: Setting state to 14
11-04 14:46:30.137  5768  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-04 14:46:30.138  5768  5784 D BluetoothBondStateMachine: make
,11-04 14:46:30.140  5768  5789 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 14:46:30.142  5768  5784 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:46:30.143  5768  5768 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 14:46:30.144  5768  5768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
11-04 14:46:30.145  5768  5768 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 14:46:30.145  5768  5768 D BtGatt.GattService: Received start request. Starting profile...
11-04 14:46:30.145  5768  5768 D BtGatt.GattService: start()
11-04 14:46:30.145  5768  5768 I bt_bluedroid: get_profile_interface gatt
,11-04 14:46:30.146  5768  5768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
11-04 14:46:30.146  5768  5768 D BtGatt.AdvertiseManager: advertise manager created
,11-04 14:46:30.150  5768  5768 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:46:30.150  5768  5768 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:30.150  5768  5768 V BluetoothAdapterState: isBleTurningOn()=true
11-04 14:46:30.150  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:30.150  5768  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 14:46:30.151  5768  5784 I bt_bluedroid: bt_bluedroid
,11-04 14:46:30.151  5768  5785 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-04 14:46:30.151  5768  5785 I bt_hci  : start_up
,11-04 14:46:30.156  5768  5785 I bt_vendor: alloc value 0xf410d871
11-04 14:46:30.156  5768  5785 I bt_vendor: init
11-04 14:46:30.156  5768  5785 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 14:46:30.156  5768  5785 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 14:46:30.187   930  2933 E native  : do suspend false
,11-04 14:46:30.194   930  5782 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 14:46:30.208   930  5783 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172730, domain null
,11-04 14:46:30.209   930  5782 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172730 seconds
,11-04 14:46:30.209   930  5782 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 14:46:30.220   930  5783 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 14:46:30.221   930  5782 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 14:46:30.222   506   924 D CommandListener: Setting iface cfg
,11-04 14:46:30.224   930  2933 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 14:46:30.225   930  5782 D DhcpClient: Scheduling renewal in 86399s
,11-04 14:46:30.231   930  2933 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 14:46:30.231   930  2933 D WifiConfigStore: No blacklist allowed without epno enabled
11-04 14:46:30.231   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 14:46:30.232   930  2933 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-04 14:46:30.236   930  2944 D ConnectivityService: Adding iface wlan0 to network 101
,11-04 14:46:30.265  5768  5785 D bt_hci  : start_up starting async portion
,11-04 14:46:30.265  5768  5792 I bt_hci  : event_finish_startup
11-04 14:46:30.265  5768  5792 I bt_hci_h4: hal_open
11-04 14:46:30.265  5768  5792 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-04 14:46:30.262  5796  5796 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-04 14:46:30.269  5768  5792 I bt_userial_vendor: device fd = 54 open
,11-04 14:46:30.269   930  2944 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-04 14:46:30.269   930  2944 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-04 14:46:30.272   930  2944 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-04 14:46:30.273   930  2944 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-04 14:46:30.274   930  2944 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-04 14:46:30.279   930  2944 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 14:46:30.282  5768  5792 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 14:46:30.283   930  2944 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-04 14:46:30.283   930  2944 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-04 14:46:30.283   930  2944 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-04 14:46:30.283   930  2933 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 14:46:30.283   930  2944 D ConnectivityService:    accepting network in place of null
11-04 14:46:30.283   930  2933 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 14:46:30.283   930  2944 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-04 14:46:30.284  5768  5792 D bt_hwcfg: Chipset BCM4358A3
11-04 14:46:30.284  5768  5792 D bt_hwcfg: Target name = [BCM4358A3]
11-04 14:46:30.284  5768  5792 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 14:46:30.292   930  5781 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110933, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 14:46:30.303   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:46:30.322   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:46:30.325   930  2944 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-04 14:46:30.325  3707  3849 W QCNEJ   : |CORE| network available: 101
11-04 14:46:30.325   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:46:30.326  3707  3849 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 14:46:30.327  3707  3849 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 14:46:30.328  3707  3849 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-04 14:46:30.328   930  2944 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-04 14:46:30.329   930   947 D Tethering: MasterInitialState.processMessage what=3
11-04 14:46:30.332  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:30.332  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:30.332  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:30.332  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:30.332  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:30.332  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:46:30.332  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:30.332  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:30.332  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:30.333  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:30.333  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:30.336  3926  3926 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-04 14:46:30.337  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:30.337  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:30.337  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:30.337  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:30.337  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:30.337  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:46:30.337  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:30.337  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:30.337  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:30.338  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:30.338  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:30.341  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:30.341  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:30.341  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:30.341  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:30.341  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:30.341  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:46:30.341  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:30.341  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:30.341  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:30.341  3939  3939 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-04 14:46:30.342  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:30.342  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:30.345  3939  3939 D SystemUpdateService: onCreate
,11-04 14:46:30.350  3939  3939 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 14:46:30.361  3939  3939 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 14:46:30.364   930  5780 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 14:46:30.369  3939  4287 I iu.UploadsManager: num queued entries: 0
11-04 14:46:30.369  3939  4287 I iu.UploadsManager: num updated entries: 0
11-04 14:46:30.370  3939  4287 I iu.SyncManager: NEXT; no task
,11-04 14:46:30.372  3939  5805 I SystemUpdateService: active receiver: enabled
,11-04 14:46:30.375  3939  3939 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 14:46:30.377  3939  3939 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 14:46:30.378  5397  5397 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:46:30.383  5397  5397 D SprintDMHelper: simOperator: 
,11-04 14:46:30.383  5397  5397 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 14:46:30.407   930  5780 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 13:46:30 GMT], X-Android-Received-Millis=[1478267190407], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478267190385]}
11-04 14:46:30.408   930  2944 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 14:46:30.408   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-04 14:46:30.408   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 14:46:30.409   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 14:46:30.411  3939  5805 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 14:46:30.417  3939  5805 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 14:46:30.417  3939  5805 I SystemUpdateService: now status is 0 (complete)
11-04 14:46:30.417  3939  5805 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 14:46:30.417  3939  5805 I SystemUpdateService: file has been verified
11-04 14:46:30.417  3939  5805 I SystemUpdateService: OTA package size = 21989297
,11-04 14:46:30.423  3939  5805 I SystemUpdateService: showing system update notification
,11-04 14:46:30.431   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 14:46:30.432  3939  3939 D SystemUpdateService: onDestroy
,11-04 14:46:30.504  5768  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-04 14:46:30.596  5768  5792 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 14:46:30.596  5768  5792 D bt_hwcfg: Settlement delay -- 100 ms
11-04 14:46:30.597  5768  5792 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 14:46:30.721  5768  5792 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 14:46:30.722  5768  5792 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-04 14:46:30.723  5768  5792 I bt_hwcfg: vendor lib fwcfg completed
,11-04 14:46:30.723  5768  5792 I bt_vendor: firmware callback
,11-04 14:46:30.723  5768  5792 I bt_hci  : firmware_config_callback
,11-04 14:46:30.732  5768  5813 I bt_btu  : btu_task pending for preload complete event
,11-04 14:46:30.732  5768  5813 I bt_btu_task: Bluetooth chip preload is complete
11-04 14:46:30.732  5768  5813 I bt_btu  : btu_task received preload complete event
,11-04 14:46:30.739  5768  5813 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 14:46:30.739  5768  5813 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 14:46:30.739  5768  5813 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 14:46:30.739  5768  5813 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 14:46:30.739  5768  5813 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-04 14:46:30.739  5768  5813 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 14:46:30.740  5768  5813 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 14:46:30.740  5768  5813 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 14:46:30.740  5768  5813 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 14:46:30.740  5768  5813 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 14:46:30.740  5768  5813 I         : BTE_InitTraceLevels -- TRC_SDP
,11-04 14:46:30.740  5768  5813 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 14:46:30.740  5768  5813 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 14:46:30.740  5768  5813 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 14:46:30.741  5768  5813 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 14:46:30.822  5768  5813 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf408b549
,11-04 14:46:30.822  5768  5813 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf408b549 
,11-04 14:46:30.837  5768  5788 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 14:46:30.838  5768  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 14:46:30.839  5768  5788 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 14:46:30.842  5768  5788 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 14:46:30.845  5768  5788 D BluetoothAdapterProperties: Scan Mode:20
11-04 14:46:30.846  5768  5788 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 14:46:30.846  5768  5788 D bt_hci  : do_postload posting postload work item
11-04 14:46:30.846  5768  5792 I bt_hci  : event_postload
11-04 14:46:30.846  5768  5792 I bt_vendor: sco_config_cb
11-04 14:46:30.847  5768  5792 I bt_hci  : sco_config_callback postload finished.
,11-04 14:46:30.852  5768  5788 D bt_bte_conf: Device ID record 1 : primary
,11-04 14:46:30.853  5768  5788 D bt_bte_conf:   vendorId            = 000f
11-04 14:46:30.853  5768  5788 D bt_bte_conf:   vendorIdSource      = 0001
11-04 14:46:30.853  5768  5788 D bt_bte_conf:   product             = 1200
11-04 14:46:30.853  5768  5788 D bt_bte_conf:   version             = 1436
,11-04 14:46:30.853  5768  5788 D bt_bte_conf:   clientExecutableURL = 
11-04 14:46:30.853  5768  5788 D bt_bte_conf:   serviceDescription  = 
11-04 14:46:30.853  5768  5788 D bt_bte_conf:   documentationURL    = 
11-04 14:46:30.854  5768  5788 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 14:46:30.854  5768  5785 D bt_stack_manager: event_start_up_stack finished
,11-04 14:46:30.856  5768  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-04 14:46:30.856  5768  5784 D BluetoothAdapterProperties: Setting state to 15
11-04 14:46:30.857  5768  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 14:46:30.857  5768  5792 I bt_vendor: low_power_mode_cb
11-04 14:46:30.859  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:30.864  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:30.865  5768  5784 I BluetoothAdapterState: Entering BleOnState
11-04 14:46:30.866  5768  5784 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-04 14:46:30.866  5768  5784 D BluetoothAdapterProperties: Setting state to 11
11-04 14:46:30.866  5768  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-04 14:46:30.868  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:30.875  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:30.878  5768  5768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
11-04 14:46:30.879  5768  5768 D HeadsetService: Received start request. Starting profile...
11-04 14:46:30.879  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:30.881  5768  5768 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 14:46:30.882  5768  5768 D HeadsetStateMachine: make
,11-04 14:46:30.882  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:30.892  5768  5768 D HeadsetStateMachine: max_hf_connections = 1
,11-04 14:46:30.892  5768  5768 I bt_bluedroid: get_profile_interface handsfree
11-04 14:46:30.892  5768  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 14:46:30.892  5768  5788 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-04 14:46:30.896  5768  5768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:30.897  5768  5768 D A2dpService: Received start request. Starting profile...
11-04 14:46:30.897  5768  5784 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:46:30.898  5768  5768 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 14:46:30.898  5768  5768 I bt_bluedroid: get_profile_interface avrcp
,11-04 14:46:30.904  5768  5768 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 14:46:30.904  5768  5768 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 14:46:30.904  5768  5768 D A2dpStateMachine: make
,11-04 14:46:30.906  5768  5768 I bt_bluedroid: get_profile_interface a2dp
,11-04 14:46:30.906  5768  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-04 14:46:30.908  5768  5820 D A2dpStateMachine: Enter Disconnected: -2
,11-04 14:46:30.910  5768  5768 I BluetoothHidServiceJni: classInitNative: succeeds
,11-04 14:46:30.911  5768  5768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
11-04 14:46:30.911  3560  3560 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:46:30.913  5722  5722 D BluetoothInputDevice: Proxy object connected
,11-04 14:46:30.913  5768  5768 D HidService: Received start request. Starting profile...
11-04 14:46:30.913  5768  5768 I bt_bluedroid: get_profile_interface hidhost
11-04 14:46:30.913  5768  5768 D HidService: setHidService(): set to: null
11-04 14:46:30.913  5768  5788 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf406c56d
11-04 14:46:30.914  5722  5722 D HidProfile: Bluetooth service connected
11-04 14:46:30.914  5768  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 14:46:30.914  5768  5768 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-04 14:46:30.915  5768  5768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
11-04 14:46:30.916  5768  5768 D HealthService: Received start request. Starting profile...
,11-04 14:46:30.917  5768  5768 I bt_bluedroid: get_profile_interface health
11-04 14:46:30.917  5768  5768 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 14:46:30.918  5768  5768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:30.919  5722  5722 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 14:46:30.919  5768  5768 D PanService: Received start request. Starting profile...
11-04 14:46:30.919  5768  5768 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 14:46:30.919  5768  5768 I bt_bluedroid: get_profile_interface pan
11-04 14:46:30.919  5722  5722 D PanProfile: Bluetooth service connected
11-04 14:46:30.920  5768  5788 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-04 14:46:30.923  5768  5768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:30.924  5722  5722 D BluetoothMap: Proxy object connected
,11-04 14:46:30.924  5722  5722 D MapProfile: Bluetooth service connected
11-04 14:46:30.924  5722  5722 D BluetoothMap: getConnectedDevices()
,11-04 14:46:30.925  5768  5768 D BluetoothMapService: Received start request. Starting profile...
11-04 14:46:30.925  5768  5768 D BluetoothMapService: start()
11-04 14:46:30.925  5722  5722 D BluetoothMap: Bluetooth is Not enabled
,11-04 14:46:30.928  5768  5768 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-04 14:46:30.929  5768  5768 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 14:46:30.929  5768  5768 D BluetoothMapAppObserver: createReceiver()
,11-04 14:46:30.930  5768  5768 D BluetoothMapAppObserver: initObservers()
11-04 14:46:30.930  5768  5768 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 14:46:30.936  5768  5768 V SapService: SapBinder()
,11-04 14:46:30.936  5768  5768 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:30.937  5768  5768 D SapService: Received start request. Starting profile...
11-04 14:46:30.937  5768  5768 V SapService: start()
,11-04 14:46:30.939  5768  5768 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:30.939  5768  5768 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:30.939  5768  5818 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 14:46:30.939  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 14:46:30.939  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:30.939  5768  5768 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:30.939  5768  5768 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:30.939  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:30.939  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:30.940  5768  5768 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:30.940  5768  5768 V BluetoothAdapterState: isTurningOn()=true
,11-04 14:46:30.940  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:30.940  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:30.940  5768  5768 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:30.940  5768  5768 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:30.940  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:30.941  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:30.941  5768  5768 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:46:30.941  5768  5768 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:30.941  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:30.941  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:30.941  5768  5768 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:30.941  5768  5768 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:30.941  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:30.941  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:46:30.943  5768  5768 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:46:30.944  5768  5768 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:30.944  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:30.944  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:46:30.944  5768  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-04 14:46:30.944  5768  5784 D BluetoothAdapterProperties: ScanMode =  20
11-04 14:46:30.944  5768  5784 D BluetoothAdapterProperties: State =  11
11-04 14:46:30.944  5768  5784 D BluetoothAdapterProperties: Setting state to 12
11-04 14:46:30.944  5768  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 14:46:30.945  5768  5784 I BluetoothAdapterState: Entering OnState
11-04 14:46:30.945  3116  3130 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 14:46:30.947   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:30.947  5768  5788 D BluetoothAdapterProperties: Scan Mode:21
11-04 14:46:30.947  3733  3749 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:30.947  5768  5788 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 14:46:30.947  3116  3116 D BluetoothInputDevice: Proxy object connected
11-04 14:46:30.947  3116  3116 D HidProfile: Bluetooth service connected
11-04 14:46:30.948  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 14:46:30.948  3116  3127 D BluetoothPan: onBluetoothStateChange on: true
,11-04 14:46:30.949   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 14:46:30.949  3116  3116 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 14:46:30.949  3116  3116 D PanProfile: Bluetooth service connected
11-04 14:46:30.950  5599  5599 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-04 14:46:30.950  3116  3347 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 14:46:30.952  3116  3958 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:30.952   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:30.952  5599  5599 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-04 14:46:30.953  5722  5733 D BluetoothMap: onBluetoothStateChange: up=true
11-04 14:46:30.954   930   930 D BluetoothA2dp: Proxy object connected
,11-04 14:46:30.954  5722  5732 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 14:46:30.956  5768  5768 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 14:46:30.956  5768  5768 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 14:46:30.957  3116  3127 D BluetoothMap: onBluetoothStateChange: up=true
11-04 14:46:30.957  5768  5768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:30.958  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:30.958  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:30.958  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:30.958  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:30.958  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:30.958  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:30.958  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:30.958  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:30.959  3116  3116 D BluetoothMap: Proxy object connected
11-04 14:46:30.959   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:30.959  3116  3116 D MapProfile: Bluetooth service connected
11-04 14:46:30.959  3116  3116 D BluetoothMap: getConnectedDevices()
11-04 14:46:30.959  5722  5733 D BluetoothPan: onBluetoothStateChange on: true
,11-04 14:46:30.960  5722  5732 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 14:46:30.960  3116  3347 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 14:46:30.961  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:30.962  5768  5768 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:30.962  3116  3116 D BluetoothA2dp: Proxy object connected
11-04 14:46:30.963   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,11-04 14:46:30.964  5768  5768 D ObexServerSockets: Succeed to create listening sockets 
,11-04 14:46:30.964  5768  5768 D ObexServerSockets0: startAccept()
11-04 14:46:30.964  5768  5768 D ObexServerSockets0: prepareForNewConnect()
,11-04 14:46:30.968  5768  5768 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 14:46:30.968  5768  5828 D ObexServerSockets0: Accepting socket connection...
11-04 14:46:30.968  5768  5768 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 14:46:30.969  5768  5829 D ObexServerSockets0: Accepting socket connection...
11-04 14:46:30.969  5768  5768 D BluetoothMapService: onReceive
11-04 14:46:30.969  5768  5768 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 14:46:30.969  5768  5768 D BluetoothMapService: STATE_ON
,11-04 14:46:30.970  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:30.970  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:30.970  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:30.970  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:30.970  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:30.970  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:30.970  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:30.970  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:46:30.971  5722  5722 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-04 14:46:30.972  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:30.973  5768  5830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 14:46:30.976  5722  5722 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-04 14:46:30.977  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:30.977  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:30.977  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:30.977  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:30.977  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:30.977  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:30.977  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:30.977  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:30.978  5768  5830 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 14:46:30.979  5768  5830 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 14:46:30.979  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:30.980  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 14:46:30.982  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:30.983  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 14:46:30.984  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:30.986  5722  5722 D BluetoothA2dp: Proxy object connected
11-04 14:46:30.987  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:30.990  3560  3560 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:46:30.995  5722  5722 D DockEventReceiver: finishStartingService: stopping service
,11-04 14:46:30.998  3116  3116 D BluetoothPbap: Proxy object connected
,11-04 14:46:30.998  3116  3116 D PbapServerProfile: Bluetooth service connected
,11-04 14:46:30.999  5768  5768 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 14:46:30.999  5768  5768 D ObexServerSockets0: prepareForNewConnect()
11-04 14:46:30.999  5722  5722 D BluetoothPbap: Proxy object connected
11-04 14:46:30.999  5722  5722 D PbapServerProfile: Bluetooth service connected
,11-04 14:46:31.007  5599  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:31.008  5599  5647 D io.jxcore.node.ConnectivityMonitor: stop
11-04 14:46:31.008  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-04 14:46:31.010  5768  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:31.011  5599  5647 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-04 14:46:31.011  5599  5647 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
11-04 14:46:31.014  5599  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:31.015  5768  5784 D BluetoothAdapterState: Current state: ON, message: 23
11-04 14:46:31.015  5768  5784 D BluetoothAdapterProperties: Setting state to 13
11-04 14:46:31.015  5768  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 14:46:31.016  5768  5784 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 14:46:31.017  5768  5784 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:46:31.017  5768  5768 D BluetoothMapService: onReceive
11-04 14:46:31.018  5768  5768 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 14:46:31.018  5768  5768 D BluetoothMapService: STATE_TURNING_OFF
,11-04 14:46:31.019  5768  5768 D BluetoothMapService: MAP Service closeService in
11-04 14:46:31.019  5768  5768 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 14:46:31.019  5768  5768 D ObexServerSockets0: shutdown(block = true)
11-04 14:46:31.020  5768  5768 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 14:46:31.020  5768  5828 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-04 14:46:31.020  5768  5768 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 14:46:31.020  5768  5829 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 14:46:31.020  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 14:46:31.022  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:31.023  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:31.023  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:31.023  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:31.023  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:31.023  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:46:31.023  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:31.023  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:31.023  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:31.023  5768  5788 D BluetoothAdapterProperties: Scan Mode:20
11-04 14:46:31.023  5768  5815 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 14:46:31.023  5768  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-04 14:46:31.025  5768  5768 D HeadsetService: Received stop request...Stopping profile...
,11-04 14:46:31.027  5722  5722 D DockEventReceiver: finishStartingService: stopping service
11-04 14:46:31.028  5768  5768 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:31.028  5768  5768 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:31.028  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:31.028  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:31.028  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:31.029  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:31.032  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 14:46:31.032  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:31.032  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:31.032  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:31.032  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:31.032  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:46:31.032  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:31.032  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:31.032  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:31.033  5599  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:31.033  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:31.035  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:31.036  3560  3560 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:46:31.037  5768  5768 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 14:46:31.037  5768  5768 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 14:46:31.037  5768  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 14:46:31.037  5768  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:31.038  5768  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:31.038  5768  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 14:46:31.038  5768  5768 D A2dpService: Received stop request...Stopping profile...
11-04 14:46:31.038  5768  5788 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
11-04 14:46:31.038  5768  5820 D A2dpStateMachine: Exit Disconnected: -1
11-04 14:46:31.039  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:31.040   930   930 D BluetoothA2dp: Proxy object disconnected
,11-04 14:46:31.041  5768  5768 D HidService: Received stop request...Stopping profile...
,11-04 14:46:31.041  5768  5768 D HidService: Stopping Bluetooth HidService
11-04 14:46:31.042  5768  5768 D HealthService: Received stop request...Stopping profile...
,11-04 14:46:31.045  5768  5768 D PanService: Received stop request...Stopping profile...
,11-04 14:46:31.047  5722  5722 D BluetoothA2dp: Proxy object disconnected
,11-04 14:46:31.048  5722  5722 D BluetoothInputDevice: Proxy object disconnected
11-04 14:46:31.048  5722  5722 D HidProfile: Bluetooth service disconnected
11-04 14:46:31.048  5722  5722 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 14:46:31.048  5722  5722 D PanProfile: Bluetooth service disconnected
11-04 14:46:31.048  5768  5768 D BluetoothMapService: Received stop request...Stopping profile...
11-04 14:46:31.048  5768  5768 D BluetoothMapService: stop()
11-04 14:46:31.048  3116  3116 D BluetoothA2dp: Proxy object disconnected
11-04 14:46:31.049  3116  3116 D BluetoothInputDevice: Proxy object disconnected
11-04 14:46:31.049  3116  3116 D HidProfile: Bluetooth service disconnected
11-04 14:46:31.049  3116  3116 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 14:46:31.049  3116  3116 D PanProfile: Bluetooth service disconnected
11-04 14:46:31.049  5768  5768 D BluetoothMapAppObserver: deinitObservers()
11-04 14:46:31.049  5768  5768 D BluetoothMapAppObserver: removeReceiver()
11-04 14:46:31.050  3116  3116 D BluetoothMap: Proxy object disconnected
11-04 14:46:31.050  3116  3116 D MapProfile: Bluetooth service disconnected
11-04 14:46:31.050  5722  5722 D BluetoothMap: Proxy object disconnected
,11-04 14:46:31.050  5722  5722 D MapProfile: Bluetooth service disconnected
11-04 14:46:31.051  5768  5768 D SapService: Received stop request...Stopping profile...
11-04 14:46:31.051  5768  5768 V SapService: stop()
11-04 14:46:31.053  5722  5722 D BluetoothPbap: Proxy object disconnected
11-04 14:46:31.053  3116  3116 D BluetoothPbap: Proxy object disconnected
11-04 14:46:31.053  5722  5722 D PbapServerProfile: Bluetooth service disconnected
11-04 14:46:31.054  5768  5768 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:31.053  3116  3116 D PbapServerProfile: Bluetooth service disconnected
11-04 14:46:31.054  5768  5768 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:31.054  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:31.054  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:46:31.055  5768  5768 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:31.055  5768  5768 V BluetoothAdapterState: isTurningOn()=false
,11-04 14:46:31.055  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:31.055  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:31.055  5768  5768 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 14:46:31.056  5768  5768 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 14:46:31.056  5768  5768 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:31.056  5768  5768 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:31.056  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:31.056  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:31.056  5768  5768 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-04 14:46:31.056  5768  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 14:46:31.056  5768  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 14:46:31.056  5768  5768 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-04 14:46:31.056  5768  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:31.056  5768  5788 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 14:46:31.058  5768  5813 W bt_l2cap: btif_in_execute0019 not found f: Unknown service being enabled
11-04 14:46:31.058  5768  5788 E bt_btif : btif_in_execute0019 not found f: Unknown service being enabled
11-04 14:46:31.058  5768  5813 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 14:46:31.058  5768  5813 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-04 14:46:31.058  5768  5813 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 14:46:31.058  5768  5768 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:31.058  5768  5768 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:31.059  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:31.059  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:46:31.059  5768  5768 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 14:46:31.059  5768  5768 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-04 14:46:31.060  5768  5768 D BluetoothMapService: MAP Service closeService in
11-04 14:46:31.060  5768  5768 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:31.060  5768  5768 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:31.060  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 14:46:31.060  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:31.060  5768  5768 D BluetoothMapService: cleanup()
11-04 14:46:31.060  5768  5768 D BluetoothMapService: MAP Service closeService in
11-04 14:46:31.061  5768  5768 V BluetoothAdapterState: isTurningOff()=true
11-04 14:46:31.062  5768  5768 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:31.062  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:31.062  5768  5768 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:31.062  5768  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-04 14:46:31.062  5768  5784 D BluetoothAdapterProperties: Setting state to 15
11-04 14:46:31.062  5768  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 14:46:31.062  5768  5784 I BluetoothAdapterState: Entering BleOnState
11-04 14:46:31.062  3116  3958 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 14:46:31.063   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-04 14:46:31.063  3733  3956 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:31.063  3116  3127 D BluetoothPan: onBluetoothStateChange on: false
,11-04 14:46:31.068  5722  5732 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 14:46:31.069   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 14:46:31.069  3116  3130 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 14:46:31.070  3116  3347 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:31.070   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:31.071  5722  5826 D BluetoothMap: onBluetoothStateChange: up=false
11-04 14:46:31.072  5722  5733 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 14:46:31.073  5722  5732 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:31.073  3116  3958 D BluetoothMap: onBluetoothStateChange: up=false
11-04 14:46:31.074   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:46:31.074  5722  5826 D BluetoothPan: onBluetoothStateChange on: false
,11-04 14:46:31.075  5722  5733 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-04 14:46:31.075  3116  3127 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-04 14:46:31.076  5768  5784 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 14:46:31.076  5768  5784 D BluetoothAdapterProperties: Setting state to 16
,11-04 14:46:31.076  5768  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 14:46:31.077  5768  5784 D BluetoothAdapterProperties: onBleDisable
,11-04 14:46:31.077  5768  5785 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 14:46:31.078  5768  5788 D BluetoothAdapterProperties: Scan Mode:20
11-04 14:46:31.077  5768  5784 I BluetoothAdapterState: Entering PendingCommandState
11-04 14:46:31.079  5768  5813 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 14:46:31.079  5768  5813 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:46:31.080  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:31.080  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 14:46:31.082  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:31.085  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:31.088  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:31.088  3560  3560 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 14:46:31.089  5722  5722 D DockEventReceiver: finishStartingService: stopping service
,11-04 14:46:31.281  5768  5788 I bt_hci  : shut_down
,11-04 14:46:31.281  5768  5792 D bt_hwcfg: hw_epilog_process
11-04 14:46:31.282  5768  5792 I bt_vendor: low_power_mode_cb
,11-04 14:46:31.286  5768  5792 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-04 14:46:31.286  5768  5792 I bt_vendor: epilog_cb
11-04 14:46:31.286  5768  5792 I bt_hci  : epilog_finished_callback
,11-04 14:46:31.288  5768  5788 I bt_hci_h4: hal_close
,11-04 14:46:31.289  5768  5788 I bt_userial_vendor: device fd = 54 close
,11-04 14:46:31.326   930  2944 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-04 14:46:31.411  5768  5785 D bt_stack_manager: event_shut_down_stack finished.
,11-04 14:46:31.411  5768  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 14:46:31.416  5768  5784 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-04 14:46:31.417  5768  5768 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 14:46:31.418  5768  5768 D BtGatt.GattService: Received stop request...Stopping profile...
,11-04 14:46:31.418  5768  5768 D BtGatt.GattService: stop()
,11-04 14:46:31.418  5768  5768 D BtGatt.AdvertiseManager: advertise clients cleared
11-04 14:46:31.422  5768  5768 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:31.422  5768  5768 V BluetoothAdapterState: isTurningOn()=false
,11-04 14:46:31.422  5768  5768 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:31.422  5768  5768 V BluetoothAdapterState: isBleTurningOff()=true
11-04 14:46:31.423  5768  5784 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-04 14:46:31.423  5768  5784 D BluetoothAdapterProperties: Setting state to 10
11-04 14:46:31.423  5768  5784 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-04 14:46:31.425  5768  5784 I BluetoothAdapterState: Entering OffState
,11-04 14:46:31.426   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-04 14:46:31.438  5768  5768 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 14:46:31.438  5768  5768 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 14:46:31.438  5768  5768 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-04 14:46:31.441  5768  5785 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 14:46:31.449  5768  5768 I art     : System.exit called, status: 0
,11-04 14:46:31.449  5768  5768 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 14:46:31.476   930  3401 I ActivityManager: Process com.android.bluetooth (pid 5768) has died
,11-04 14:46:31.517  5599  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 14:46:31.517  5599  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:31.517  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:31.517  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:31.517  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:31.517  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:46:31.517  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:31.517  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:31.517  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:31.517  5599  5670 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:46:31.517  5599  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:31.521  5599  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:31.542   930   947 I ActivityManager: Start proc 5843:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 14:46:31.609  5843  5843 D AdapterServiceConfig: Adding HeadsetService
,11-04 14:46:31.609  5843  5843 D AdapterServiceConfig: Adding A2dpService
11-04 14:46:31.609  5843  5843 D AdapterServiceConfig: Adding HidService
11-04 14:46:31.609  5843  5843 D AdapterServiceConfig: Adding HealthService
,11-04 14:46:31.610  5843  5843 D AdapterServiceConfig: Adding PanService
11-04 14:46:31.610  5843  5843 D AdapterServiceConfig: Adding GattService
11-04 14:46:31.610  5843  5843 D AdapterServiceConfig: Adding BluetoothMapService
,11-04 14:46:31.610  5843  5843 D AdapterServiceConfig: Adding SapService
,11-04 14:46:31.623   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f93a1c2:true
,11-04 14:46:31.623  5843  5843 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 14:46:31.626  5843  5843 I bt_bluedroid: init
11-04 14:46:31.626  5843  5855 I BluetoothAdapterState: Entering OffState
,11-04 14:46:31.627  5843  5856 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 14:46:31.628  5843  5856 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-04 14:46:31.628  5843  5856 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-04 14:46:31.628  5843  5856 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-04 14:46:31.628  5843  5843 I bt_bluedroid: get_profile_interface socket
,11-04 14:46:31.630  5843  5859 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 14:46:31.630  5843  5843 I bt_bluedroid: get_profile_interface sdp
,11-04 14:46:31.631  5843  5859 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 14:46:31.636  5843  5854 I bt_bluedroid: config_hci_snoop_log
,11-04 14:46:31.637   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 14:46:31.660  5843  5855 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 14:46:31.660  5843  5855 D BluetoothAdapterProperties: Setting state to 14
11-04 14:46:31.660  5843  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-04 14:46:31.661  5843  5855 D BluetoothBondStateMachine: make
,11-04 14:46:31.662  5843  5860 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 14:46:31.664  5843  5855 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:46:31.665  5843  5843 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 14:46:31.667  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
11-04 14:46:31.667  5843  5843 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 14:46:31.668  5843  5843 D BtGatt.GattService: Received start request. Starting profile...
11-04 14:46:31.668  5843  5843 D BtGatt.GattService: start()
11-04 14:46:31.668  5843  5843 I bt_bluedroid: get_profile_interface gatt
,11-04 14:46:31.669  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:31.669  5843  5843 D BtGatt.AdvertiseManager: advertise manager created
,11-04 14:46:31.673  5843  5843 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:46:31.673  5843  5843 V BluetoothAdapterState: isTurningOn()=false
11-04 14:46:31.673  5843  5843 V BluetoothAdapterState: isBleTurningOn()=true
11-04 14:46:31.673  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:46:31.674  5843  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-04 14:46:31.675  5843  5855 I bt_bluedroid: bt_bluedroid
,11-04 14:46:31.675  5843  5856 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-04 14:46:31.675  5843  5856 I bt_hci  : start_up
,11-04 14:46:31.679  5843  5856 I bt_vendor: alloc value 0xf410d871
,11-04 14:46:31.679  5843  5856 I bt_vendor: init
11-04 14:46:31.679  5843  5856 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 14:46:31.679  5843  5856 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 14:46:31.788  5843  5856 D bt_hci  : start_up starting async portion
,11-04 14:46:31.789  5843  5863 I bt_hci  : event_finish_startup
11-04 14:46:31.789  5843  5863 I bt_hci_h4: hal_open
,11-04 14:46:31.789  5843  5863 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 14:46:31.785  5864  5864 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 14:46:31.791  5843  5863 I bt_userial_vendor: device fd = 54 open
,11-04 14:46:31.804  5843  5863 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 14:46:31.806  5843  5863 D bt_hwcfg: Chipset BCM4358A3
,11-04 14:46:31.807  5843  5863 D bt_hwcfg: Target name = [BCM4358A3]
11-04 14:46:31.807  5843  5863 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 14:46:32.025  5843  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-04 14:46:32.200  5843  5863 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 14:46:32.200  5843  5863 D bt_hwcfg: Settlement delay -- 100 ms
,11-04 14:46:32.201  5843  5863 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 14:46:32.326  5843  5863 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 14:46:32.326  5843  5863 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-04 14:46:32.327  5843  5863 I bt_hwcfg: vendor lib fwcfg completed
,11-04 14:46:32.328  5843  5863 I bt_vendor: firmware callback
,11-04 14:46:32.328  5843  5863 I bt_hci  : firmware_config_callback
,11-04 14:46:32.336  5843  5866 I bt_btu  : btu_task pending for preload complete event
,11-04 14:46:32.336  5843  5866 I bt_btu_task: Bluetooth chip preload is complete
11-04 14:46:32.336  5843  5866 I bt_btu  : btu_task received preload complete event
,11-04 14:46:32.343  5843  5866 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 14:46:32.343  5843  5866 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 14:46:32.343  5843  5866 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 14:46:32.344  5843  5866 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 14:46:32.344  5843  5866 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 14:46:32.344  5843  5866 I         : BTE_InitTraceLevels -- TRC_A2D
,11-04 14:46:32.344  5843  5866 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 14:46:32.344  5843  5866 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 14:46:32.344  5843  5866 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 14:46:32.344  5843  5866 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 14:46:32.344  5843  5866 I         : BTE_InitTraceLevels -- TRC_SDP
,11-04 14:46:32.345  5843  5866 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 14:46:32.345  5843  5866 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 14:46:32.345  5843  5866 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 14:46:32.345  5843  5866 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 14:46:32.424  5843  5866 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf408b549
,11-04 14:46:32.425  5843  5866 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf408b549 
,11-04 14:46:32.451  5843  5859 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 14:46:32.452  5843  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 14:46:32.452  5843  5859 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 14:46:32.454  5843  5859 D BluetoothAdapterProperties: Name is: Nexus 6P
11-04 14:46:32.456  5843  5859 D BluetoothAdapterProperties: Scan Mode:20
,11-04 14:46:32.456  5843  5859 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-04 14:46:32.457  5843  5859 D bt_hci  : do_postload posting postload work item
11-04 14:46:32.457  5843  5863 I bt_hci  : event_postload
11-04 14:46:32.457  5843  5863 I bt_vendor: sco_config_cb
11-04 14:46:32.457  5843  5863 I bt_hci  : sco_config_callback postload finished.
,11-04 14:46:32.463  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:32.464  5843  5863 I bt_vendor: low_power_mode_cb
11-04 14:46:32.466  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:32.467  5843  5859 D bt_bte_conf: Device ID record 1 : primary
11-04 14:46:32.467  5843  5859 D bt_bte_conf:   vendorId            = 000f
11-04 14:46:32.468  5843  5859 D bt_bte_conf:   vendorIdSource      = 0001
11-04 14:46:32.468  5843  5859 D bt_bte_conf:   product             = 1200
11-04 14:46:32.468  5843  5859 D bt_bte_conf:   version             = 1436
11-04 14:46:32.468  5843  5859 D bt_bte_conf:   clientExecutableURL = 
,11-04 14:46:32.468  5843  5859 D bt_bte_conf:   serviceDescription  = 
11-04 14:46:32.468  5843  5859 D bt_bte_conf:   documentationURL    = 
11-04 14:46:32.468  5843  5859 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 14:46:32.468  5843  5856 D bt_stack_manager: event_start_up_stack finished
,11-04 14:46:32.469  5843  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 14:46:32.470  5843  5855 D BluetoothAdapterProperties: Setting state to 15
11-04 14:46:32.470  5843  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-04 14:46:32.471  5843  5855 I BluetoothAdapterState: Entering BleOnState
,11-04 14:46:32.474  5843  5855 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-04 14:46:32.474  5843  5855 D BluetoothAdapterProperties: Setting state to 11
11-04 14:46:32.474  5843  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-04 14:46:32.479  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:32.480  3116  3347 D BluetoothHeadset: Proxy object connected
11-04 14:46:32.480  3116  3116 D HeadsetProfile: Bluetooth service connected
11-04 14:46:32.480  3733  3749 D BluetoothHeadset: Proxy object connected
11-04 14:46:32.481   930   930 D BluetoothHeadset: Proxy object connected
11-04 14:46:32.481   930   930 D BluetoothHeadset: Proxy object connected
11-04 14:46:32.481   930   930 D BluetoothHeadset: Proxy object connected
11-04 14:46:32.481  5722  5733 D BluetoothHeadset: Proxy object connected
,11-04 14:46:32.483  5722  5722 D HeadsetProfile: Bluetooth service connected
11-04 14:46:32.484  5843  5843 D HeadsetService: Received start request. Starting profile...
11-04 14:46:32.486  5843  5843 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 14:46:32.486  5843  5843 D HeadsetStateMachine: make
11-04 14:46:32.488  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:32.491  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:32.491  5843  5855 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:46:32.495  5843  5843 D HeadsetStateMachine: max_hf_connections = 1
11-04 14:46:32.496  5843  5843 I bt_bluedroid: get_profile_interface handsfree
,11-04 14:46:32.496  5843  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 14:46:32.496  5843  5859 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
11-04 14:46:32.499  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:32.500  5843  5843 D A2dpService: Received start request. Starting profile...
,11-04 14:46:32.500  5843  5843 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 14:46:32.500  5843  5843 I bt_bluedroid: get_profile_interface avrcp
,11-04 14:46:32.506  5843  5843 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-04 14:46:32.506  5843  5843 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-04 14:46:32.506  5843  5843 D A2dpStateMachine: make
11-04 14:46:32.507  5843  5843 I bt_bluedroid: get_profile_interface a2dp
,11-04 14:46:32.508  5843  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-04 14:46:32.509  5843  5843 I BluetoothHidServiceJni: classInitNative: succeeds
11-04 14:46:32.509  5843  5875 D A2dpStateMachine: Enter Disconnected: -2
11-04 14:46:32.510  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:32.511  5843  5843 D HidService: Received start request. Starting profile...
11-04 14:46:32.511  5843  5843 I bt_bluedroid: get_profile_interface hidhost
,11-04 14:46:32.511  5843  5859 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf406c56d
11-04 14:46:32.511  5843  5843 D HidService: setHidService(): set to: null
11-04 14:46:32.511  5843  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-04 14:46:32.512  5843  5843 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-04 14:46:32.514  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
11-04 14:46:32.515  5843  5843 D HealthService: Received start request. Starting profile...
,11-04 14:46:32.516  5843  5843 I bt_bluedroid: get_profile_interface health
11-04 14:46:32.517  5843  5843 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 14:46:32.517  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:32.518  5843  5843 D PanService: Received start request. Starting profile...
11-04 14:46:32.518  5843  5843 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 14:46:32.518  5843  5843 I bt_bluedroid: get_profile_interface pan
11-04 14:46:32.519  5843  5859 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-04 14:46:32.521  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
,11-04 14:46:32.522  5843  5843 D BluetoothMapService: Received start request. Starting profile...
11-04 14:46:32.522  5843  5843 D BluetoothMapService: start()
11-04 14:46:32.524  5843  5843 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-04 14:46:32.525  5843  5843 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 14:46:32.525  5843  5843 D BluetoothMapAppObserver: createReceiver()
,11-04 14:46:32.526  5843  5843 D BluetoothMapAppObserver: initObservers()
11-04 14:46:32.526  5843  5843 D BluetoothMapAppObserver: getEnabledAccountItems()
11-04 14:46:32.527  5843  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-04 14:46:32.534  5843  5843 V SapService: SapBinder()
,11-04 14:46:32.535  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
11-04 14:46:32.535  3560  3560 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:46:32.535  5843  5843 D SapService: Received start request. Starting profile...
11-04 14:46:32.535  5843  5843 V SapService: start()
,11-04 14:46:32.538  5843  5843 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:46:32.538  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:32.538  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:32.538  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:46:32.538  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:32.538  5843  5843 V BluetoothAdapterState: isTurningOn()=true
,11-04 14:46:32.538  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:32.539  5843  5872 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isTurningOn()=true
,11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:46:32.539  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:32.540  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-04 14:46:32.541  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-04 14:46:32.541  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 14:46:32.541  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:46:32.541  5843  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 14:46:32.541  5843  5855 D BluetoothAdapterProperties: ScanMode =  20
11-04 14:46:32.541  5843  5855 D BluetoothAdapterProperties: State =  11
11-04 14:46:32.541  5843  5855 D BluetoothAdapterProperties: Setting state to 12
11-04 14:46:32.541  5843  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 14:46:32.542  3116  3130 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 14:46:32.543  5843  5855 I BluetoothAdapterState: Entering OnState
,11-04 14:46:32.544  5843  5859 D BluetoothAdapterProperties: Scan Mode:21
11-04 14:46:32.544  5843  5859 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 14:46:32.544  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 14:46:32.545   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:32.545  3733  3753 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:32.545  3116  3347 D BluetoothPan: onBluetoothStateChange on: true
11-04 14:46:32.546  3116  3116 D BluetoothInputDevice: Proxy object connected
11-04 14:46:32.546  3116  3116 D HidProfile: Bluetooth service connected
11-04 14:46:32.547  5722  5732 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 14:46:32.549   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 14:46:32.550  3116  3130 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 14:46:32.550   930   930 D BluetoothA2dp: Proxy object connected
11-04 14:46:32.551  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:32.551  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:32.551  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:32.551  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:32.551  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:32.551  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:32.551  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:32.551  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:32.552  3116  3127 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:32.552  3116  3116 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 14:46:32.552   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:32.552  3116  3116 D PanProfile: Bluetooth service connected
,11-04 14:46:32.552  5722  5733 D BluetoothMap: onBluetoothStateChange: up=true
11-04 14:46:32.553  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:32.553  5843  5843 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 14:46:32.553  5722  5732 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 14:46:32.554  5843  5843 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 14:46:32.555  5722  5826 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:32.555  5843  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:32.555  3116  3347 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 14:46:32.556  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:32.556  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:32.556  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:32.556  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:32.556  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:32.556  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:32.556  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:32.556  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:46:32.557   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:46:32.557  5722  5733 D BluetoothPan: onBluetoothStateChange on: true
11-04 14:46:32.559  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:32.559  5843  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:32.559  5722  5826 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 14:46:32.560  5722  5722 D BluetoothA2dp: Proxy object connected
,11-04 14:46:32.560  5843  5843 D ObexServerSockets: Succeed to create listening sockets 
11-04 14:46:32.560  5843  5843 D ObexServerSockets0: startAccept()
11-04 14:46:32.560  5843  5843 D ObexServerSockets0: prepareForNewConnect()
11-04 14:46:32.561  3116  3958 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 14:46:32.562  5843  5843 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 14:46:32.562  5843  5843 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 14:46:32.563  5843  5881 D ObexServerSockets0: Accepting socket connection...
,11-04 14:46:32.563  3116  3116 D BluetoothA2dp: Proxy object connected
,11-04 14:46:32.563  5843  5882 D ObexServerSockets0: Accepting socket connection...
11-04 14:46:32.564   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 14:46:32.564   930   930 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-04 14:46:32.565  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-04 14:46:32.566  5722  5722 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 14:46:32.567  5722  5722 D PanProfile: Bluetooth service connected
11-04 14:46:32.567  5722  5722 D BluetoothInputDevice: Proxy object connected
11-04 14:46:32.567  5722  5722 D HidProfile: Bluetooth service connected
11-04 14:46:32.568  5843  5843 D BluetoothMapService: onReceive
11-04 14:46:32.568  5843  5843 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 14:46:32.568  3116  3116 D BluetoothMap: Proxy object connected
11-04 14:46:32.568  5843  5843 D BluetoothMapService: STATE_ON
11-04 14:46:32.568  3116  3116 D MapProfile: Bluetooth service connected
,11-04 14:46:32.568  3116  3116 D BluetoothMap: getConnectedDevices()
11-04 14:46:32.570  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:32.571  5843  5884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 14:46:32.572  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:32.573  5843  5884 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 14:46:32.573  5843  5884 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-04 14:46:32.576  5722  5722 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 14:46:32.577  5722  5722 D BluetoothMap: Proxy object connected
,11-04 14:46:32.578  5722  5722 D MapProfile: Bluetooth service connected
11-04 14:46:32.578  5722  5722 D BluetoothMap: getConnectedDevices()
,11-04 14:46:32.581  3560  3560 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:46:32.582  5722  5722 D DockEventReceiver: finishStartingService: stopping service
,11-04 14:46:32.587  5722  5722 D BluetoothPbap: Proxy object connected
,11-04 14:46:32.587  5722  5722 D PbapServerProfile: Bluetooth service connected
,11-04 14:46:32.593  5843  5888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:32.593  5843  5843 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 14:46:32.593  5843  5843 D ObexServerSockets0: prepareForNewConnect()
,11-04 14:46:32.600  3116  3116 D BluetoothPbap: Proxy object connected
11-04 14:46:32.600  3116  3116 D PbapServerProfile: Bluetooth service connected
,11-04 14:46:32.611  5843  5892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 14:46:32.612  5843  5892 I BtOppRfcommListener: Accept thread started.
,11-04 14:46:33.040  5599  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:33.040  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:33.040  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:33.040  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:33.040  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:33.040  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:33.040  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:33.040  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:46:33.046  5599  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:33.049  5599  5647 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-04 14:46:33.052   930  3402 D WifiService: setWifiEnabled: false pid=5599, uid=10077
11-04 14:46:33.052   930  3402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:33.057   930  2933 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-04 14:46:33.057   930  2933 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 14:46:33.058   930  2933 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 14:46:33.058   930  2933 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 14:46:33.058  5599  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:33.073   930  5782 D DhcpClient: Clearing IP address
,11-04 14:46:33.073   506   924 D CommandListener: Clearing all IP addresses on wlan0
,11-04 14:46:33.080   506   924 D CommandListener: Setting iface cfg
,11-04 14:46:33.082   930  5783 D DhcpClient: Receive thread stopped
,11-04 14:46:33.088  3560  5812 V NativeCrypto: Read error: ssl=0x7f89985000: I/O error during system call, Connection timed out
,11-04 14:46:33.090  3560  5812 V NativeCrypto: SSL shutdown failed: ssl=0x7f89985000: I/O error during system call, Broken pipe
,11-04 14:46:33.092   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-04 14:46:33.092   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-04 14:46:33.095   532   532 E Parcel  : Reading a NULL string not supported here.
11-04 14:46:33.099   930   930 D RttService: SCAN_AVAILABLE : 1
,11-04 14:46:33.100   930  3052 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 14:46:33.101   930  2944 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-04 14:46:33.103  3707  3849 W QCNEJ   : |CORE| network lost: 101
,11-04 14:46:33.104  3707  3849 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-04 14:46:33.115   930  2933 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-04 14:46:33.125   930  2933 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 14:46:33.126   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:46:33.146   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:46:33.147   506   924 D CommandListener: Clearing all IP addresses on wlan0
11-04 14:46:33.147   930  2944 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-04 14:46:33.147   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:46:33.151   930   947 D Tethering: MasterInitialState.processMessage what=3
,11-04 14:46:33.154   930  2933 D DhcpClient: doQuit
,11-04 14:46:33.154  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:33.154  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:33.154  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:33.154  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:33.154  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:33.154  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:33.154  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:33.154  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:33.154   930  2933 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 14:46:33.154   930  5782 D DhcpClient: onQuitting
11-04 14:46:33.155  5718  5718 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-04 14:46:33.157  3926  3926 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-04 14:46:33.160  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:33.161  3939  3939 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 14:46:33.164  3939  3939 D SystemUpdateService: onCreate
11-04 14:46:33.164  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:33.164  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:33.164  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:33.164  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:46:33.164  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:33.164  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:33.164  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:33.164  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:33.167  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:46:33.168  3939  3939 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 14:46:33.170  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:33.170  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:33.170  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:33.170  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:46:33.170  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:33.170  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:33.170  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:33.170  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:33.172  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:46:33.173  3939  5899 I SystemUpdateService: active receiver: enabled
,11-04 14:46:33.174  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:33.178  5718  5718 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-04 14:46:33.179  3939  3939 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 14:46:33.184  3939  4287 I iu.UploadsManager: num queued entries: 0
,11-04 14:46:33.184  5718  5718 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-04 14:46:33.184  3939  4287 I iu.UploadsManager: num updated entries: 0
11-04 14:46:33.186  3939  5899 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 14:46:33.188  3939  5899 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 14:46:33.188  3939  5899 I SystemUpdateService: now status is 0 (complete)
11-04 14:46:33.188  3939  5899 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 14:46:33.188  3939  5899 I SystemUpdateService: file has been verified
,11-04 14:46:33.189  3939  3939 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 14:46:33.191  3939  3939 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 14:46:33.192  5397  5397 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:46:33.199  5397  5397 D SprintDMHelper: simOperator: 
11-04 14:46:33.199  5397  5397 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 14:46:33.201  3939  5899 I SystemUpdateService: OTA package size = 21989297
,11-04 14:46:33.207  3939  4287 I iu.SyncManager: NEXT; no task
,11-04 14:46:33.209   506   924 E Netd    : netlink response contains error (No such file or directory)
,11-04 14:46:33.211   930  2944 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-04 14:46:33.214  5718  5718 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 14:46:33.222  5718  5718 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 14:46:33.225  3939  5899 I SystemUpdateService: showing system update notification
,11-04 14:46:33.234   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 14:46:33.236  3939  3939 D SystemUpdateService: onDestroy
,11-04 14:46:33.326   930  2933 D wifi    : In wifi stop Hal
,11-04 14:46:33.326   930  2933 D wifi    : halHandle = 0x7f87730300, mVM = 0x7fa3d4d140, mCls = 0x2019aa
11-04 14:46:33.327   930  5717 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 14:46:33.327   930  5717 D WifiHAL : Got a signal to exit!!!
11-04 14:46:33.327   930  5717 I WifiHAL : Exit wifi_event_loop
11-04 14:46:33.331   930  2933 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-04 14:46:33.331   930  2933 E WifiHAL : Event processing terminated
,11-04 14:46:33.332   930  2933 D wifi    : In wifi cleaned up handler
11-04 14:46:33.332   930  2933 I WifiHAL : Internal cleanup completed
11-04 14:46:33.336  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:33.337  4071  4195 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 14:46:33.338  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:33.339  5019  5019 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 14:46:33.354   930  5717 D wifi    : set interface wlan0 flags (DOWN)
,11-04 14:46:33.354   930  2933 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 14:46:33.560   930   947 D Tethering: InitialState.processMessage what=4
,11-04 14:46:33.567  5599  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:33.567  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:33.567  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:33.567  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:46:33.567  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:33.567  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:33.567  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:33.567  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:33.567   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 14:46:33.573  5599  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:33.575   930   941 D WifiService: setWifiEnabled: true pid=5599, uid=10077
,11-04 14:46:33.575   930   941 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-04 14:46:33.576  5599  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:33.580   506   924 D SoftapController: Softap fwReload - Ok
,11-04 14:46:33.584   506   924 D CommandListener: Setting iface cfg
,11-04 14:46:33.585   506   924 D CommandListener: Trying to bring down wlan0
,11-04 14:46:33.586   506   924 D CommandListener: Clearing all IP addresses on wlan0
,11-04 14:46:33.590   930  2933 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 14:46:33.741   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-04 14:46:33.741   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-04 14:46:34.082   930  3401 D WifiService: setWifiEnabled: true pid=5599, uid=10077
,11-04 14:46:34.088   930  3401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:34.208   930  2933 D wifi    : set interface wlan0 flags (UP)
,11-04 14:46:34.209   930  2933 I WifiHAL : Initializing wifi
,11-04 14:46:34.209   930  2933 I WifiHAL : Creating socket
,11-04 14:46:34.215   930  2933 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-04 14:46:34.215   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 14:46:34.216   930  2933 D wifi    : Did set static halHandle = 0x7f87730300
11-04 14:46:34.216   930  2933 D wifi    : halHandle = 0x7f87730300, mVM = 0x7fa3d4d140, mCls = 0x1018f2
,11-04 14:46:34.216   930  2933 D wifi    : array field set
,11-04 14:46:34.217   930  2933 I WifiNative-HAL: interface[0] = wlan0
,11-04 14:46:34.219   930  5908 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547733308160
,11-04 14:46:34.220   930  5908 D wifi    : waitForHalEvents called, vm = 0x7fa3d4d140, obj = 0x1018f2, env = 0x7f87717cc0
,11-04 14:46:34.282  5909  5909 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 14:46:34.321   930  2933 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 14:46:34.330  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:34.331  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:34.358  5909  5909 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 14:46:34.364  5909  5909 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 14:46:34.364  5909  5909 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 14:46:34.375   930  2933 D WifiConfigStore: Loading config and enabling all networks 
,11-04 14:46:34.379  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:34.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:34.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:34.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:34.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:34.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:34.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:34.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:46:34.380  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:34.384  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:34.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:34.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:34.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:34.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:34.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:34.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:34.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:34.385  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:34.391   930  2933 D WifiConfigStore: loaded 0 passpoint configs
,11-04 14:46:34.391   930  2933 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-04 14:46:34.392   930  2933 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-04 14:46:34.392   930  2933 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-04 14:46:34.392   930  2933 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-04 14:46:34.392   930  2933 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-04 14:46:34.393   930  2933 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 14:46:34.393   930  2933 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 14:46:34.393   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 14:46:34.393   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-04 14:46:34.393   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 14:46:34.393   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 14:46:34.393   930  2933 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 14:46:34.395   930  2933 D WifiNative-HAL: Setting external_sim to 1
,11-04 14:46:34.395   930  2933 D wifi    : setting dfs flag to true, 0x7f8849c360
,11-04 14:46:34.396  5019  5019 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 14:46:34.396   930  2933 D WifiStateMachine: Setting OUI to DA-A1-19
,11-04 14:46:34.396   930  2933 D wifi    : setting scan oui 0x7f8849c360
11-04 14:46:34.396   930  2933 D WifiHAL : Sending mac address OUI
,11-04 14:46:34.398   930  2933 E native  : do suspend false
,11-04 14:46:34.404   930  2933 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-04 14:46:34.405   930   930 D RttService: SCAN_AVAILABLE : 3
11-04 14:46:34.405   930  3052 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 14:46:34.408   506   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-04 14:46:34.409   506   924 D CommandListener: Setting iface cfg
,11-04 14:46:34.414   930  2932 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,11-04 14:46:34.414   930  2932 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 14:46:34.416   930  2932 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 14:46:34.416   930  2932 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 14:46:34.421   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=115063 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-04 14:46:34.596  5599  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:34.596  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:34.596  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:34.596  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:34.596  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:34.596  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:34.596  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:34.596  5599  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:34.601  5599  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:34.604  5599  5647 D BluetoothAdapter: enable(): BT is already enabled..!
11-04 14:46:34.604   930  3402 D WifiService: setWifiEnabled: true pid=5599, uid=10077
,11-04 14:46:34.604   930  3402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:46:34.605  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 14:46:34.606  5599  5647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 14:46:34.606  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:46:34.606  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:46:34.606  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 14:46:34.606  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@465d58 removed from the list
11-04 14:46:34.606  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 14:46:34.606  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@876beb1 removed from the list
,11-04 14:46:34.606  5599  5647 D io.jxcore.node.ConnectivityMonitor: stop
11-04 14:46:34.607  5599  5647 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 14:46:34.607  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:46:34.609  5599  5647 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,11-04 14:46:34.611  5599  5647 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-04 14:46:34.613  5599  5647 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-04 14:46:34.615  5599  5647 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-04 14:46:34.617  5599  5647 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-04 14:46:34.618  5599  5647 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-04 14:46:34.619  5599  5647 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-04 14:46:34.620  5599  5647 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-04 14:46:34.621  5599  5647 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-04 14:46:34.624  5599  5647 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-04 14:46:34.624  5599  5647 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8475fcf Bundle[{}]
11-04 14:46:34.625  5599  5647 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-04 14:46:34.626  5599  5647 I io.jxcore.node.LifeCycleMonitor: start: OK
11-04 14:46:34.626  5599  5647 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-04 14:46:34.627  5599  5647 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-04 14:46:34.627  5599  5647 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-04 14:46:34.628  5599  5647 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-04 14:46:34.629  5599  5647 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-04 14:46:34.630  5599  5647 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,11-04 14:46:34.630  5599  5647 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-04 14:46:34.631  5599  5647 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-04 14:46:34.632  5599  5647 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 14:46:34.634  5599  5647 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-04 14:46:34.637  5599  5647 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-04 14:46:34.639  5599  5647 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-04 14:46:34.639  5599  5647 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
11-04 14:46:34.640  5599  5647 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
11-04 14:46:34.641  5599  5647 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-04 14:46:34.642  5599  5647 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-04 14:46:34.643  5599  5647 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-04 14:46:34.644  5599  5647 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-04 14:46:34.646  5599  5647 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-04 14:46:34.647  5599  5647 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-04 14:46:34.647  5599  5647 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-04 14:46:34.648  5599  5647 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 146)
11-04 14:46:34.648  5599  5647 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-04 14:46:34.648  5599  5647 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-04 14:46:34.648  5599  5647 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 147)
,11-04 14:46:34.649  5599  5647 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-04 14:46:34.650  5599  5647 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-04 14:46:34.651  5599  5647 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-04 14:46:34.652  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 14:46:34.652  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ff704 added. We now have 3 listener(s)
,11-04 14:46:34.654  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 14:46:34.654  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 14:46:34.654  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 14:46:34.654  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 14:46:34.654  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50794ed added. We now have 3 listener(s)
11-04 14:46:34.654  5599  5647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 14:46:34.655  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 14:46:34.658  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:46:34.661  5599  5647 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:46:34.661  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:34.661  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:34.661  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:34.661  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:34.661  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:46:34.661  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:46:34.661  5599  5647 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:46:34.663  5599  5647 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:46:34.663  5599  5647 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 14:46:34.666  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:46:34.667  5599  5647 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-04 14:46:34.667  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:46:34.667  5599  5647 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-04 14:46:34.667  5599  5647 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-04 14:46:34.668  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-04 14:46:34.668  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:34.668  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:46:34.668  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 14:46:34.668  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:46:34.669  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 14:46:34.670  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:46:34.671  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-04 14:46:34.671  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:46:34.671  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:46:34.671  5599  5911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:46:34.671  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 14:46:34.671  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:46:34.671  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:46:34.671  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 14:46:34.672  5599  5911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 14:46:34.672  5883  5883 W Binder_6: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[34375]" dev="sockfs" ino=34375 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:46:34.675  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:46:34.675  5599  5647 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:46:34.675  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 14:46:34.678  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:46:34.679  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:46:34.679  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:46:34.675  5883  5883 W Binder_6: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34375]" dev="sockfs" ino=34375 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:46:34.679  5599  5911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-04 14:46:34.681  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:34.681  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 14:46:34.681  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:46:34.681  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-04 14:46:34.681  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:46:34.682  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:34.682  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:34.682  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:34.682  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:34.683  5599  5647 D BluetoothAdapter: STATE_ON
,11-04 14:46:34.685  5843  5853 D BtGatt.GattService: registerClient() - UUID=546c5463-8fd3-4e78-bf61-bcaeec7fb7cb
,11-04 14:46:34.686  5843  5859 D BtGatt.GattService: onClientRegistered() - UUID=546c5463-8fd3-4e78-bf61-bcaeec7fb7cb, clientIf=5
11-04 14:46:34.687  5599  5609 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-04 14:46:34.689  5843  5861 D BtGatt.AdvertiseManager: message : 0
,11-04 14:46:34.691  5843  5861 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:46:34.701  5843  5859 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 14:46:34.707  5843  5859 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 14:46:34.707  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:34.708  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:34.708  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:46:34.708  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:34.708  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:34.708  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:34.708  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:34.708  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:34.708  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-04 14:46:34.710  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-04 14:46:34.710  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:34.712  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:34.712  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:34.712  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:34.712  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:34.712  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:46:34.713  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-04 14:46:34.713  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 14:46:34.713  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:46:34.713  5599  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:34.713  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:46:34.713  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:46:34.713  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 14:46:34.713  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:46:34.713  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 14:46:34.713  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-04 14:46:34.713  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 14:46:34.716  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 14:46:34.716  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:46:34.716  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 14:46:34.716  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 14:46:34.716  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:46:34.717  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:34.717  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 14:46:35.218  5599  5599 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-04 14:46:35.218  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 14:46:35.218  5599  5599 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 14:46:37.499  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 14:46:37.508  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 14:46:37.513  5909  5909 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 14:46:37.541   930  2933 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 14:46:37.542   930  2933 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-04 14:46:37.543   930  2933 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:46:37.554   930  2933 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 14:46:37.589   930  2933 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 14:46:37.595  5909  5909 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 14:46:38.025  5909  5909 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 14:46:38.057  5909  5909 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 14:46:38.058  5909  5909 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 14:46:38.071   930  2933 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 14:46:38.071   930  2933 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 14:46:38.071   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 14:46:38.088   930  2933 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:46:38.101   506   924 D CommandListener: Setting iface cfg
,11-04 14:46:38.106   930  2933 D WifiStateMachine: Start Dhcp Watchdog 3
,11-04 14:46:38.117   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-04 14:46:38.117   930  2933 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 14:46:38.117   930  2944 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
11-04 14:46:38.118   930  5916 D DhcpClient: Receive thread started
,11-04 14:46:38.200   930  2933 E native  : do suspend false
,11-04 14:46:38.214  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-04 14:46:38.214   930  5915 D DhcpClient: Broadcasting DHCPDISCOVER
11-04 14:46:38.215  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 14:46:38.215  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:46:38.215  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:46:38.215  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-04 14:46:38.216  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:46:38.216  5599  5911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 14:46:38.216  5599  5911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 14:46:38.216  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 14:46:38.216  5599  5911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-04 14:46:38.216  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:46:38.217  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-04 14:46:38.217  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 14:46:38.217  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 14:46:38.217  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:46:38.217  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 14:46:38.217  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 14:46:38.217  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:46:38.218  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:38.218  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.221  5599  5647 D BluetoothAdapter: STATE_ON
11-04 14:46:38.222  5599  5647 D BluetoothLeScanner: could not find callback wrapper
11-04 14:46:38.222  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-04 14:46:38.222  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.223  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.223  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 14:46:38.223  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:38.225  5843  5861 D BtGatt.AdvertiseManager: message : 1
11-04 14:46:38.226  5843  5861 D BtGatt.AdvertiseManager: stop advertise for client 5
11-04 14:46:38.230   930  5916 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
11-04 14:46:38.231   930  5915 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
,11-04 14:46:38.233   930  5915 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 14:46:38.241  5843  5859 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-04 14:46:38.242  5843  5859 D BtGatt.GattService: Client app is not null!
,11-04 14:46:38.244  5843  5853 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 14:46:38.245  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 14:46:38.245  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.245  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-04 14:46:38.245  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:38.245  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.245  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:38.245  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-04 14:46:38.246  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:46:38.246  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:38.246  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.246  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 14:46:38.246  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.248  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.248  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:38.248  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:38.248  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.248  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.249  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.249  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.249  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:46:38.249  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-04 14:46:38.250  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:46:38.250  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.251   930  5916 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-04 14:46:38.251  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.251  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.252  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.252   930  5915 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-04 14:46:38.252  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 14:46:38.252  5599  5599 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 14:46:38.252  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:46:38.252  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 14:46:38.252  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:38.254   506   924 D CommandListener: Setting iface cfg
11-04 14:46:38.258   930  2933 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 14:46:38.260  5599  5647 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-04 14:46:38.260  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 14:46:38.261   930  5915 D DhcpClient: Scheduling renewal in 86399s
11-04 14:46:38.261  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 14:46:38.261  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-04 14:46:38.261  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 14:46:38.261  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:46:38.261  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-04 14:46:38.265  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:46:38.266  5599  5647 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:46:38.266  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 14:46:38.270   930  2933 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 14:46:38.270   930  2933 D WifiConfigStore: No blacklist allowed without epno enabled
11-04 14:46:38.271   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 14:46:38.271  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:46:38.272  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:46:38.272  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:46:38.272   930  2933 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 14:46:38.276   930  2944 D ConnectivityService: Adding iface wlan0 to network 102
,11-04 14:46:38.281  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:38.281  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 14:46:38.281  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 14:46:38.281  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-04 14:46:38.282  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 14:46:38.282  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:38.283  5599  5647 D BluetoothAdapter: STATE_ON
,11-04 14:46:38.286  5843  5883 D BtGatt.GattService: registerClient() - UUID=10b3b1c6-f57b-4d43-88bc-551ff5bcb7d4
,11-04 14:46:38.286  5843  5859 D BtGatt.GattService: onClientRegistered() - UUID=10b3b1c6-f57b-4d43-88bc-551ff5bcb7d4, clientIf=5
,11-04 14:46:38.287  5599  5639 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 14:46:38.288  5843  5853 D BtGatt.GattService: start scan with filters
,11-04 14:46:38.294  5843  5862 D BtGatt.ScanManager: handling starting scan
11-04 14:46:38.295  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 14:46:38.295  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.295  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-04 14:46:38.296  5843  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@78c3e30
11-04 14:46:38.296  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.296  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.296  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 14:46:38.296  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 14:46:38.296  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.296  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.296  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 14:46:38.297  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.299  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.299  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 14:46:38.300  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.300  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.300  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 14:46:38.300  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.300  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 14:46:38.301  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 14:46:38.302  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.303  5843  5859 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 14:46:38.303  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:38.304  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.304  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.304  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:38.304  5843  5862 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 14:46:38.310  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 14:46:38.311  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:46:38.311  5843  5862 D BtGatt.ScanManager: Starting BLE batch scan
11-04 14:46:38.311  5843  5862 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 14:46:38.314   930  2944 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 14:46:38.314   930  2944 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-04 14:46:38.315   930  2944 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-04 14:46:38.317   930  2944 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-04 14:46:38.318   930  2944 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-04 14:46:38.322  5843  5859 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 14:46:38.323  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:38.324   930  2944 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-04 14:46:38.327  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 14:46:38.327  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:38.327   930  2944 D ConnectivityService: scheduleUnvalidatedPrompt 102
11-04 14:46:38.327   930  2944 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-04 14:46:38.328   930  2944 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-04 14:46:38.328   930  2933 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 14:46:38.328   930  2944 D ConnectivityService:    accepting network in place of null
,11-04 14:46:38.328   930  2933 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 14:46:38.328   930  2944 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 14:46:38.346   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:46:38.365   506   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:46:38.368   930  2944 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-04 14:46:38.368  3707  3849 W QCNEJ   : |CORE| network available: 102
11-04 14:46:38.368   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:46:38.370  3707  3849 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-04 14:46:38.370   930   947 D Tethering: MasterInitialState.processMessage what=3
11-04 14:46:38.370   930  2944 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-04 14:46:38.371  3707  3849 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-04 14:46:38.371  3707  3849 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-04 14:46:38.372   930  2944 D ConnectivityService: handlePromptUnvalidated 101
,11-04 14:46:38.379  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:38.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:38.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:38.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:38.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:38.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:38.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:38.379  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:46:38.381  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:38.382  3926  3926 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-04 14:46:38.384  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:38.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:38.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:38.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:38.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:38.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:38.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:38.384  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:46:38.386  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:46:38.383  3939  3939 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 14:46:38.389  5599  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:46:38.389  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:46:38.389  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:46:38.389  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:46:38.389  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:46:38.389  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:38.389  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:46:38.389  5599  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:46:38.391  5599  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:46:38.391  3939  3939 D SystemUpdateService: onCreate
,11-04 14:46:38.394  3939  3939 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 14:46:38.404  3939  3939 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 14:46:38.410  3939  4287 I iu.UploadsManager: num queued entries: 0
,11-04 14:46:38.410  3939  4287 I iu.UploadsManager: num updated entries: 0
11-04 14:46:38.410  3939  4287 I iu.SyncManager: NEXT; no task
,11-04 14:46:38.413  3939  3939 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 14:46:38.415  3939  3939 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 14:46:38.416  5397  5397 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:46:38.420  5397  5397 D SprintDMHelper: simOperator: 
11-04 14:46:38.420  5397  5397 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 14:46:38.421  3939  5926 I SystemUpdateService: active receiver: enabled
,11-04 14:46:38.438   930  5914 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119079, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 14:46:38.442  3939  5926 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 14:46:38.446  3939  5926 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 14:46:38.447  3939  5926 I SystemUpdateService: now status is 0 (complete)
11-04 14:46:38.447  3939  5926 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 14:46:38.447  3939  5926 I SystemUpdateService: file has been verified
11-04 14:46:38.447  3939  5926 I SystemUpdateService: OTA package size = 21989297
,11-04 14:46:38.452  3939  5926 I SystemUpdateService: showing system update notification
,11-04 14:46:38.461   930   930 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 14:46:38.463  3939  3939 D SystemUpdateService: onDestroy
,11-04 14:46:38.510   930  5913 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 14:46:38.565   930  5913 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 13:46:38 GMT], X-Android-Received-Millis=[1478267198564], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478267198535]}
,11-04 14:46:38.566   930  2944 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 14:46:38.566   930  2944 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-04 14:46:38.566   930  2944 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-04 14:46:38.567   930  2944 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 14:46:38.742   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:38.800  5599  5599 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 14:46:38.801  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 14:46:38.801  5599  5599 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 14:46:38.830  5843  5843 D BtGatt.ScanManager: awakened up at time 119471
,11-04 14:46:38.833  5843  5862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 14:46:38.856  5843  5859 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
11-04 14:46:38.856  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:46:38.856  5843  5859 D BtGatt.GattService: current time is 119498424552
,11-04 14:46:38.857  5843  5859 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -76, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-04 14:46:38.862  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-04 14:46:38.864  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 14:46:38.868  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,11-04 14:46:38.868  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 14:46:38.869  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=119449298979}
,11-04 14:46:38.870  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 14:46:38.870  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=119499298979}
,11-04 14:46:39.369   930  2944 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,11-04 14:46:39.743   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:40.671   930  2933 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 11 -> obsolete
,11-04 14:46:40.744   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:41.307  5599  5647 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-04 14:46:41.307  5599  5647 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-04 14:46:41.307  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-04 14:46:41.308  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:46:41.308  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:46:41.310  5599  5647 D BluetoothAdapter: STATE_ON
11-04 14:46:41.312  5843  5873 D BtGatt.GattService: stopScan() - queue size =1
,11-04 14:46:41.315  5843  5880 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 14:46:41.317  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-04 14:46:41.317  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:41.317  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-04 14:46:41.318  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:46:41.318  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.318  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 14:46:41.319  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 14:46:41.319  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 14:46:41.319  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 14:46:41.320  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.321  5599  5647 D BluetoothAdapter: STATE_ON
11-04 14:46:41.328  5843  5854 D BtGatt.GattService: registerClient() - UUID=7a191df7-af83-4159-9fb5-6ba3e8abdfc1
11-04 14:46:41.329  5843  5843 D BtGatt.ScanManager: awakened up at time 121970
,11-04 14:46:41.330  5843  5859 D BtGatt.GattService: onClientRegistered() - UUID=7a191df7-af83-4159-9fb5-6ba3e8abdfc1, clientIf=5
,11-04 14:46:41.332  5599  5609 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 14:46:41.333  5843  5870 D BtGatt.GattService: start scan with filters
11-04 14:46:41.336  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 14:46:41.337  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:46:41.337  5843  5862 D BtGatt.ScanManager: stopping BLe Batch
11-04 14:46:41.339  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 14:46:41.339  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.339  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 14:46:41.339  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.339  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.339  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 14:46:41.339  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 14:46:41.340  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.340  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.340  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:41.340  5599  5647 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:46:41.340  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-04 14:46:41.340  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:46:41.341  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 14:46:41.342  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:46:41.342  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:46:41.342  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:46:41.342  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:46:41.343  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
,11-04 14:46:41.343  5599  5934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:46:41.343  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:46:41.343  5599  5934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:46:41.345  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:46:41.345  5599  5647 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:46:41.346  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 14:46:41.346  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:41.346  5843  5862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 14:46:41.347  5599  5934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 14:46:41.342  5873  5873 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34882]" dev="sockfs" ino=34882 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:46:41.342  5873  5873 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34882]" dev="sockfs" ino=34882 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 14:46:41.353  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:41.353  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.353  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 14:46:41.353  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:46:41.353  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
,11-04 14:46:41.353  5599  5647 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:46:41.353  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.354  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.354  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.354  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.355  5599  5647 D BluetoothAdapter: STATE_ON
,11-04 14:46:41.362  5843  5870 D BtGatt.GattService: registerClient() - UUID=fa68b41a-5776-4ac4-9b9e-d86d554512c6
,11-04 14:46:41.368  5843  5859 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-04 14:46:41.368  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:41.368  5843  5859 D BtGatt.GattService: current time is 122009774430
11-04 14:46:41.368  5843  5859 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -89, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -83, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -91, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -85, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-04 14:46:41.368  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-04 14:46:41.370  5843  5862 D BtGatt.ScanManager: handling starting scan
,11-04 14:46:41.369  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,11-04 14:46:41.387  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
11-04 14:46:41.387  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-04 14:46:41.387  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 14:46:41.387  5843  5859 D BtGatt.GattService: onClientRegistered() - UUID=fa68b41a-5776-4ac4-9b9e-d86d554512c6, clientIf=6
11-04 14:46:41.388  5599  5639 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-04 14:46:41.389  5843  5861 D BtGatt.AdvertiseManager: message : 0
,11-04 14:46:41.392  5843  5861 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:46:41.399  5843  5859 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-04 14:46:41.399  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:41.399  5843  5862 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 14:46:41.406  5843  5859 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-04 14:46:41.411  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-04 14:46:41.411  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:41.411  5843  5862 D BtGatt.ScanManager: Starting BLE batch scan
,11-04 14:46:41.411  5843  5862 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 14:46:41.416  5843  5859 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-04 14:46:41.416  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.417  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:41.417  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-04 14:46:41.417  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.417  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.417  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.417  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.417  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.417  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:41.417  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:41.418  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:41.418  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-04 14:46:41.418  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-04 14:46:41.418  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 14:46:41.420  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-04 14:46:41.420  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:41.423  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:41.423  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.423  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:41.424  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:41.424  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
11-04 14:46:41.424  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 14:46:41.424  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-85, mTimestampNanos=120010225785}
11-04 14:46:41.424  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-04 14:46:41.427  5843  5859 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 14:46:41.427  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-83, mTimestampNanos=119710225785}
11-04 14:46:41.427  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:41.427  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 14:46:41.427  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=120460225785}
,11-04 14:46:41.427  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-89, mTimestampNanos=119510225785}
11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-91, mTimestampNanos=119910225785}
11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:46:41.428  5599  5599 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-04 14:46:41.428  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-04 14:46:41.428  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-04 14:46:41.429  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 14:46:41.431  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 14:46:41.431  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-04 14:46:41.431  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 14:46:41.431  5599  5599 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 14:46:41.431  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:46:41.431  5599  5599 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 14:46:41.431  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-04 14:46:41.433  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 14:46:41.433  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:41.433   930  2933 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 11 -> obsolete
,11-04 14:46:41.745   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:41.932  5599  5599 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-04 14:46:41.933  5599  5599 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-04 14:46:41.933  5599  5599 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 14:46:42.746   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:43.746   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-04 14:46:44.431  5599  5647 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-04 14:46:44.431  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 14:46:44.432  5599  5647 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:46:44.432  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:46:44.432  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 14:46:44.433  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:46:44.433  5599  5934 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-04 14:46:44.433  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 14:46:44.433  5599  5934 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 14:46:44.433  5599  5647 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:46:44.433  5599  5934 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-04 14:46:44.433  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 14:46:44.434  5599  5599 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:46:44.434  5599  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36ff704 removed from the list
11-04 14:46:44.434  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-04 14:46:44.434  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 14:46:44.434  5599  5599 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:46:44.434  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 14:46:44.434  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 14:46:44.434  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 14:46:44.435  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:44.435  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.435  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 14:46:44.437  5599  5647 D BluetoothAdapter: STATE_ON
,11-04 14:46:44.439  5843  5870 D BtGatt.GattService: stopScan() - queue size =1
11-04 14:46:44.440  5843  5883 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 14:46:44.441  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 14:46:44.442  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.442  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 14:46:44.442  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.442  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.443  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:46:44.443  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-04 14:46:44.443  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.443  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:44.443  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-04 14:46:44.443  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.447  5843  5843 D BtGatt.ScanManager: awakened up at time 125089
,11-04 14:46:44.451  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:44.451  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:46:44.451  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.451  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.451  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.451  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.451  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-04 14:46:44.451  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.453  5843  5861 D BtGatt.AdvertiseManager: message : 1
11-04 14:46:44.453  5843  5861 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-04 14:46:44.456  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-04 14:46:44.456  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:44.456  5843  5862 D BtGatt.ScanManager: stopping BLe Batch
,11-04 14:46:44.462  5843  5859 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-04 14:46:44.462  5843  5859 D BtGatt.GattService: Client app is not null!
,11-04 14:46:44.463  5843  5870 D BtGatt.GattService: unregisterClient() - clientIf=6
11-04 14:46:44.463  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 14:46:44.464  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.464  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 14:46:44.464  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:44.464  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.464  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.465  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 14:46:44.465  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:46:44.465  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.465  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.466  5599  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 14:46:44.466  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.467  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.467  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:44.467  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:44.467  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.467  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.467  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.468  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.468  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:46:44.468  5599  5647 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 14:46:44.468  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:46:44.469  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:44.470  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-66,5,main], id: 66
,11-04 14:46:44.470  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.470  5599  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-66,5,main], id: 66
11-04 14:46:44.470  5599  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50794ed removed from the list
11-04 14:46:44.470  5599  5647 D io.jxcore.node.ConnectivityMonitor: stop
11-04 14:46:44.470  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 14:46:44.470  5599  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:46:44.470  5599  5599 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:46:44.470  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:46:44.470  5599  5599 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:46:44.472  5599  5647 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,11-04 14:46:44.472  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 14:46:44.472  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 14:46:44.472  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 14:46:44.472  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-04 14:46:44.472  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-04 14:46:44.472  5599  5647 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 14:46:44.473  5599  5647 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-04 14:46:44.474  5599  5647 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-04 14:46:44.474  5599  5647 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,11-04 14:46:44.475  5599  5647 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-04 14:46:44.475  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 14:46:44.475  5599  5647 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-04 14:46:44.476  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:44.476  5843  5862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-04 14:46:44.476  5599  5647 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-04 14:46:44.477  5599  5647 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-04 14:46:44.478  5599  5647 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-04 14:46:44.490  5843  5859 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-04 14:46:44.490  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:46:44.491  5843  5859 D BtGatt.GattService: current time is 125132474918
11-04 14:46:44.491  5843  5859 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -88, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -83, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -85, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-04 14:46:44.491  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 14:46:44.491  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 14:46:44.491  5843  5859 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-04 14:46:44.971  5599  5599 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 14:46:46.333   930  2944 D ConnectivityService: handlePromptUnvalidated 102
,11-04 14:46:46.483  5599  5647 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-04 14:46:46.612  5599  5936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 14:46:46.612  5599  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:46:47.416  5599  5936 W !!      : call onHalfStreamCopied
,11-04 14:46:47.416  5599  5936 I testCopyDataAndClose: closing input stream
,11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 14:46:48.196  5599  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 14:46:48.747   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:49.424   930  2933 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-04 14:46:49.749   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:50.233   930  2933 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,11-04 14:46:50.750   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:51.751   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:52.543  5599  5647 I StreamCopyingThreadTest: Starting test: testRun
,11-04 14:46:52.547  5599  5937 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:46:52.547  5599  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:46:52.752   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:46:53.752   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-04 14:46:55.264   930  3179 I ActivityManager: Start proc 5939:com.google.android.youtube/u0a75 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,11-04 14:46:55.298  5939  5939 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm64
,11-04 14:46:55.382  5939  5951 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-04 14:46:55.463  5939  5951 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-04 14:46:55.508  5939  5951 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-04 14:46:55.525  5964  5964 I dex2oat : /system/bin/dex2oat -j2 --dex-file=/data/user/0/com.google.android.youtube/cache/ads439191734.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads439191734.dex
,11-04 14:46:55.541  5939  5939 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,11-04 14:46:55.561  5964  5964 I dex2oat : dex2oat took 37.197ms (threads: 2) arena alloc=159KB java alloc=37KB native alloc=1258KB free=1301KB
,11-04 14:46:55.701  5939  5939 W InstanceID/Rpc: Found 10012
,11-04 14:46:55.749   930  3179 I ActivityManager: Killing 5473:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-04 14:46:55.758  3632  3804 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-04 14:46:55.758  3632  3804 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-04 14:46:55.795  3560  3560 I ConfigService: onCreate
,11-04 14:46:57.553  5599  5938 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-04 14:46:57.556  5599  5647 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-04 14:46:57.718  5599  6018 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 14:46:57.718  5599  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 166, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 14:46:59.409  5599  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 14:47:00.816   930  5914 D NetlinkSocketObserver: NeighborEvent{elapsedMs=141457, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-04 14:47:00.821  3560  3560 I ConfigService: onDestroy
,11-04 14:47:03.627  5599  5647 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-04 14:47:03.630  5599  6019 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:47:03.630  5599  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:47:03.630  5599  6019 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:47:03.630  5599  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 14:47:03.630  5599  6019 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 14:47:03.630  5599  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 14:47:03.630  5599  6019 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-04 14:47:03.630  5599  6019 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 14:47:03.631  5599  6019 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 14:47:03.631  5599  6019 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-04 14:47:03.631  5599  6019 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 14:47:03.631  5599  6019 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:47:03.631  5599  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-04 14:47:03.633  5599  5647 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-04 14:47:03.633  5599  5647 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-04 14:47:03.634  5599  5647 I StreamCopyingThreadTest: Starting test: testRunWithException
11-04 14:47:03.636  5599  6020 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:47:03.636  5599  6020 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 14:47:03.637  5599  6020 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 172, thread name: My test thread name): Test exception.
,11-04 14:47:03.637  5599  6020 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:47:03.637  5599  6020 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-04 14:47:03.637  5599  6020 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-04 14:47:03.637  5599  6020 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:47:03.637  5599  6020 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-04 14:47:03.639  5599  5647 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-04 14:47:03.639  5599  5647 E com.test.thalitest.ThaliTestRunner: 
11-04 14:47:03.639  5599  5647 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-04 14:47:03.639  5599  5647 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.,junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-04 1,4:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-04 14:47:03.640  5599  5647 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runne,rs.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:47:03.641  5599  5647 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,11-04 14:47:03.643  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG UnitTest_app: 'Running unit tests'
11-04 14:47:03.643  5599  5647 I jxcore-log: 
,11-04 14:47:03.643  5599  5647 I jxcore-log: *Native tests were executed*
11-04 14:47:03.643  5599  5647 I jxcore-log: 
11-04 14:47:03.643  5599  5647 I jxcore-log: Total number of executed tests:  82
11-04 14:47:03.643  5599  5647 I jxcore-log: 
11-04 14:47:03.643  5599  5647 I jxcore-log: Number of passed tests:  80
11-04 14:47:03.643  5599  5647 I jxcore-log: 
,11-04 14:47:03.644  5599  5647 I jxcore-log: Number of failed tests:  2
11-04 14:47:03.644  5599  5647 I jxcore-log: 
11-04 14:47:03.644  5599  5647 I jxcore-log: Number of ignored tests:  0
11-04 14:47:03.644  5599  5647 I jxcore-log: 
11-04 14:47:03.644  5599  5647 I jxcore-log: Total duration:  46598
,11-04 14:47:03.644  5599  5647 I jxcore-log: 
11-04 14:47:03.644  5599  5647 I jxcore-log: Failed to execute UT.
11-04 14:47:03.644  5599  5647 I jxcore-log: 
11-04 14:47:03.645  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-04 14:47:03.645  5599  5647 I jxcore-log: ,
11-04 14:47:03.646  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-04 14:47:03.646  5599  5647 I jxcore-log: 
11-04 14:47:03.649  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.649  5599  5647 I jxcore-log: 
11-04 14:47:03.649  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.649  5599  5647 I jxcore-log: 
,11-04 14:47:03.650  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.650  5599  5647 I jxcore-log: 
11-04 14:47:03.651  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.651  5599  5647 I jxcore-log: 
11-04 14:47:03.652  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.652  5599  5647 I jxcore-log: 
11-04 14:47:03.652  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.652  5599  5647 I jxcore-log: 
11-04 14:47:03.652  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 14:47:03.652  5599  5647 I jxcore-log: ,
11-04 14:47:03.652  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 14:47:03.652  5599  5647 I jxcore-log: 
11-04 14:47:03.653  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 14:47:03.653  5599  5647 I jxcore-log: 
11-04 14:47:03.653  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 14:47:03.653  5599  5647 I jxcore-log: 
11-04 14:47:03.653  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.653  5599  5647 I jxcore-log: 
11-04 14:47:03.654  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.654  5599  5647 I jxcore-log: 
11-04 14:47:03.654  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
,11-04 14:47:03.654  5599  5647 I jxcore-log: 
11-04 14:47:03.654  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.654  5599  5647 I jxcore-log: 
11-04 14:47:03.654  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.654  5599  5647 I jxcore-log: 
,11-04 14:47:03.654  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.654  5599  5647 I jxcore-log: 
11-04 14:47:03.655  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.655  5599  5647 I jxcore-log: 
11-04 14:47:03.655  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.655  5599  5647 I jxcore-log: 
,11-04 14:47:03.655  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 14:47:03.655  5599  5647 I jxcore-log: 
11-04 14:47:03.655  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:47:03.655  5599  5647 I jxcore-log: 
11-04 14:47:03.656  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.656  5599  5647 I jxcore-log: 
,11-04 14:47:03.656  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:47:03.656  5599  5647 I jxcore-log: 
11-04 14:47:03.656  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.656  5599  5647 I jxcore-log: 
11-04 14:47:03.656  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:47:03.656  5599  5647 I jxcore-log: 
11-04 14:47:03.656  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.656  5599  5647 I jxcore-log: 
11-04 14:47:03.657  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.657  5599  5647 I jxcore-log: 
,11-04 14:47:03.657  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.657  5599  5647 I jxcore-log: 
11-04 14:47:03.657  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.657  5599  5647 I jxcore-log: 
11-04 14:47:03.657  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.657  5599  5647 I jxcore-log: 
11-04 14:47:03.659  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.659  5599  5647 I jxcore-log: 
,11-04 14:47:03.659  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.659  5599  5647 I jxcore-log: 
11-04 14:47:03.659  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.659  5599  5647 I jxcore-log: 
11-04 14:47:03.659  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.659  5599  5647 I jxcore-log: 
11-04 14:47:03.660  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.660  5599  5647 I jxcore-log: 
,11-04 14:47:03.660  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.660  5599  5647 I jxcore-log: 
11-04 14:47:03.660  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.660  5599  5647 I jxcore-log: 
11-04 14:47:03.660  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.660  5599  5647 I jxcore-log: 
11-04 14:47:03.660  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.660  5599  5647 I jxcore-log: 
11-04 14:47:03.660  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,11-04 14:47:03.660  5599  5647 I jxcore-log: 
11-04 14:47:03.661  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.661  5599  5647 I jxcore-log: 
11-04 14:47:03.661  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.661  5599  5647 I jxcore-log: 
,11-04 14:47:03.661  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.661  5599  5647 I jxcore-log: 
11-04 14:47:03.661  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.661  5599  5647 I jxcore-log: 
11-04 14:47:03.662  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.662  5599  5647 I jxcore-log: 
11-04 14:47:03.662  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.662  5599  5647 I jxcore-log: 
,11-04 14:47:03.662  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.662  5599  5647 I jxcore-log: 
11-04 14:47:03.662  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.662  5599  5647 I jxcore-log: 
11-04 14:47:03.662  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.662  5599  5647 I jxcore-log: 
11-04 14:47:03.663  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.663  5599  5647 I jxcore-log: 
,11-04 14:47:03.663  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.663  5599  5647 I jxcore-log: 
11-04 14:47:03.663  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.663  5599  5647 I jxcore-log: 
11-04 14:47:03.663  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.663  5599  5647 I jxcore-log: 
11-04 14:47:03.663  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.663  5599  5647 I jxcore-log: 
11-04 14:47:03.663  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}',
11-04 14:47:03.663  5599  5647 I jxcore-log: 
11-04 14:47:03.664  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.664  5599  5647 I jxcore-log: 
11-04 14:47:03.664  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.664  5599  5647 I jxcore-log: 
11-04 14:47:03.664  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.664  5599  5647 I jxcore-log: 
,11-04 14:47:03.664  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.664  5599  5647 I jxcore-log: 
11-04 14:47:03.664  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.664  5599  5647 I jxcore-log: 
11-04 14:47:03.665  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.665  5599  5647 I jxcore-log: 
11-04 14:47:03.665  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.665  5599  5647 I jxcore-log: 
,11-04 14:47:03.665  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.665  5599  5647 I jxcore-log: 
11-04 14:47:03.665  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.665  5599  5647 I jxcore-log: 
11-04 14:47:03.665  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:47:03.665  5599  5647 I jxcore-log: 
11-04 14:47:03.666  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.666  5599  5647 I jxcore-log: 
11-04 14:47:03.666  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:47:03.666  5599  5647 I jxcore-log: 
,11-04 14:47:03.666  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.666  5599  5647 I jxcore-log: 
11-04 14:47:03.666  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:47:03.666  5599  5647 I jxcore-log: 
11-04 14:47:03.666  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.666  5599  5647 I jxcore-log: 
11-04 14:47:03.666  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.666  5599  5647 I jxcore-log: 
,11-04 14:47:03.667  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.667  5599  5647 I jxcore-log: 
11-04 14:47:03.667  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.667  5599  5647 I jxcore-log: 
11-04 14:47:03.667  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.667  5599  5647 I jxcore-log: 
11-04 14:47:03.667  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.667  5599  5647 I jxcore-log: 
11-04 14:47:03.667  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.667  5599  5647 I jxcore-log: 
,11-04 14:47:03.668  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:47:03.668  5599  5647 I jxcore-log: 
11-04 14:47:03.668  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.668  5599  5647 I jxcore-log: 
11-04 14:47:03.668  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 14:47:03.668  5599  5647 I jxcore-log: 
11-04 14:47:03.668  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.668  5599  5647 I jxcore-log: 
11-04 14:47:03.668  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.668  5599  5647 I jxcore-log: 
11-04 14:47:03.669  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
,11-04 14:47:03.669  5599  5647 I jxcore-log: 
11-04 14:47:03.669  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.669  5599  5647 I jxcore-log: 
11-04 14:47:03.669  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:47:03.669  5599  5647 I jxcore-log: 
11-04 14:47:03.669  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:47:03.669  5599  5647 I jxcore-log: 
11-04 14:47:03.670  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 14:47:03.670  5599  5647 I jxcore-log: 
,11-04 14:47:03.670  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-04 14:47:03.670  5599  5647 I jxcore-log: 
11-04 14:47:03.670  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 14:47:03.670  5599  5647 I jxcore-log: 
11-04 14:47:03.671  5599  5599 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-04 14:47:03.675  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-04 14:47:03.675  5599  5647 I jxcore-log: 
11-04 14:47:03.676  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - WARN testUtils: 'myNameCallback not set!'
11-04 14:47:03.676  5599  5647 I jxcore-log: 
,11-04 14:47:03.677  5599  5647 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-04 14:47:03.677  5599  5647 I jxcore-log: 2016-11-04 13:47:03 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-04 14:47:03.677  5599  5647 I jxcore-log: 
,11-04 14:47:03.753   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:47:04.755   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:47:05.731  5599  5647 I jxcore-log: 2016-11-04 13:47:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-04 14:47:05.731  5599  5647 I jxcore-log: 
,11-04 14:47:05.756   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:47:06.070  5599  5647 I jxcore-log: 2016-11-04 13:47:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-04 14:47:06.070  5599  5647 I jxcore-log: 
,11-04 14:47:06.082  5599  5647 I jxcore-log: 2016-11-04 13:47:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-04 14:47:06.082  5599  5647 I jxcore-log: 
,11-04 14:47:06.757   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:47:07.185  5599  5647 I jxcore-log: 2016-11-04 13:47:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-04 14:47:07.185  5599  5647 I jxcore-log: 
,11-04 14:47:07.360  5599  5647 I jxcore-log: 2016-11-04 13:47:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-04 14:47:07.360  5599  5647 I jxcore-log: 
,11-04 14:47:07.365  5599  5647 I jxcore-log: 2016-11-04 13:47:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-04 14:47:07.365  5599  5647 I jxcore-log: 
,11-04 14:47:07.370  5599  5647 I jxcore-log: 2016-11-04 13:47:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-04 14:47:07.370  5599  5647 I jxcore-log: 
,11-04 14:47:07.758   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:47:07.854  5599  5647 I jxcore-log: 2016-11-04 13:47:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-04 14:47:07.854  5599  5647 I jxcore-log: 
,11-04 14:47:07.898  5599  5647 I jxcore-log: 2016-11-04 13:47:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-04 14:47:07.898  5599  5647 I jxcore-log: 
,11-04 14:47:07.911  5599  5647 I jxcore-log: 2016-11-04 13:47:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-04 14:47:07.911  5599  5647 I jxcore-log: 
,11-04 14:47:07.916  5599  5647 I jxcore-log: 2016-11-04 13:47:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-04 14:47:07.916  5599  5647 I jxcore-log: 
,11-04 14:47:08.207  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-04 14:47:08.207  5599  5647 I jxcore-log: 
,11-04 14:47:08.348  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-04 14:47:08.348  5599  5647 I jxcore-log: 
,11-04 14:47:08.732  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-04 14:47:08.732  5599  5647 I jxcore-log: 
,11-04 14:47:08.758   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-04 14:47:08.769  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-04 14:47:08.769  5599  5647 I jxcore-log: 
,11-04 14:47:08.776  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-04 14:47:08.776  5599  5647 I jxcore-log: 
,11-04 14:47:08.782  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-04 14:47:08.782  5599  5647 I jxcore-log: 
,11-04 14:47:08.791  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-04 14:47:08.791  5599  5647 I jxcore-log: 
,11-04 14:47:08.805  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-04 14:47:08.805  5599  5647 I jxcore-log: 
,11-04 14:47:08.811  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-04 14:47:08.811  5599  5647 I jxcore-log: 
,11-04 14:47:08.840  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-04 14:47:08.840  5599  5647 I jxcore-log: 
,11-04 14:47:08.878  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-04 14:47:08.878  5599  5647 I jxcore-log: 
,11-04 14:47:08.885  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-04 14:47:08.885  5599  5647 I jxcore-log: 
,11-04 14:47:08.892  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-04 14:47:08.892  5599  5647 I jxcore-log: 
,11-04 14:47:08.907  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-04 14:47:08.907  5599  5647 I jxcore-log: 
,11-04 14:47:08.911  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-04 14:47:08.911  5599  5647 I jxcore-log: 
,11-04 14:47:08.917  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-04 14:47:08.917  5599  5647 I jxcore-log: 
,11-04 14:47:08.922  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-04 14:47:08.922  5599  5647 I jxcore-log: 
,11-04 14:47:08.935  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-04 14:47:08.935  5599  5647 I jxcore-log: 
,11-04 14:47:08.942  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-04 14:47:08.942  5599  5647 I jxcore-log: 
,11-04 14:47:08.964  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-04 14:47:08.964  5599  5647 I jxcore-log: 
,11-04 14:47:08.975  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-04 14:47:08.975  5599  5647 I jxcore-log: 
,11-04 14:47:08.987  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-04 14:47:08.987  5599  5647 I jxcore-log: 
,11-04 14:47:08.997  5599  5647 I jxcore-log: 2016-11-04 13:47:08 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-04 14:47:08.997  5599  5647 I jxcore-log: 
,11-04 14:47:09.010  5599  5647 I jxcore-log: 2016-11-04 13:47:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-04 14:47:09.010  5599  5647 I jxcore-log: 
,11-04 14:47:09.020  5599  5647 I jxcore-log: 2016-11-04 13:47:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-04 14:47:09.020  5599  5647 I jxcore-log: 
,11-04 14:47:09.027  5599  5647 I jxcore-log: 2016-11-04 13:47:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-04 14:47:09.027  5599  5647 I jxcore-log: 
,11-04 14:47:09.032  5599  5647 I jxcore-log: 2016-11-04 13:47:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-04 14:47:09.032  5599  5647 I jxcore-log: 
,11-04 14:47:09.038  5599  5647 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-04 14:47:09.039  5599  5647 I jxcore-log: 2016-11-04 13:47:09 - INFO testUtils: 'BLE multiple advertisement supported'
11-04 14:47:09.039  5599  5647 I jxcore-log: 
,11-04 14:47:09.118  5599  5647 I jxcore-log: 2016-11-04 13:47:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:09.118  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:09.118  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:09.118  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:09.118  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:09.118  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:09.118  5599  5647 I jxcore-log: 
,11-04 14:47:09.416  5599  5647 I jxcore-log: 2016-11-04 13:47:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:09.416  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:09.416  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:09.416  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:09.416  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:09.416  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:09.416  5599  5647 I jxcore-log: 
,11-04 14:47:09.419  5599  5647 I jxcore-log: 2016-11-04 13:47:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:09.419  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:09.419  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:09.419  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:09.419  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:09.419  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:09.419  5599  5647 I jxcore-log: 
,11-04 14:47:10.012  5599  5647 I jxcore-log: 2016-11-04 13:47:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:10.012  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:10.012  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:10.012  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:10.012  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:10.012  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:10.012  5599  5647 I jxcore-log: 
,11-04 14:47:10.016  5599  5647 I jxcore-log: 2016-11-04 13:47:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:10.016  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:10.016  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:10.016  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:10.016  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:10.016  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:10.016  5599  5647 I jxcore-log: 
,11-04 14:47:10.732  5599  5647 I jxcore-log: 2016-11-04 13:47:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:10.732  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:10.732  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:10.732  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:10.732  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:10.732  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:10.732  5599  5647 I jxcore-log: 
,11-04 14:47:10.734  5599  5647 I jxcore-log: 2016-11-04 13:47:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:10.734  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:10.734  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:10.734  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:10.734  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:10.734  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:10.734  5599  5647 I jxcore-log: 
,11-04 14:47:11.765  5599  5647 I jxcore-log: 2016-11-04 13:47:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:11.765  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:11.765  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:11.765  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:11.765  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:11.765  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:11.765  5599  5647 I jxcore-log: 
,11-04 14:47:11.770  5599  5647 I jxcore-log: 2016-11-04 13:47:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:11.770  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:11.770  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:11.770  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:11.770  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:11.770  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:11.770  5599  5647 I jxcore-log: 
,11-04 14:47:11.788   930   950 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-04 14:47:11.789  3402  3402 W Binder_6: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33056]" dev="sockfs" ino=33056 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:47:11.792  3402  3402 W Binder_6: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[33056]" dev="sockfs" ino=33056 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:47:11.799  3632  3632 I Keyboard.Facilitator: onFinishInput()
,11-04 14:47:11.803   930   950 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 14:47:11.803   930   950 I Adreno  : Build Date                       : 12/06/15
11-04 14:47:11.803   930   950 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 14:47:11.803   930   950 I Adreno  : Local Branch                     : mybranch17112971
11-04 14:47:11.803   930   950 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 14:47:11.803   930   950 I Adreno  : Remote Branch                    : NONE
11-04 14:47:11.803   930   950 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 14:47:11.834   382   405 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (181 us)
,11-04 14:47:12.524  5599  5599 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 14:47:12.524  5599  5599 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-04 14:47:12.552   930   950 I sensors : batch
,11-04 14:47:12.553   930   950 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-04 14:47:12.554  5599  5599 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8475fcf Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f43b621, 16908290=android.view.AbsSavedState$1@f43b621}, android:focusedViewId=100}]}]
11-04 14:47:12.554  5599  5599 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-04 14:47:12.554  5599  5599 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 14:47:12.555  5599  5599 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-04 14:47:12.558   930  2732 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-04 14:47:12.559   930   950 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-04 14:47:12.559   930   950 I sensors : activate
,11-04 14:47:12.560   382   382 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7fac5c3c00
11-04 14:47:12.560   930   948 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-04 14:47:12.560   382   382 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-04 14:47:12.564   930  2732 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-04 14:47:12.786  5599  5647 I jxcore-log: 2016-11-04 13:47:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:12.786  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:12.786  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:12.786  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:12.786  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:12.786  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:12.786  5599  5647 I jxcore-log: 
,11-04 14:47:12.788  5599  5647 I jxcore-log: 2016-11-04 13:47:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:12.788  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:12.788  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:12.788  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:12.788  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:12.788  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:12.788  5599  5647 I jxcore-log: 
,11-04 14:47:12.791   506   924 D TetherController: Setting IP forward enable = 1
,11-04 14:47:12.852   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-04 14:47:12.853   382   382 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-04 14:47:12.853   930  3071 D SurfaceControl: Excessive delay in setPowerMode(): 292ms
,11-04 14:47:12.858   930   950 I DreamManagerService: Entering dreamland.
,11-04 14:47:12.858   930   950 I PowerManagerService: Dozing...
11-04 14:47:12.859   930   945 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-04 14:47:12.875  3884  3884 W Binder_8: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[34661]" dev="sockfs" ino=34661 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:47:12.875  3884  3884 W Binder_8: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[34661]" dev="sockfs" ino=34661 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:47:12.880   930  3402 I sensors : batch
11-04 14:47:12.881   930  3402 I sensors : activate
,11-04 14:47:12.884   930  2732 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-04 14:47:12.884   930  2732 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-04 14:47:12.890   511   511 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-04 14:47:12.893   930  2933 E native  : do suspend false
,11-04 14:47:12.899   930  2933 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 14:47:12.910  3733  4728 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-04 14:47:12.910  3733  4728 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 14:47:12.910  3733  4728 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 14:47:12.910   524  1358 D         : oem-qmi: Connection accepted
,11-04 14:47:12.910   524  1358 D         : oem-qmi: Waiting to accept connection
,11-04 14:47:12.912   930   930 I sensors : activate
,11-04 14:47:12.912  3733  4728 D         : oem_qmi_lib:output 0
11-04 14:47:12.912  3733  4728 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 14:47:12.913   511  3018 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
11-04 14:47:12.914   930  2933 E native  : do suspend true
11-04 14:47:12.915   930  2732 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-04 14:47:12.932  3733  4728 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-04 14:47:12.932  3733  4728 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 14:47:12.932  3733  4728 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 14:47:12.932   524  1358 D         : oem-qmi: Connection accepted
11-04 14:47:12.932   524  1358 D         : oem-qmi: Waiting to accept connection
,11-04 14:47:12.934  3733  4728 D         : oem_qmi_lib:output 0
,11-04 14:47:12.934  3733  4728 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 14:47:13.391   930  2933 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,11-04 14:47:13.826  5599  5647 I jxcore-log: 2016-11-04 13:47:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:13.826  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:13.826  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:13.826  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:13.826  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:13.826  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:13.826  5599  5647 I jxcore-log: 
,11-04 14:47:13.831  5599  5647 I jxcore-log: 2016-11-04 13:47:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:13.831  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:13.831  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:13.831  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:13.831  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:13.831  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:13.831  5599  5647 I jxcore-log: 
,11-04 14:47:14.102   930  5914 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-04 14:47:14.863  5599  5647 I jxcore-log: 2016-11-04 13:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:14.863  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:14.863  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:14.863  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:14.863  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:14.863  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:14.863  5599  5647 I jxcore-log: 
,11-04 14:47:14.868  5599  5647 I jxcore-log: 2016-11-04 13:47:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:14.868  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:14.868  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:14.868  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:14.868  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:14.868  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:14.868  5599  5647 I jxcore-log: 
,11-04 14:47:15.907  5599  5647 I jxcore-log: 2016-11-04 13:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:15.907  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:15.907  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:15.907  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:15.907  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:15.907  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:15.907  5599  5647 I jxcore-log: 
,11-04 14:47:15.913  5599  5647 I jxcore-log: 2016-11-04 13:47:15 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:15.913  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:15.913  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:15.913  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:15.913  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:15.913  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:15.913  5599  5647 I jxcore-log: 
,11-04 14:47:16.946  5599  5647 I jxcore-log: 2016-11-04 13:47:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:16.946  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:16.946  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:16.946  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:16.946  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:16.946  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:16.946  5599  5647 I jxcore-log: 
,11-04 14:47:16.951  5599  5647 I jxcore-log: 2016-11-04 13:47:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:16.951  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:16.951  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:16.951  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:16.951  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:16.951  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:16.951  5599  5647 I jxcore-log: 
,11-04 14:47:17.074  4071  4475 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-04 14:47:18.024  5599  5647 I jxcore-log: 2016-11-04 13:47:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:18.024  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:18.024  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:18.024  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:18.024  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:18.024  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:18.024  5599  5647 I jxcore-log: 
,11-04 14:47:18.030  5599  5647 I jxcore-log: 2016-11-04 13:47:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:18.030  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:18.030  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:18.030  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:18.030  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:18.030  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:18.030  5599  5647 I jxcore-log: 
,11-04 14:47:18.279   930  2933 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,11-04 14:47:19.076  5599  5647 I jxcore-log: 2016-11-04 13:47:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:19.076  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:19.076  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:19.076  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:19.076  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:19.076  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:19.076  5599  5647 I jxcore-log: 
,11-04 14:47:19.082  5599  5647 I jxcore-log: 2016-11-04 13:47:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:19.082  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:19.082  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:19.082  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:19.082  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:19.082  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:19.082  5599  5647 I jxcore-log: 
,11-04 14:47:20.119  5599  5647 I jxcore-log: 2016-11-04 13:47:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:20.119  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:20.119  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:20.119  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:20.119  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:20.119  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:20.119  5599  5647 I jxcore-log: 
,11-04 14:47:20.123  5599  5647 I jxcore-log: 2016-11-04 13:47:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:20.123  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:20.123  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:20.123  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:20.123  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:20.123  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:20.123  5599  5647 I jxcore-log: 
,11-04 14:47:21.155  5599  5647 I jxcore-log: 2016-11-04 13:47:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:21.155  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:21.155  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:21.155  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:21.155  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:21.155  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:21.155  5599  5647 I jxcore-log: 
,11-04 14:47:21.159  5599  5647 I jxcore-log: 2016-11-04 13:47:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:21.159  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:21.159  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:21.159  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:21.159  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:21.159  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:21.159  5599  5647 I jxcore-log: 
,11-04 14:47:22.186  5599  5647 I jxcore-log: 2016-11-04 13:47:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:22.186  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:22.186  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:22.186  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:22.186  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:22.186  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:22.186  5599  5647 I jxcore-log: 
,11-04 14:47:22.190  5599  5647 I jxcore-log: 2016-11-04 13:47:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:22.190  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:22.190  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:22.190  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:22.190  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:22.190  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:22.190  5599  5647 I jxcore-log: 
,11-04 14:47:23.229  5599  5647 I jxcore-log: 2016-11-04 13:47:23 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:47:23.229  5599  5647 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:47:23.229  5599  5647 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:47:23.229  5599  5647 I jxcore-log: emit@events.js:82:1
11-04 14:47:23.229  5599  5647 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:47:23.229  5599  5647 I jxcore-log: emit@events.js:82:1'
11-04 14:47:23.229  5599  5647 I jxcore-log: 
,11-04 14:47:23.241  5599  5647 E jxcore  : Error!: error is undefined
11-04 14:47:23.241  5599  5647 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-04 14:47:23.249  5599  5647 I jxcore-log: 2016-11-04 13:47:23 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-04 14:47:23.249  5599  5647 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-04 14:47:23.249  5599  5647 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-04 14:47:23.249  5599  5647 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-04 14:47:23.249  5599  5647 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-04 14:47:23.249  5599  5647 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-04 14:47:23.249  5599  5647 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-04 14:47:23.249  5599  5647 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-04 14:47:23.251  5599  5647 I jxcore-log: 2016-11-04 13:47:23 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-04 14:47:23.251  5599  5647 I jxcore-log: 
,11-04 14:47:23.252  5599  5647 E jxcore-log: TypeError: 
11-04 14:47:23.252  5599  5647 E jxcore-log: error is undefined
11-04 14:47:23.252  5599  5647 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-04 14:47:23.252  5599  5647 E jxcore-log: 
,11-04 14:47:23.316   930  2913 W InputDispatcher: channel 'f2bbde9 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-04 14:47:23.316   930  2913 E InputDispatcher: channel 'f2bbde9 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-04 14:47:23.327   930  3179 D GraphicsStats: Buffer count: 2
,11-04 14:47:23.328   930   940 I WindowState: WIN DEATH: Window{f2bbde9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-04 14:47:23.328   930  2940 D WifiService: Client connection lost with reason: 4
,11-04 14:47:23.329   930   940 W InputDispatcher: Attempted to unregister already unregistered input channel 'f2bbde9 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-04 14:47:23.341   526   526 I Zygote  : Process 5599 exited cleanly (139)
,11-04 14:47:23.344   930  4983 I ActivityManager: Process com.test.thalitest (pid 5599) has died
,11-04 14:47:23.362   930  4983 I ActivityManager: Start proc 6067:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-04 14:47:23.436  6067  6067 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-04 14:47:23.464  6067  6067 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 14:47:23.470  6067  6067 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4109-4111)
,11-04 14:47:23.470  6067  6067 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 14:47:23.480  6067  6067 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a850418}
11-04 14:47:23.480  6067  6067 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 14:47:23.481  6067  6067 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 14:47:23.484  6067  6067 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 14:47:23.485  6067  6067 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 14:47:23.495  6067  6067 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 14:47:23.504  6067  6067 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 14:47:23.504  6067  6067 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 14:47:23.504  6067  6067 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 14:47:23.504  6067  6067 I Adreno  : Build Date                       : 12/06/15
11-04 14:47:23.504  6067  6067 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 14:47:23.504  6067  6067 I Adreno  : Local Branch                     : mybranch17112971
11-04 14:47:23.504  6067  6067 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 14:47:23.504  6067  6067 I Adreno  : Remote Branch                    : NONE
11-04 14:47:23.504  6067  6067 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 14:47:23.538   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c7b8677:true
,11-04 14:47:23.552   407   407 W Binder_2: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[16072]" dev="sockfs" ino=16072 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:47:23.552   407   407 W Binder_2: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[16072]" dev="sockfs" ino=16072 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:47:23.567  6067  6067 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 14:47:23.575  6067  6067 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 14:47:23.599   746   746 W Binder_3: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[34686]" dev="sockfs" ino=34686 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:47:23.599   746   746 W Binder_3: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[34686]" dev="sockfs" ino=34686 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 14:47:23.602  6067  6103 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 14:47:23.602   940   940 W Binder_1: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[16084]" dev="sockfs" ino=16084 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:47:23.602   940   940 W Binder_1: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[16084]" dev="sockfs" ino=16084 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:47:23.606  6067  6090 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 14:47:23.640  6067  6103 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 14:47:23.654   930  3812 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5599 uid 10077
,11-04 14:47:23.652  3812  3812 W Binder_7: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[36582]" dev="sockfs" ino=36582 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:47:23.652  3812  3812 W Binder_7: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[36582]" dev="sockfs" ino=36582 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:47:23.652  3111  3111 W Binder_3: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[36581]" dev="sockfs" ino=36581 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:47:23.658  3632  3632 I Keyboard.Facilitator: onFinishInput()
11-04 14:47:23.652  3111  3111 W Binder_3: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[36581]" dev="sockfs" ino=36581 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:47:23.675   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +288ms (total +329ms)
,11-04 14:47:23.677  6067  6067 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6067
,11-04 14:47:23.740  6067  6067 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 14:47:23.759   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:47:23.791  6064  6064 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-04 14:47:23.807  6064  6064 D AndroidRuntime: CheckJNI is OFF
,11-04 14:47:23.828  6064  6064 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-04 14:47:23.853  6064  6064 I Radio-JNI: register_android_hardware_Radio DONE
,11-04 14:47:23.867  6064  6064 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-04 14:47:23.873   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-04 14:47:23.873   930   943 I ActivityManager: Killing 6067:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-04 14:47:23.886   930  2913 W InputDispatcher: channel 'a948bb2 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-04 14:47:23.886   930  2913 E InputDispatcher: channel 'a948bb2 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-04 14:47:23.889   930  3111 D GraphicsStats: Buffer count: 2
,11-04 14:47:23.889   930  3888 I WindowState: WIN DEATH: Window{a948bb2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-04 14:47:23.889   930  3888 W InputDispatcher: Attempted to unregister already unregistered input channel 'a948bb2 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-04 14:47:23.972   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-04 14:47:23.973   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-04 14:47:23.973   930   943 E ActivityManager: Failure starting process com.test.thalitest
11-04 14:47:23.973   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-04 14:47:23.973   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:47:23.973   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:47:23.973   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 14:47:23.973   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-04 14:47:23.974   930   943 I ActivityManager:   Force finishing activity ActivityRecord{61c6d36 u0 com.test.thalitest/.MainActivity t68}
11-04 14:47:23.974   930   953 I art     : Starting a blocking GC Explicit
,11-04 14:47:23.980   930  3179 W ActivityManager: Spurious death for ProcessRecord{1767680 0:com.test.thalitest/u0a77}, curProc for 6067: null
,11-04 14:47:24.055   930   953 I art     : Explicit concurrent mark sweep GC freed 16777(1130KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 1.704ms total 80.111ms
,11-04 14:47:24.074   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-04 14:47:24.077  6064  6064 I art     : System.exit called, status: 0
,11-04 14:47:24.077  6064  6064 I AndroidRuntime: VM exiting with result code 0.
,11-04 14:47:24.092   930   953 I ActivityManager: Start proc 6117:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-04 14:47:24.092   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-04 14:47:24.097   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-04 14:47:24.102  5843  5843 D BluetoothMapAppObserver: onReceive
11-04 14:47:24.102  5843  5843 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-04 14:47:24.104  4071  4153 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-04 14:47:24.108  3632  3632 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-04 14:47:24.123   930  2914 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-04 14:47:24.133  3632  6129 I Keyboard.Facilitator.DecoderInitializer: run()
,11-04 14:47:24.151  3632  6129 I Decoder : createOrResetDecoder
,11-04 14:47:24.155  3733  3733 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-04 14:47:24.172   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-04 14:47:24.183  3560  3560 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-04 14:47:24.183  3560  3560 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-04 14:47:24.185  3111  3111 W Binder_3: type=1400 audit(0.0:141): avc: denied { ioctl } for path="socket:[28183]" dev="sockfs" ino=28183 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:47:24.190   930  3111 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6067 uid 10077
11-04 14:47:24.191  3632  3632 I Keyboard.Facilitator: onFinishInput()
,11-04 14:47:24.185  3111  3111 W Binder_3: type=1400 audit(0.0:142): avc: denied { ioctl } for path="socket:[28183]" dev="sockfs" ino=28183 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:47:24.195   214   214 W kworker/3:2: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 14:47:24.202  3939  6136 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-04 14:47:24.202  3939  6136 D AccountUtils: Clearing selected account for com.test.thalitest
,11-04 14:47:24.209   214   214 W kworker/3:2: type=1400 audit(0.0:144): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 14:47:24.214  3939  6136 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-04 14:47:24.225   214   214 W kworker/3:2: type=1400 audit(0.0:145): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 14:47:24.234  3939  6136 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,11-04 14:47:24.272  3939  6140 I GMPM-SVC: App measurement is starting up
,11-04 14:47:24.274  3939  6140 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-04 14:47:24.275  3939  6140 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-04 14:47:24.283  3939  6140 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-04 14:47:24.283  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
,11-04 14:47:24.284  3939  6140 E GMPM-SVC: Opening the database failed, dropping and recreating it
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement.db'.
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-04 14:47:24.285  3939  6140 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
,11-04 14:47:24.285  3939  6140 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-04 14:47:24.286  3939  6140 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-04 14:47:24.287  3939  6140 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-04 14:47:24.288  3939  4919 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-04 14:47:24.288  3939  4919 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,11-04 14:47:24.289  3939  4919 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-04 14:47:24.289  3939  4919 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-04 14:47:24.289  3939  4919 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-04 14:47:24.289  3939  4919 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
11-04 14:47:24.290  3384  6134 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-04 14:47:24.299  3384  3408 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjFA022E974) - 
,--------- beginning of crash
11-04 14:47:24.300  3384  3408 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-04 14:47:24.300  3384  3408 E AndroidRuntime: Process: android.process.acore, PID: 3384
11-04 14:47:24.300  3384  3408 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:47:24.300  3384  3408 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-04 14:47:24.302   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
