#### Test 896247961682436_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-08 17:09:12.705  4041  4239 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-08 17:09:12.790  4041  4239 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-08 17:09:13.154  5600  5600 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-08 17:09:13.160  5600  5600 D AndroidRuntime: CheckJNI is OFF
11-08 17:09:13.187  5600  5600 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-08 17:09:13.222  5600  5600 I Radio-JNI: register_android_hardware_Radio DONE
11-08 17:09:13.236  5600  5600 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-08 17:09:13.247   931  3837 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-08 17:09:13.262  5600  5600 D AndroidRuntime: Shutting down VM
11-08 17:09:13.273  3956  4127 W SearchService: Abort, client detached.
11-08 17:09:13.283  3956  3956 I HotwordDetector: Closing mic
11-08 17:09:13.283  3956  4229 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@971104d
11-08 17:09:13.283  3956  4238 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-08 17:09:13.303   931   942 I ActivityManager: Start proc 5609:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-08 17:09:13.348   514  4241 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-08 17:09:13.350   514  4241 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-08 17:09:13.354   514  4241 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-08 17:09:13.355   514  4241 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-08 17:09:13.355   514  3001 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-08 17:09:13.356  3956  4233 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-08 17:09:13.357  3956  4237 I MicroRecognitionRnrImpl: Detection finished
11-08 17:09:13.383  5609  5609 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-08 17:09:13.405  5609  5609 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-08 17:09:13.465  5609  5609 I LibraryLoader: Time to load native libraries: 54 ms (timestamps 5526-5580)
11-08 17:09:13.465  5609  5609 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 17:09:13.496  5609  5609 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c5f387}
11-08 17:09:13.497  5609  5609 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-08 17:09:13.497  5609  5609 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-08 17:09:13.501  5609  5609 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-08 17:09:13.502  5609  5609 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 17:09:13.556  5609  5609 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 17:09:13.564  5609  5609 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 17:09:13.564  5609  5609 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 17:09:13.564  5609  5609 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 17:09:13.564  5609  5609 I Adreno  : Build Date                       : 12/06/15
11-08 17:09:13.564  5609  5609 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 17:09:13.564  5609  5609 I Adreno  : Local Branch                     : mybranch17112971
11-08 17:09:13.564  5609  5609 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 17:09:13.564  5609  5609 I Adreno  : Remote Branch                    : NONE
11-08 17:09:13.564  5609  5609 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 17:09:13.603   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dc7e4c4:true
,11-08 17:09:13.625   406   406 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[13950]" dev="sockfs" ino=13950 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:09:13.625   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[13950]" dev="sockfs" ino=13950 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:09:13.638  5609  5609 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 17:09:13.646  5609  5609 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 17:09:13.665   766   766 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33347]" dev="sockfs" ino=33347 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:09:13.665   766   766 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33347]" dev="sockfs" ino=33347 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-08 17:09:13.670  5609  5646 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-08 17:09:13.672  3785  3785 W Binder_7: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33837]" dev="sockfs" ino=33837 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:09:13.672  3785  3785 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33837]" dev="sockfs" ino=33837 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:09:13.676  5609  5633 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 17:09:13.698  5609  5646 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 17:09:13.772  3426  3426 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33351]" dev="sockfs" ino=33351 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:09:13.772  3426  3426 W Binder_6: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[33351]" dev="sockfs" ino=33351 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:09:13.775  3802  3802 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[33350]" dev="sockfs" ino=33350 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:09:13.781  3654  3654 I Keyboard.Facilitator: onFinishInput()
11-08 17:09:13.775  3802  3802 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[33350]" dev="sockfs" ino=33350 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:09:13.783   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +507ms
,11-08 17:09:13.839  5609  5609 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5609
,11-08 17:09:13.942  5609  5609 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-08 17:09:14.116  5609  5649 D jxcore_app_log: JniHelper::setJavaVM(0xf533c000), pthread_self() = -600049360
,11-08 17:09:14.119  5609  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-08 17:09:14.119  5609  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-08 17:09:14.119  5609  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-08 17:09:14.119  5609  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-08 17:09:14.119  5609  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-08 17:09:14.119  5609  5649 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84686a added. We now have 1 listener(s)
,11-08 17:09:14.122  5609  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-08 17:09:14.122  5609  5649 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:09:14.123  5609  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 17:09:14.123  5609  5649 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-08 17:09:14.125  5609  5649 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d11d2d1 added. We now have 1 listener(s)
11-08 17:09:14.125  5609  5649 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 17:09:14.130   931  2953 D WifiService: New client listening to asynchronous messages
,11-08 17:09:14.130  5609  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 17:09:14.130  5609  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-08 17:09:14.130  5609  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-08 17:09:14.130  5609  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-08 17:09:14.130  5609  5649 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-08 17:09:14.132  5609  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:09:14.132  5609  5649 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-08 17:09:14.135  5609  5649 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-08 17:09:14.136  5609  5649 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:09:14.136  5609  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:14.136  5609  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:14.136  5609  5649 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:14.136  5609  5649 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:14.136  5609  5649 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:09:14.136  5609  5649 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:09:14.136  5609  5649 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:09:14.136  5609  5649 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-08 17:09:14.136  5609  5649 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 17:09:14.136  5609  5649 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-08 17:09:14.240  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:14.245  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:14.248  5609  5609 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-08 17:09:14.518  5609  5657 W jxcore-log: Initializing JXcore engine
11-08 17:09:14.519  5609  5657 W jxcore-log: JXcore engine is ready
,11-08 17:09:14.539  5657  5657 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12448 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-08 17:09:14.539  5657  5657 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13438]" dev="sockfs" ino=13438 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-08 17:09:14.539  5657  5657 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-08 17:09:14.539  5657  5657 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33326]" dev="sockfs" ino=33326 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-08 17:09:14.550  5609  5657 W jxcore-log: Starting JXcore engine
,11-08 17:09:14.602  5609  5657 W jxcore-log: Platform android
11-08 17:09:14.602  5609  5657 W jxcore-log: 
,11-08 17:09:14.602  5609  5657 W jxcore-log: Process ARCH arm
11-08 17:09:14.602  5609  5657 W jxcore-log: 
,11-08 17:09:14.740  5609  5657 I jxcore-log: JXcore Cordova bridge is ready!
11-08 17:09:14.740  5609  5657 I jxcore-log: 
,11-08 17:09:14.741  5609  5657 W jxcore-log: JXcore engine is started
,11-08 17:09:14.744  5609  5649 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-08 17:09:14.747  5609  5609 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-08 17:09:16.856  3592  3592 I ConfigService: onDestroy
,11-08 17:09:18.290   931  3837 I ActivityManager: Killing 5167:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-08 17:09:18.382   931  2952 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-08 17:09:21.666   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:09:22.667   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:09:23.668   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:09:24.442  5609  5657 I jxcore-log: 2016-11-08 16:09:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-08 17:09:24.442  5609  5657 I jxcore-log: 
,11-08 17:09:24.444  5609  5657 I jxcore-log: 2016-11-08 16:09:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-08 17:09:24.444  5609  5657 I jxcore-log: 
,11-08 17:09:24.447  5609  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:09:24.447  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:24.447  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:24.447  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:24.447  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:24.447  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:09:24.447  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:09:24.447  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:09:24.449  5609  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:09:24.450  5609  5657 I jxcore-log: 2016-11-08 16:09:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-08 17:09:24.450  5609  5657 I jxcore-log: 
,11-08 17:09:24.452  5609  5657 I jxcore-log: 2016-11-08 16:09:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-08 17:09:24.452  5609  5657 I jxcore-log: 
,11-08 17:09:24.670   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:09:24.702  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 17:09:24.702  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a7f6f6 added. We now have 2 listener(s)
11-08 17:09:24.703  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:09:24.703  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 17:09:24.703  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 17:09:24.703  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-08 17:09:24.703  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a074af7 added. We now have 2 listener(s)
,11-08 17:09:24.703  5609  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 17:09:24.704  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-08 17:09:24.706  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:09:24.709  5609  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:09:24.709  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:24.709  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:24.709  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:24.709  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:24.709  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:09:24.709  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:09:24.709  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-08 17:09:24.710  5609  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:09:24.710  5609  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 17:09:24.711  5609  5657 D ExecuteNativeTests: Running unit tests
,11-08 17:09:24.713  5609  5657 D BluetoothAdapter: enable(): BT is already enabled..!
,11-08 17:09:24.713   931  3802 D WifiService: setWifiEnabled: true pid=5609, uid=10077
11-08 17:09:24.713   931  3802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:09:24.715  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:24.722  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:25.671   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:09:26.392  3956  5659 W CronetSyncConnectionRcs: Upload content type not set.
,11-08 17:09:26.538  4895  4928 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-08 17:09:26.540  4895  4895 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-08 17:09:26.542   931  3802 I ActivityManager: Killing 5256:org.codeaurora.ims/1001 (adj 15): empty #17
,11-08 17:09:26.672   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-08 17:09:34.719  5609  5657 I com.test.thalitest.ThaliTestRunner: Running UT
,11-08 17:09:34.786  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-08 17:09:34.786  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7a8271 added. We now have 3 listener(s)
11-08 17:09:34.787  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:09:34.787  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 17:09:34.787  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-08 17:09:34.788  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 17:09:34.788  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4e2856 added. We now have 3 listener(s)
11-08 17:09:34.788  5609  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 17:09:34.789  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 17:09:34.792  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:09:34.801  5609  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:09:34.801  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:34.801  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:34.801  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:34.801  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:34.801  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:09:34.801  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:09:34.801  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:09:34.803  5609  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:09:34.803  5609  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
11-08 17:09:34.807  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:34.808  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:34.810  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-08 17:09:34.810  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-08 17:09:34.810  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:09:34.810  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:09:34.810  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:09:34.811  5609  5657 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-08 17:09:34.811  5609  5657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-08 17:09:34.811  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 17:09:34.811  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:09:34.812  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:09:34.812  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:09:34.812  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-08 17:09:34.812  5609  5657 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-08 17:09:34.813  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-08 17:09:34.815  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-08 17:09:34.815  5609  5657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 17:09:34.815  5609  5657 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 17:09:34.816  5609  5657 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-08 17:09:34.816  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-08 17:09:34.816  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:09:34.816  5609  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:09:34.816  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:09:34.816  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:09:34.817  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 17:09:34.817  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 17:09:34.817  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 17:09:34.817  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-08 17:09:34.818  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:09:34.818  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 17:09:34.818  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:09:34.818  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 17:09:34.818  5609  5609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:09:34.818  5609  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 17:09:34.820  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:09:34.821  5609  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:09:34.821  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 17:09:34.822  5609  5663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:09:34.828  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 17:09:34.829  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:09:34.829  5609  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 17:09:34.829  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:09:34.819  4688  4688 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33386]" dev="sockfs" ino=33386 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:09:34.822  4688  4688 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33386]" dev="sockfs" ino=33386 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 17:09:34.830  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.830  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:09:34.831  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:09:34.831  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-08 17:09:34.831  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:09:34.831  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.831  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:34.831  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.831  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.832  5609  5657 D BluetoothAdapter: STATE_ON
,11-08 17:09:34.835  4675  4688 D BtGatt.GattService: registerClient() - UUID=b3dbb4bc-63f8-472f-b4a1-25209862d75b
,11-08 17:09:34.835  4675  4735 D BtGatt.GattService: onClientRegistered() - UUID=b3dbb4bc-63f8-472f-b4a1-25209862d75b, clientIf=5
,11-08 17:09:34.837  5609  5619 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 17:09:34.840  4675  4737 D BtGatt.AdvertiseManager: message : 0
,11-08 17:09:34.843  4675  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:09:34.860  4675  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:09:34.869  4675  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:09:34.870  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:34.870  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.870  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 17:09:34.870  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.870  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.870  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.871  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.871  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:34.871  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 17:09:34.871  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:09:34.871  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.872  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:34.872  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.872  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:34.872  5609  5657 I io.jxcore.node.ConnectionHelper: start: OK
11-08 17:09:34.873  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-08 17:09:34.873  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-08 17:09:34.873  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:34.873  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:09:34.874  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:09:34.874  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:34.874  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:09:34.874  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:09:34.874  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:09:34.874  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-08 17:09:34.875  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-08 17:09:34.875  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 17:09:34.875  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:34.878  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-08 17:09:34.879  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:09:34.879  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:34.879  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:34.879  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:34.879  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-08 17:09:34.879  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 17:09:35.376  5609  5657 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-08 17:09:35.376  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-08 17:09:35.376  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-08 17:09:35.376  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-08 17:09:35.376  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-08 17:09:35.376  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-08 17:09:35.376  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-08 17:09:35.376  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-08 17:09:35.376  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-08 17:09:35.377  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-08 17:09:35.377  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-08 17:09:35.377  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-08 17:09:35.377  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-08 17:09:35.377  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-08 17:09:35.377  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-08 17:09:35.377  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-08 17:09:35.378  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-08 17:09:35.379  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-08 17:09:35.379  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-08 17:09:35.379  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-08 17:09:35.379  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-08 17:09:35.379  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-08 17:09:35.379  5609  5657 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-08 17:09:35.379  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-08 17:09:35.379  5609  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 17:09:35.380  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 17:09:35.380  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 17:09:35.380  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 17:09:35.380  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 17:09:35.380  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 17:09:35.380  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 17:09:35.380  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 17:09:35.381  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 17:09:35.381  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 17:09:35.381  5609  5609 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-08 17:09:35.381  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 17:09:35.382  5609  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:09:35.382  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.382  5609  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 17:09:35.382  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.382  5609  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 17:09:35.384  5609  5657 D BluetoothAdapter: STATE_ON
11-08 17:09:35.384  5609  5657 D BluetoothLeScanner: could not find callback wrapper
,11-08 17:09:35.384  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 17:09:35.384  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.384  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.384  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 17:09:35.384  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:35.387  4675  4737 D BtGatt.AdvertiseManager: message : 1
11-08 17:09:35.388  4675  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
11-08 17:09:35.400  4675  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 17:09:35.401  4675  4735 D BtGatt.GattService: Client app is not null!
11-08 17:09:35.402  4675  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:09:35.403  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:09:35.403  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.403  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:09:35.403  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.403  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:35.404  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.404  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-08 17:09:35.404  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:09:35.404  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.404  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.404  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-08 17:09:35.404  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.406  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.406  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:09:35.406  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.406  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.407  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.407  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.407  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.407  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 17:09:35.407  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 17:09:35.408  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 17:09:35.408  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.410  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.410  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.410  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.411  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 17:09:35.411  5609  5609 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 17:09:35.413  5609  5657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 17:09:35.413  5609  5657 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 17:09:35.413  5609  5657 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,11-08 17:09:35.414  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-08 17:09:35.415  5609  5609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 17:09:35.414  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:09:35.415  5609  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:09:35.415  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:09:35.415  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:09:35.419  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 17:09:35.422  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 17:09:35.422  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 17:09:35.422  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 17:09:35.422  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:09:35.423  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 17:09:35.423  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:09:35.423  5609  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 17:09:35.423  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 17:09:35.423  5609  5666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:09:35.425  4887  4887 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33390]" dev="sockfs" ino=33390 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 17:09:35.425  4887  4887 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33390]" dev="sockfs" ino=33390 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:09:35.427  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:09:35.428  5609  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:09:35.428  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 17:09:35.429  5609  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-08 17:09:35.433  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 17:09:35.433  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:09:35.434  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 17:09:35.437  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.437  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-08 17:09:35.437  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:09:35.437  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-08 17:09:35.437  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:09:35.437  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.437  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.437  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.438  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:35.438  5609  5657 D BluetoothAdapter: STATE_ON
,11-08 17:09:35.441  4675  4686 D BtGatt.GattService: registerClient() - UUID=1b3094d6-4776-4990-8829-a31e548cbb2c
11-08 17:09:35.442  4675  4735 D BtGatt.GattService: onClientRegistered() - UUID=1b3094d6-4776-4990-8829-a31e548cbb2c, clientIf=5
11-08 17:09:35.442  5609  5620 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 17:09:35.443  4675  4737 D BtGatt.AdvertiseManager: message : 0
,11-08 17:09:35.445  4675  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:09:35.456  4675  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:09:35.462  4675  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:09:35.463  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.463  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.463  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-08 17:09:35.463  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.463  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.463  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.463  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.463  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.464  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 17:09:35.465  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:09:35.465  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.466  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.466  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.466  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:35.466  5609  5657 I io.jxcore.node.ConnectionHelper: start: OK
11-08 17:09:35.467  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:09:35.467  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.467  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[main,5,main], id: 1
,11-08 17:09:35.468  5609  5609 D BluetoothAdapter: STATE_ON
11-08 17:09:35.468  5609  5609 D BluetoothLeScanner: could not find callback wrapper
11-08 17:09:35.468  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 17:09:35.468  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[main,5,main], id: 1
,11-08 17:09:35.468  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.468  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 17:09:35.468  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.469  4675  4737 D BtGatt.AdvertiseManager: message : 1
11-08 17:09:35.469  4675  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:09:35.475  4675  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 17:09:35.476  4675  4735 D BtGatt.GattService: Client app is not null!
,11-08 17:09:35.476  4675  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 17:09:35.477  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:09:35.477  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
,11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.478  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.478  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 17:09:35.478  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-08 17:09:35.479  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 17:09:35.479  5609  5609 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:09:35.479  5609  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 17:09:35.482  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:09:35.483  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:09:35.483  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:09:35.485  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.485  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:09:35.485  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:09:35.485  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-08 17:09:35.485  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:09:35.485  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.485  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.486  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.486  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.486  5609  5609 D BluetoothAdapter: STATE_ON
,11-08 17:09:35.489  4675  4887 D BtGatt.GattService: registerClient() - UUID=98a82f08-bdd7-4084-8d86-9b9a3ea6c276
11-08 17:09:35.489  4675  4735 D BtGatt.GattService: onClientRegistered() - UUID=98a82f08-bdd7-4084-8d86-9b9a3ea6c276, clientIf=5
11-08 17:09:35.490  5609  5620 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 17:09:35.491  4675  4737 D BtGatt.AdvertiseManager: message : 0
,11-08 17:09:35.492  4675  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:09:35.503  4675  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:09:35.509  4675  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:09:35.510  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.510  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.510  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 17:09:35.510  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
,11-08 17:09:35.510  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.510  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.510  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.510  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.510  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 17:09:35.512  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:09:35.512  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.513  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.513  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.513  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.514  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-08 17:09:35.514  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:09:35.515  5609  5609 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-08 17:09:35.517  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.517  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:09:35.517  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-08 17:09:35.518  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-08 17:09:35.518  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.518  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.519  4675  4737 D BtGatt.AdvertiseManager: message : 1
11-08 17:09:35.519  4675  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:09:35.525  4675  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 17:09:35.525  4675  4735 D BtGatt.GattService: Client app is not null!
11-08 17:09:35.526  4675  4688 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:09:35.526  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:09:35.526  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.526  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-08 17:09:35.526  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.526  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.526  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.527  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.527  5609  5609 D BluetoothAdapter: STATE_ON
,11-08 17:09:35.530  4675  4887 D BtGatt.GattService: registerClient() - UUID=e41d181e-f414-4245-bb2b-610170d422d8
11-08 17:09:35.531  4675  4735 D BtGatt.GattService: onClientRegistered() - UUID=e41d181e-f414-4245-bb2b-610170d422d8, clientIf=5
11-08 17:09:35.531  5609  5619 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 17:09:35.532  4675  4737 D BtGatt.AdvertiseManager: message : 0
,11-08 17:09:35.535  4675  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:09:35.545  4675  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:09:35.551  4675  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:09:35.551  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.551  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.551  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 17:09:35.552  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.552  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-08 17:09:35.552  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.552  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.552  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
,11-08 17:09:35.552  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.552  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Already running
11-08 17:09:35.552  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.552  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.552  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.552  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 17:09:35.553  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:09:35.553  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.555  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-08 17:09:35.555  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.555  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.555  5609  5609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 17:09:35.555  5609  5609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  false
11-08 17:09:35.556  5609  5609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-08 17:09:35.556  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:09:35.556  5609  5609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:09:35.556  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:09:35.556  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.556  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-08 17:09:35.556  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to RUNNING
11-08 17:09:35.556  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.556  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.557  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.557  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-08 17:09:35.557  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:09:35.557  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.557  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.557  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 17:09:35.557  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 17:09:35.558  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.558  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.558  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.558  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.558  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:35.559  5609  5609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 17:09:35.559  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-08 17:09:36.057  5609  5609 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-08 17:09:36.058  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-08 17:09:40.472  5609  5667 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,11-08 17:09:40.480  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-08 17:09:40.480  5609  5657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 17:09:40.480  5609  5657 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 17:09:40.480  5609  5657 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,11-08 17:09:40.480  5609  5657 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-08 17:09:40.483  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,11-08 17:09:40.484  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 17:09:40.484  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 17:09:40.484  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 17:09:40.484  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-08 17:09:40.484  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 17:09:40.484  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 17:09:40.484  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 17:09:40.484  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 17:09:40.484  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-08 17:09:40.484  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.487  4675  4737 D BtGatt.AdvertiseManager: message : 1
11-08 17:09:40.488  4675  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:09:40.499  4675  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 17:09:40.500  4675  4735 D BtGatt.GattService: Client app is not null!
,11-08 17:09:40.501  4675  4686 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:09:40.501  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:09:40.502  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.502  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:09:40.502  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.502  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.502  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:09:40.502  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.502  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:09:40.502  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:09:40.503  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-08 17:09:40.503  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:09:40.503  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.503  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.503  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.503  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.504  5609  5657 D BluetoothAdapter: STATE_ON
,11-08 17:09:40.508  4675  4887 D BtGatt.GattService: registerClient() - UUID=4cbb5e79-4e1b-4605-89cd-9abf3cac4635
11-08 17:09:40.509  4675  4735 D BtGatt.GattService: onClientRegistered() - UUID=4cbb5e79-4e1b-4605-89cd-9abf3cac4635, clientIf=5
,11-08 17:09:40.509  5609  5620 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 17:09:40.510  4675  4737 D BtGatt.AdvertiseManager: message : 0
,11-08 17:09:40.513  4675  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:09:40.523  4675  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:09:40.529  4675  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-08 17:09:40.529  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:09:40.529  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.529  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.530  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-08 17:09:40.530  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.530  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.530  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.530  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.530  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:40.530  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:40.530  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:09:40.530  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:09:40.530  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:09:40.530  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-08 17:09:40.530  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:09:40.530  5609  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:09:40.530  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:40.530  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:09:40.530  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:09:40.530  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:09:40.530  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:09:40.530  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:09:40.530  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:40.531  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-08 17:09:40.532  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
11-08 17:09:40.533  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:09:40.533  5609  5657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
11-08 17:09:40.533  5609  5657 I io.jxcore.node.ConnectionHelper: start: OK
,11-08 17:09:45.541  5609  5668 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,11-08 17:09:45.545  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,11-08 17:09:45.546  5609  5657 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-08 17:09:45.552  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-08 17:09:45.554  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-08 17:09:45.555  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-08 17:09:45.556  5609  5657 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-08 17:09:45.557  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,11-08 17:09:45.558  5609  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-08 17:09:45.559  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-08 17:09:45.559  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 17:09:45.560  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:09:45.560  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:09:45.560  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:09:45.560  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 17:09:45.561  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:09:45.562  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:09:45.562  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:09:45.562  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-08 17:09:45.562  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:09:45.562  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:09:45.562  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-08 17:09:45.564  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-08 17:09:45.565  5609  5657 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-08 17:09:45.565  5609  5657 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-08 17:09:45.568  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-08 17:09:45.568  5609  5657 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-08 17:09:45.573  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-08 17:09:45.573  5609  5657 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,11-08 17:09:45.574  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,11-08 17:09:45.575  5609  5657 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-08 17:09:45.575  5609  5657 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-08 17:09:45.576  5609  5657 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,11-08 17:09:45.576  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-08 17:09:45.576  5609  5657 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-08 17:09:45.576  5609  5657 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-08 17:09:45.576  5609  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-08 17:09:45.576  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 17:09:45.577  5609  5657 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-08 17:09:45.577  5609  5657 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-08 17:09:45.577  5609  5657 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-08 17:09:45.577  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 17:09:45.577  5609  5657 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-08 17:09:45.579  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-08 17:09:45.580  5609  5657 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-08 17:09:45.580  5609  5657 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-08 17:09:45.580  5609  5657 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-08 17:09:45.580  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
,11-08 17:09:45.581  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 17:09:45.581  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 17:09:45.581  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 17:09:45.581  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
11-08 17:09:45.581  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 17:09:45.581  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 17:09:45.581  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 17:09:45.581  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 17:09:45.581  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-08 17:09:45.581  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.584  4675  4737 D BtGatt.AdvertiseManager: message : 1
,11-08 17:09:45.585  4675  4737 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:09:45.596  4675  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-08 17:09:45.596  4675  4735 D BtGatt.GattService: Client app is not null!
11-08 17:09:45.597  4675  4686 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:09:45.598  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 17:09:45.598  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.598  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:09:45.599  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:45.599  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.599  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:09:45.599  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.599  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:09:45.599  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:09:45.599  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-08 17:09:45.600  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:09:45.600  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.600  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.600  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:45.600  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.601  5609  5657 D BluetoothAdapter: STATE_ON
,11-08 17:09:45.606  4675  4887 D BtGatt.GattService: registerClient() - UUID=831c642d-fe13-465a-9d59-9727d34a8803
,11-08 17:09:45.606  4675  4735 D BtGatt.GattService: onClientRegistered() - UUID=831c642d-fe13-465a-9d59-9727d34a8803, clientIf=5
,11-08 17:09:45.606  5609  5620 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 17:09:45.608  4675  4737 D BtGatt.AdvertiseManager: message : 0
,11-08 17:09:45.611  4675  4737 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:09:45.627  4675  4735 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:09:45.636  4675  4735 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:09:45.637  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.637  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-08 17:09:45.637  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.637  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-08 17:09:45.637  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:45.638  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.638  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.638  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.638  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:45.638  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-08 17:09:45.638  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:45.638  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:09:45.638  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:09:45.639  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:09:45.639  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-08 17:09:45.639  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:45.639  5609  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:09:45.639  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-08 17:09:45.639  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:09:45.639  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-08 17:09:45.639  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-08 17:09:45.639  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-08 17:09:45.639  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-08 17:09:45.639  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-08 17:09:45.640  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
,11-08 17:09:45.640  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-08 17:09:45.640  5609  5657 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the connection manager (Bluetooth connection listener)
11-08 17:09:45.640  5609  5657 I io.jxcore.node.ConnectionHelper: start: OK
,11-08 17:09:50.646  5609  5669 E io.jxcore.node.ConnectionHelperTest: Discovery manager didn't start after 5s!
,11-08 17:09:50.651  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-08 17:09:50.653  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:09:50.655  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Already started
11-08 17:09:50.655  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:09:50.655  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-08 17:09:50.659  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-08 17:09:50.661  5609  5657 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-08 17:09:50.661  5609  5657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-08 17:09:50.662  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-08 17:09:50.662  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:09:50.662  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-08 17:09:50.662  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-08 17:09:50.665  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-08 17:09:50.672  5609  5657 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-08 17:09:50.672  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 17:09:50.672  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 17:09:50.672  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 17:09:50.673  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 17:09:50.673  5609  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:09:50.673  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 17:09:50.673  5609  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-08 17:09:50.673  5609  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 17:09:50.673  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 17:09:50.673  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7a8271 removed from the list
11-08 17:09:50.673  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 17:09:50.673  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4e2856 removed from the list
,11-08 17:09:50.673  5609  5657 D io.jxcore.node.ConnectivityMonitor: stop
11-08 17:09:50.674  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 17:09:50.674  5609  5609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 17:09:50.674  5609  5609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 17:09:50.677  5609  5657 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-08 17:09:50.677  5609  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-08 17:09:50.678  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 17:09:50.678  5609  5657 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-08 17:09:50.678  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-08 17:09:50.678  5609  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-08 17:09:50.678  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-08 17:09:50.679  5609  5657 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,11-08 17:09:50.680  5609  5657 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-08 17:09:50.682  5609  5657 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-08 17:09:50.683  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-08 17:09:50.683  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-08 17:09:50.684  5609  5657 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-08 17:09:50.684  5609  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-08 17:09:50.684  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-08 17:09:50.685  5609  5657 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-08 17:09:50.685  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-08 17:09:50.685  5609  5657 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-08 17:09:50.685  5609  5657 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-08 17:09:50.686  5609  5657 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
,11-08 17:09:50.686  5609  5657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-08 17:09:50.686  5609  5657 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-08 17:09:50.687  5609  5657 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-08 17:09:50.688  5609  5657 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,11-08 17:09:50.688  5609  5657 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-08 17:09:50.688  5609  5657 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-08 17:09:50.688  5609  5657 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-08 17:09:50.689  5609  5657 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-08 17:09:50.690  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-08 17:09:50.690  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d97748 added. We now have 3 listener(s)
11-08 17:09:50.692  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:09:50.692  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 17:09:50.692  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 17:09:50.693  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 17:09:50.693  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f9fe9e1 added. We now have 3 listener(s)
11-08 17:09:50.693  5609  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-08 17:09:50.693  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 17:09:50.697  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:09:50.701  5609  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:09:50.701  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:50.701  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:50.701  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:50.701  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:50.701  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:09:50.701  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:09:50.701  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:09:50.703  5609  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:09:50.704  5609  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 17:09:50.706  5609  5657 D BluetoothAdapter: enable(): BT is already enabled..!
,11-08 17:09:50.706   931  3837 D WifiService: setWifiEnabled: true pid=5609, uid=10077
11-08 17:09:50.706   931  3837 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 17:09:50.707  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:50.708  5609  5657 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-08 17:09:50.711  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:50.712  5609  5657 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-08 17:09:50.713  5609  5657 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-08 17:09:50.716   931  3131 D WifiService: setWifiEnabled: false pid=5609, uid=10077
,11-08 17:09:50.716   931  3131 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:09:50.721   931  2952 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-08 17:09:50.721   931  2952 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-08 17:09:50.722   931  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 17:09:50.722   931  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:09:50.729   931  5381 D DhcpClient: Clearing IP address
,11-08 17:09:50.730   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-08 17:09:50.737   509   925 D CommandListener: Setting iface cfg
,11-08 17:09:50.739   931  5382 D DhcpClient: Receive thread stopped
,11-08 17:09:50.748  3592  5438 V NativeCrypto: Read error: ssl=0x7f81159000: I/O error during system call, Connection timed out
,11-08 17:09:50.749   931  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-08 17:09:50.750   931  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-08 17:09:50.750  3592  5438 V NativeCrypto: SSL shutdown failed: ssl=0x7f81159000: I/O error during system call, Broken pipe
11-08 17:09:50.755   535   535 E Parcel  : Reading a NULL string not supported here.
11-08 17:09:50.755   931   931 D RttService: SCAN_AVAILABLE : 1
,11-08 17:09:50.755   931  3061 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 17:09:50.760   931  3785 I ActivityManager: Killing 5272:com.android.settings/1000 (adj 15): empty #17
,11-08 17:09:50.765   931  2952 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-08 17:09:50.798   509   925 D TetherController: Setting IP forward enable = 0
,11-08 17:09:50.805   931  2954 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-08 17:09:50.807   931  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 17:09:50.807  3724  3864 W QCNEJ   : |CORE| network lost: 100
,11-08 17:09:50.808  3724  3864 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-08 17:09:50.826   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:09:50.844   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:09:50.844   509   925 D CommandListener: Clearing all IP addresses on wlan0
11-08 17:09:50.845   509   925 D TetherController: Setting IP forward enable = 0
,11-08 17:09:50.846   931  2954 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-08 17:09:50.846   931  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-08 17:09:50.851   931   948 D Tethering: MasterInitialState.processMessage what=3
11-08 17:09:50.852  5287  5287 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@97148e3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-08 17:09:50.853  3956  3956 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-08 17:09:50.854  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:50.854  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:50.854  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:50.854  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:50.854  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:50.854  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:50.854  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:50.854  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:50.856   931  2952 D DhcpClient: doQuit
,11-08 17:09:50.856   931  2952 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-08 17:09:50.856  3446  3446 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-08 17:09:50.857   931  5381 D DhcpClient: onQuitting
,11-08 17:09:50.860  4041  4041 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-08 17:09:50.864  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:50.869  4041  4041 D SystemUpdateService: onCreate
,11-08 17:09:50.871  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:50.871  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:50.871  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:50.871  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:09:50.871  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:50.871  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:50.871  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:50.871  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:50.874  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:50.876  3446  3446 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-08 17:09:50.878  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:50.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:50.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:50.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:09:50.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:50.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:50.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:50.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:50.880  3446  3446 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-08 17:09:50.881  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:50.885  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:50.885  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:50.885  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:50.885  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:09:50.885  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:50.885  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:50.885  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:50.885  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:50.887  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:50.888  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:50.889  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:50.890  4041  4041 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 17:09:50.899  4041  4041 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-08 17:09:50.904  4041  4254 I iu.UploadsManager: num queued entries: 0
,11-08 17:09:50.904  4041  4254 I iu.UploadsManager: num updated entries: 0
11-08 17:09:50.905  4041  4254 I iu.SyncManager: NEXT; no task
,11-08 17:09:50.906  4041  5692 I SystemUpdateService: active receiver: enabled
,11-08 17:09:50.908   509   925 E Netd    : netlink response contains error (No such file or directory)
,11-08 17:09:50.908  4041  4041 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-08 17:09:50.909   931  2954 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-08 17:09:50.910  4041  4041 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 17:09:50.912  5410  5410 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:09:50.913  3446  3446 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-08 17:09:50.916  5410  5410 D SprintDMHelper: simOperator: 
11-08 17:09:50.916  5410  5410 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 17:09:50.925  3446  3446 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-08 17:09:50.926  4041  5692 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 17:09:50.932  4041  5692 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-08 17:09:50.932  4041  5692 I SystemUpdateService: now status is 0 (complete)
11-08 17:09:50.932  4041  5692 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 17:09:50.932  4041  5692 I SystemUpdateService: file has been verified
,11-08 17:09:50.933  4041  5692 I SystemUpdateService: OTA package size = 21989297
,11-08 17:09:50.942  4041  5692 I SystemUpdateService: showing system update notification
,11-08 17:09:50.942   931  3837 I ActivityManager: Start proc 5696:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-08 17:09:50.951   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 17:09:50.954  4041  4041 D SystemUpdateService: onDestroy
,11-08 17:09:50.976  5696  5696 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-08 17:09:50.984   931  3425 I ActivityManager: Killing 5067:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-08 17:09:51.030   931  2952 D wifi    : In wifi stop Hal
11-08 17:09:51.031   931  2952 D wifi    : halHandle = 0x7f7f584080, mVM = 0x7f9bc0d140, mCls = 0x1009fa
,11-08 17:09:51.031   931  3445 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-08 17:09:51.031   931  3445 D WifiHAL : Got a signal to exit!!!
11-08 17:09:51.031   931  3445 I WifiHAL : Exit wifi_event_loop
11-08 17:09:51.032  3936  4222 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 17:09:51.032   931  2952 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-08 17:09:51.032   931  2952 E WifiHAL : Event processing terminated
11-08 17:09:51.032   931  2952 D wifi    : In wifi cleaned up handler
11-08 17:09:51.032   931  2952 I WifiHAL : Internal cleanup completed
11-08 17:09:51.033  4521  4521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 17:09:51.034  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:51.036  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:51.038  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:51.056   931  3445 D wifi    : set interface wlan0 flags (DOWN)
,11-08 17:09:51.057   931  2952 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 17:09:51.225  5609  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:51.229   931  3425 D WifiService: setWifiEnabled: true pid=5609, uid=10077
,11-08 17:09:51.230   931  3425 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:09:51.260   931   948 D Tethering: InitialState.processMessage what=4
,11-08 17:09:51.262   509   925 D SoftapController: Softap fwReload - Ok
,11-08 17:09:51.266   509   925 D CommandListener: Setting iface cfg
,11-08 17:09:51.266   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-08 17:09:51.266   509   925 D CommandListener: Trying to bring down wlan0
,11-08 17:09:51.268   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-08 17:09:51.273   931  2952 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 17:09:51.673   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-08 17:09:51.675   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-08 17:09:51.737   931  3802 D WifiService: setWifiEnabled: true pid=5609, uid=10077
,11-08 17:09:51.737   931  3802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:09:51.883   931  2952 D wifi    : set interface wlan0 flags (UP)
,11-08 17:09:51.884   931  2952 I WifiHAL : Initializing wifi
11-08 17:09:51.884   931  2952 I WifiHAL : Creating socket
11-08 17:09:51.889   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-08 17:09:51.889   931  2952 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-08 17:09:51.889   931  2952 D wifi    : Did set static halHandle = 0x7f7f584080
11-08 17:09:51.889   931  2952 D wifi    : halHandle = 0x7f7f584080, mVM = 0x7f9bc0d140, mCls = 0x17c2
11-08 17:09:51.891   931  2952 D wifi    : array field set
11-08 17:09:51.891   931  2952 I WifiNative-HAL: interface[0] = wlan0
11-08 17:09:51.895   931  5711 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547597336704
11-08 17:09:51.895   931  5711 D wifi    : waitForHalEvents called, vm = 0x7f9bc0d140, obj = 0x17c2, env = 0x7f7fa982c0
,11-08 17:09:51.901   931  2952 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-08 17:09:51.908  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:51.910  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:51.913  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:51.971  5712  5712 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 17:09:52.049  5712  5712 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 17:09:52.073  5712  5712 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 17:09:52.073  5712  5712 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 17:09:52.087   931  2952 D WifiConfigStore: Loading config and enabling all networks 
,11-08 17:09:52.097  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:52.097  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:52.097  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:52.097  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:52.097  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:52.097  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:52.097  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:52.097  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:52.102  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:52.106   931  2952 D WifiConfigStore: loaded 0 passpoint configs
11-08 17:09:52.106  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:52.106  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:52.106  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:52.106  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:52.106  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:52.106  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:52.106  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:52.106  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:52.107   931  2952 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-08 17:09:52.107   931  2952 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-08 17:09:52.108   931  2952 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-08 17:09:52.108   931  2952 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-08 17:09:52.108   931  2952 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-08 17:09:52.109   931  2952 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-08 17:09:52.109  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:52.109   931  2952 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
,11-08 17:09:52.109   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-08 17:09:52.109   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-08 17:09:52.109   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 17:09:52.109   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-08 17:09:52.109   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-08 17:09:52.111   931  2952 D WifiNative-HAL: Setting external_sim to 1
,11-08 17:09:52.111  4521  4521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 17:09:52.112   931  2952 D wifi    : setting dfs flag to true, 0x7f80733be0
11-08 17:09:52.112   931  2952 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 17:09:52.112   931  2952 D wifi    : setting scan oui 0x7f80733be0
11-08 17:09:52.112   931  2952 D WifiHAL : Sending mac address OUI
,11-08 17:09:52.113  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:52.113  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:52.113  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:52.113  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:52.113  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:52.113  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:52.113  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:52.113  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:52.114   931  2952 E native  : do suspend false
,11-08 17:09:52.115  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:52.120   931  2952 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-08 17:09:52.121   931   931 D RttService: SCAN_AVAILABLE : 3
11-08 17:09:52.121   931  3061 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 17:09:52.125   509   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-08 17:09:52.127   509   925 D CommandListener: Setting iface cfg
,11-08 17:09:52.132   931  2951 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '120 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 120 Failed to set address (No such device)'
,11-08 17:09:52.132   931  2951 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-08 17:09:52.140   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=114256 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
11-08 17:09:52.141   931  2951 D WifiNative-HAL: p2pGetDeviceAddress
,11-08 17:09:52.141   931  2951 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-08 17:09:52.241  5609  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:52.250  4675  4731 D BluetoothAdapterState: Current state: ON, message: 23
,11-08 17:09:52.250  4675  4731 D BluetoothAdapterProperties: Setting state to 13
,11-08 17:09:52.250  4675  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-08 17:09:52.252  4675  4731 D BluetoothAdapterProperties: onBluetoothDisable()
11-08 17:09:52.256  4675  4731 I BluetoothAdapterState: Entering PendingCommandState
,11-08 17:09:52.257  4675  4675 D BluetoothMapService: onReceive
,11-08 17:09:52.257  4675  4675 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 17:09:52.257  4675  4675 D BluetoothMapService: STATE_TURNING_OFF
11-08 17:09:52.258  4675  4675 D BluetoothMapService: MAP Service closeService in
11-08 17:09:52.258  4675  4675 D BluetoothMapMasInstance0: MAP Service shutdown
11-08 17:09:52.258  4675  4675 D ObexServerSockets0: shutdown(block = true)
11-08 17:09:52.259  4675  4675 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 17:09:52.259  4675  4908 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-08 17:09:52.259  4675  4885 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-08 17:09:52.259  4675  4675 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 17:09:52.259  4675  4909 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-08 17:09:52.261  4675  4675 I BtOppRfcommListener: stopping Accept Thread
11-08 17:09:52.261  4675  5314 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-08 17:09:52.262  4675  5314 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-08 17:09:52.263  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:52.263  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:52.263  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:52.263  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:52.263  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:52.263  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:09:52.263  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:52.263  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:52.263  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:52.264  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:52.264  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:52.268  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:52.268  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:52.268  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:52.268  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:52.268  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:52.268  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:09:52.268  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:52.268  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:52.268  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:52.269  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-08 17:09:52.269  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:52.269  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 13
11-08 17:09:52.272  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:52.272  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:52.272  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:52.272  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:52.272  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:52.272  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:09:52.272  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:52.272  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:52.272  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:52.273  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:52.273  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:52.275   931   944 I ActivityManager: Start proc 5716:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-08 17:09:52.276  4675  4735 D BluetoothAdapterProperties: Scan Mode:20
11-08 17:09:52.276  4675  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-08 17:09:52.279  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:52.280  4675  4675 D HeadsetService: Received stop request...Stopping profile...
11-08 17:09:52.281   931   931 D BluetoothHeadset: Proxy object disconnected
11-08 17:09:52.281   931   931 D BluetoothHeadset: Proxy object disconnected
11-08 17:09:52.282  4675  4675 V BluetoothAdapterState: isTurningOff()=true
,11-08 17:09:52.282  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:52.282  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:52.282  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:52.282  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:52.282  3132  3146 D BluetoothHeadset: Proxy object disconnected
11-08 17:09:52.282  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-08 17:09:52.282  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.282   931   931 D BluetoothHeadset: Proxy object disconnected
11-08 17:09:52.282  4675  4675 D A2dpService: Received stop request...Stopping profile...
11-08 17:09:52.283  3762  3990 D BluetoothHeadset: Proxy object disconnected
11-08 17:09:52.283  3132  3132 D HeadsetProfile: Bluetooth service disconnected
11-08 17:09:52.284  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.284  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:09:52.284  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.285  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.286  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:52.286  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:09:52.286  4675  4890 D A2dpStateMachine: Exit Disconnected: -1
11-08 17:09:52.288   931   931 D BluetoothA2dp: Proxy object disconnected
11-08 17:09:52.288  3132  3132 D BluetoothA2dp: Proxy object disconnected
11-08 17:09:52.290  4675  4675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-08 17:09:52.290  4675  4675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-08 17:09:52.290  4675  4880 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:52.290  4675  4880 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:52.290  4675  4880 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:52.290  4675  4735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-08 17:09:52.291  4675  4735 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-08 17:09:52.291  4675  4675 D HidService: Received stop request...Stopping profile...
11-08 17:09:52.291  4675  4675 D HidService: Stopping Bluetooth HidService
11-08 17:09:52.292  3132  3132 D BluetoothInputDevice: Proxy object disconnected
11-08 17:09:52.292  3132  3132 D HidProfile: Bluetooth service disconnected
11-08 17:09:52.292  4675  4675 D HealthService: Received stop request...Stopping profile...
11-08 17:09:52.293  4675  4675 D PanService: Received stop request...Stopping profile...
11-08 17:09:52.295  3132  3132 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 17:09:52.295  3132  3132 D PanProfile: Bluetooth service disconnected
11-08 17:09:52.295  4675  4675 D BluetoothMapService: Received stop request...Stopping profile...
11-08 17:09:52.295  4675  4675 D BluetoothMapService: stop()
11-08 17:09:52.296  4675  4675 D BluetoothMapAppObserver: deinitObservers()
11-08 17:09:52.296  4675  4675 D BluetoothMapAppObserver: removeReceiver()
11-08 17:09:52.298  3132  3132 D BluetoothMap: Proxy object disconnected
11-08 17:09:52.298  3132  3132 D MapProfile: Bluetooth service disconnected
11-08 17:09:52.299  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:52.299  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:52.299  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:52.299  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:52.299  4675  4675 D SapService: Received stop request...Stopping profile...
11-08 17:09:52.299  4675  4675 V SapService: stop()
11-08 17:09:52.301  4675  4735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-08 17:09:52.301  4675  4880 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:52.301  4675  4880 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:52.301  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:52.302  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:52.302  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:52.302  4675  4880 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 17:09:52.302  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:52.302  4675  4880 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 17:09:52.302  4675  4880 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 17:09:52.302  4675  4880 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 17:09:52.302  4675  4675 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-08 17:09:52.303  4675  4675 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 17:09:52.303  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:52.303  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:52.303  4675  4735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 17:09:52.303  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:52.303  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:52.303  4675  4675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 17:09:52.303  4675  4735 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-08 17:09:52.304  4675  4675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-08 17:09:52.304  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:52.304  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:52.304  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:52.304  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:52.304  4675  4675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-08 17:09:52.305  4675  4675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-08 17:09:52.305  4675  4675 D BluetoothMapService: MAP Service closeService in
11-08 17:09:52.306  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:52.306  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:52.306  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:52.306  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:52.306  4675  4675 D BluetoothMapService: cleanup()
11-08 17:09:52.306  4675  4675 D BluetoothMapService: MAP Service closeService in
11-08 17:09:52.307  4675  4675 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:52.307  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:52.307  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:52.307  4675  4675 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:52.307  4675  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-08 17:09:52.307  4675  4731 D BluetoothAdapterProperties: Setting state to 15
11-08 17:09:52.307  4675  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-08 17:09:52.308  4675  4731 I BluetoothAdapterState: Entering BleOnState
11-08 17:09:52.308  3132  3374 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:52.309  3762  3791 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:52.309  3132  3147 D BluetoothMap: onBluetoothStateChange: up=false
11-08 17:09:52.310   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:52.310  3132  3146 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 17:09:52.311  3132  3978 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 17:09:52.312   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 17:09:52.312  3132  3374 D BluetoothPan: onBluetoothStateChange on: false
11-08 17:09:52.313  3132  3147 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 17:09:52.314   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:52.314   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:52.314  4675  4731 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-08 17:09:52.314  4675  4731 D BluetoothAdapterProperties: Setting state to 16
11-08 17:09:52.314  4675  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 17:09:52.315  4675  4731 D BluetoothAdapterProperties: onBleDisable
11-08 17:09:52.315  4675  4731 I BluetoothAdapterState: Entering PendingCommandState
11-08 17:09:52.315  4675  4732 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-08 17:09:52.317  4675  4735 D BluetoothAdapterProperties: Scan Mode:20
11-08 17:09:52.317  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:52.321  4675  4880 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-08 17:09:52.321  4675  4880 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:52.322  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:52.322  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 10
11-08 17:09:52.322  5609  5609 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: Bluetooth disabled, pausing BLE based peer discovery...
11-08 17:09:52.322  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.322  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[main,5,main], id: 1
,11-08 17:09:52.323  5609  5609 D BluetoothAdapter: STATE_OFF
,11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: BT Adapter is not turned ON
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: java.lang.IllegalStateException: BT Adapter is not turned ON
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeUtils.checkAdapterStateOn(BluetoothLeUtils.java:136)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.bluetooth.le.BluetoothLeScanner.stopScan(BluetoothLeScanner.java:169)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner.stop(BleScanner.java:150)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScanner(BlePeerDiscoverer.java:436)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stopScannerAndAdvertiser(BlePeerDiscoverer.java:503)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.stopBlePeerDiscoverer(DiscoveryManager.java:1217)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.onBluetoothAdapterStateChanged(DiscoveryManager.java:773)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver.onReceive(BluetoothManager.java:564)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:52.331  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:09:52.332  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.332  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.332  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 17:09:52.332  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.333  4675  4737 D BtGatt.AdvertiseManager: message : 1
11-08 17:09:52.334  4675  4737 D BtGatt.AdvertiseManage,r: stop advertise for client 5
11-08 17:09:52.340  4675  4735 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 17:09:52.340  4675  4735 D BtGatt.GattService: Client app is not null!
11-08 17:09:52.341  4675  4686 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:09:52.341  5716  5716 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-08 17:09:52.341  4675  4880 E bt_btif : bta_gattc_deregister Deregister Failedm unknown client cif
11-08 17:09:52.341  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:09:52.342  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:52.342  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:09:52.342  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.342  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:52.342  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.342  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 17:09:52.342  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:09:52.342  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.342  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.342  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 17:09:52.342  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.343  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.343  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
11-08 17:09:52.343  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.343  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.344  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.344  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:52.344  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.344  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 17:09:52.344  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.345  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.345  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.345  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.346  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:52.347  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:52.349  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:52.349  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
11-08 17:09:52.349  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.350  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.350  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.350  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:52.352  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:52.352  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
11-08 17:09:52.352  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 17:09:52.357   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13ae5f0:true
11-08 17:09:52.359  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 17:09:52.371   931  3425 I ActivityManager: Start proc 5728:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-08 17:09:52.379  5716  5716 D LocalBluetoothProfileManager: Adding local MAP profile
11-08 17:09:52.383  5716  5716 D BluetoothMap: Create BluetoothMap proxy object
11-08 17:09:52.392  5716  5716 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
11-08 17:09:52.407  5728  5728 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
11-08 17:09:52.409  5716  5716 D DockEventReceiver: finishStartingService: stopping service
,11-08 17:09:52.411   931  3837 I ActivityManager: Killing 5287:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-08 17:09:52.527  4675  4735 I bt_hci  : shut_down
,11-08 17:09:52.531  4675  4739 D bt_hwcfg: hw_epilog_process
,11-08 17:09:52.531  4675  4739 I bt_vendor: low_power_mode_cb
,11-08 17:09:52.533  4675  4739 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-08 17:09:52.534  4675  4739 I bt_vendor: epilog_cb
11-08 17:09:52.534  4675  4739 I bt_hci  : epilog_finished_callback
,11-08 17:09:52.536  4675  4735 I bt_hci_h4: hal_close
,11-08 17:09:52.536  4675  4735 I bt_userial_vendor: device fd = 54 close
,11-08 17:09:52.628  5728  5728 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 17:09:52.628  5728  5728 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 17:09:52.628  5728  5728 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:52.628  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 17:09:52.638  5728  5728 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 17:09:52.638  5728  5728 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.k.d(PG:583)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.e.b(PG:170)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 17:09:52.638  5728  5728 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:09:52.638  5728  5728 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.File.exists(File.java:361)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:09:52.638,  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:09:52.638  5728  5728 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:52.638  5728  5728 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:09:52.642  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 17:09:52.649  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 17:09:52.651  4675  4732 D bt_stack_manager: event_shut_down_stack finished.
11-08 17:09:52.652  4675  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-08 17:09:52.654  4675  4675 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-08 17:09:52.654  4675  4731 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-08 17:09:52.654  4675  4675 D BtGatt.GattService: Received stop request...Stopping profile...
11-08 17:09:52.654  4675  4675 D BtGatt.GattService: stop()
11-08 17:09:52.654  4675  4675 D BtGatt.AdvertiseManager: advertise clients cleared
,11-08 17:09:52.655  5716  5716 D DockEventReceiver: finishStartingService: stopping service
,11-08 17:09:52.656  4675  4675 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:09:52.656  4675  4675 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:52.656  4675  4675 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:52.656  4675  4675 V BluetoothAdapterState: isBleTurningOff()=true
11-08 17:09:52.656  4675  4731 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-08 17:09:52.656  4675  4731 D BluetoothAdapterProperties: Setting state to 10
11-08 17:09:52.656  4675  4731 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-08 17:09:52.656   931  3202 I ActivityManager: Killing 3875:com.android.providers.calendar/u0a1 (adj 15): empty #17
11-08 17:09:52.657  4675  4731 I BluetoothAdapterState: Entering OffState
11-08 17:09:52.657   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-08 17:09:52.686  4675  4675 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-08 17:09:52.686  4675  4675 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-08 17:09:52.686  4675  4675 I BluetoothServiceJni: cleanupNative: return from cleanup
11-08 17:09:52.687  4675  4732 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-08 17:09:52.689  4675  4675 I art     : System.exit called, status: 0
,11-08 17:09:52.689  4675  4675 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 17:09:52.724   931  3840 I ActivityManager: Process com.android.bluetooth (pid 4675) has died
,11-08 17:09:52.749  5609  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:52.762   931   948 I ActivityManager: Start proc 5760:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-08 17:09:52.824  5760  5760 D AdapterServiceConfig: Adding HeadsetService
,11-08 17:09:52.824  5760  5760 D AdapterServiceConfig: Adding A2dpService
,11-08 17:09:52.825  5760  5760 D AdapterServiceConfig: Adding HidService
11-08 17:09:52.825  5760  5760 D AdapterServiceConfig: Adding HealthService
,11-08 17:09:52.825  5760  5760 D AdapterServiceConfig: Adding PanService
11-08 17:09:52.825  5760  5760 D AdapterServiceConfig: Adding GattService
11-08 17:09:52.825  5760  5760 D AdapterServiceConfig: Adding BluetoothMapService
11-08 17:09:52.825  5760  5760 D AdapterServiceConfig: Adding SapService
,11-08 17:09:52.836   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9eecb76:true
,11-08 17:09:52.836  5760  5760 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 17:09:52.839  5760  5760 I bt_bluedroid: init
,11-08 17:09:52.839  5760  5772 I BluetoothAdapterState: Entering OffState
,11-08 17:09:52.841  5760  5773 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-08 17:09:52.841  5760  5773 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 17:09:52.841  5760  5773 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-08 17:09:52.841  5760  5773 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-08 17:09:52.841  5760  5760 I bt_bluedroid: get_profile_interface socket
,11-08 17:09:52.843  5760  5760 I bt_bluedroid: get_profile_interface sdp
,11-08 17:09:52.843  5760  5776 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 17:09:52.844  5760  5776 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 17:09:52.846  5760  5771 I bt_bluedroid: config_hci_snoop_log
,11-08 17:09:52.847   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-08 17:09:52.852  5760  5772 D BluetoothAdapterState: Current state: OFF, message: 0
,11-08 17:09:52.852  5760  5772 D BluetoothAdapterProperties: Setting state to 14
11-08 17:09:52.852  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-08 17:09:52.853  5609  5609 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 17:09:52.855  5760  5772 D BluetoothBondStateMachine: make
,11-08 17:09:52.856  5760  5777 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-08 17:09:52.858  5728  5748 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
11-08 17:09:52.859  5760  5772 I BluetoothAdapterState: Entering PendingCommandState
11-08 17:09:52.860  5760  5760 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-08 17:09:52.862  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
,11-08 17:09:52.863  5760  5760 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-08 17:09:52.863  5760  5760 D BtGatt.GattService: Received start request. Starting profile...
,11-08 17:09:52.863  5760  5760 D BtGatt.GattService: start()
,11-08 17:09:52.864  5760  5760 I bt_bluedroid: get_profile_interface gatt
11-08 17:09:52.864  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:09:52.865  5760  5760 D BtGatt.AdvertiseManager: advertise manager created
11-08 17:09:52.870  5760  5760 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:52.870  5760  5760 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:52.870  5760  5760 V BluetoothAdapterState: isBleTurningOn()=true
11-08 17:09:52.870  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:52.870  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 17:09:52.871  5760  5772 I bt_bluedroid: bt_bluedroid
,11-08 17:09:52.871  5760  5773 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-08 17:09:52.872  5760  5773 I bt_hci  : start_up
,11-08 17:09:52.872   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a2ec6f:true
11-08 17:09:52.876  5760  5773 I bt_vendor: alloc value 0xf3fff871
11-08 17:09:52.876  5760  5773 I bt_vendor: init
11-08 17:09:52.876  5760  5773 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 17:09:52.877  5760  5773 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 17:09:52.986  5760  5773 D bt_hci  : start_up starting async portion
11-08 17:09:52.986  5760  5781 I bt_hci  : event_finish_startup
,11-08 17:09:52.986  5760  5781 I bt_hci_h4: hal_open
11-08 17:09:52.986  5760  5781 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-08 17:09:52.985  5783  5783 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 17:09:52.989  5760  5781 I bt_userial_vendor: device fd = 54 open
,11-08 17:09:53.002  5760  5781 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 17:09:53.004  5760  5781 D bt_hwcfg: Chipset BCM4358A3
11-08 17:09:53.004  5760  5781 D bt_hwcfg: Target name = [BCM4358A3]
,11-08 17:09:53.004  5760  5781 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-08 17:09:53.257  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 17:09:53.358  5760  5781 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-08 17:09:53.359  5760  5781 D bt_hwcfg: Settlement delay -- 100 ms
,11-08 17:09:53.359  5760  5781 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 17:09:53.483  5760  5781 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-08 17:09:53.483  5760  5781 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-08 17:09:53.484  5760  5781 I bt_hwcfg: vendor lib fwcfg completed
11-08 17:09:53.484  5760  5781 I bt_vendor: firmware callback
11-08 17:09:53.485  5760  5781 I bt_hci  : firmware_config_callback
,11-08 17:09:53.494  5760  5785 I bt_btu  : btu_task pending for preload complete event
,11-08 17:09:53.495  5760  5785 I bt_btu_task: Bluetooth chip preload is complete
,11-08 17:09:53.495  5760  5785 I bt_btu  : btu_task received preload complete event
,11-08 17:09:53.503  5760  5785 I         : BTE_InitTraceLevels -- TRC_HCI
,11-08 17:09:53.503  5760  5785 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-08 17:09:53.503  5760  5785 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-08 17:09:53.504  5760  5785 I         : BTE_InitTraceLevels -- TRC_AVDT
11-08 17:09:53.504  5760  5785 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-08 17:09:53.504  5760  5785 I         : BTE_InitTraceLevels -- TRC_A2D
,11-08 17:09:53.504  5760  5785 I         : BTE_InitTraceLevels -- TRC_BNEP
11-08 17:09:53.505  5760  5785 I         : BTE_InitTraceLevels -- TRC_BTM
11-08 17:09:53.505  5760  5785 I         : BTE_InitTraceLevels -- TRC_GAP
11-08 17:09:53.505  5760  5785 I         : BTE_InitTraceLevels -- TRC_PAN
,11-08 17:09:53.505  5760  5785 I         : BTE_InitTraceLevels -- TRC_SDP
11-08 17:09:53.505  5760  5785 I         : BTE_InitTraceLevels -- TRC_GATT
11-08 17:09:53.505  5760  5785 I         : BTE_InitTraceLevels -- TRC_SMP
11-08 17:09:53.505  5760  5785 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-08 17:09:53.505  5760  5785 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 17:09:53.584  5760  5785 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f7d549
,11-08 17:09:53.584  5760  5785 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f7d549 
,11-08 17:09:53.596  5760  5776 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-08 17:09:53.597  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-08 17:09:53.598  5760  5776 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-08 17:09:53.602  5760  5776 D BluetoothAdapterProperties: Name is: Nexus 6P
11-08 17:09:53.605  5760  5776 D BluetoothAdapterProperties: Scan Mode:20
,11-08 17:09:53.605  5760  5776 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 17:09:53.605  5760  5776 D bt_hci  : do_postload posting postload work item
11-08 17:09:53.606  5760  5781 I bt_hci  : event_postload
11-08 17:09:53.606  5760  5781 I bt_vendor: sco_config_cb
,11-08 17:09:53.606  5760  5781 I bt_hci  : sco_config_callback postload finished.
,11-08 17:09:53.609  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.613  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.613  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 20
,11-08 17:09:53.614  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.614  5760  5776 D bt_bte_conf: Device ID record 1 : primary
,11-08 17:09:53.615  5760  5776 D bt_bte_conf:   vendorId            = 000f
11-08 17:09:53.615  5760  5776 D bt_bte_conf:   vendorIdSource      = 0001
11-08 17:09:53.615  5760  5776 D bt_bte_conf:   product             = 1200
11-08 17:09:53.615  5760  5776 D bt_bte_conf:   version             = 1436
,11-08 17:09:53.615  5760  5776 D bt_bte_conf:   clientExecutableURL = 
11-08 17:09:53.615  5760  5776 D bt_bte_conf:   serviceDescription  = 
11-08 17:09:53.615  5760  5776 D bt_bte_conf:   documentationURL    = 
11-08 17:09:53.615  5760  5776 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-08 17:09:53.616  5760  5773 D bt_stack_manager: event_start_up_stack finished
11-08 17:09:53.618  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.618  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-08 17:09:53.618  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-08 17:09:53.621  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:53.622  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-08 17:09:53.623  5760  5772 D BluetoothAdapterProperties: Setting state to 15
11-08 17:09:53.623  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 17:09:53.623  5760  5781 I bt_vendor: low_power_mode_cb
11-08 17:09:53.624  5760  5772 I BluetoothAdapterState: Entering BleOnState
,11-08 17:09:53.627  5760  5772 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-08 17:09:53.627  5760  5772 D BluetoothAdapterProperties: Setting state to 11
11-08 17:09:53.627  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-08 17:09:53.632  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
,11-08 17:09:53.635  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:53.637  5760  5760 D HeadsetService: Received start request. Starting profile...
11-08 17:09:53.640  5760  5760 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-08 17:09:53.640  5760  5760 D HeadsetStateMachine: make
11-08 17:09:53.642  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.642  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 11
11-08 17:09:53.644  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.647  5760  5772 I BluetoothAdapterState: Entering PendingCommandState
,11-08 17:09:53.649  5760  5760 D HeadsetStateMachine: max_hf_connections = 1
,11-08 17:09:53.649  5760  5760 I bt_bluedroid: get_profile_interface handsfree
,11-08 17:09:53.650  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-08 17:09:53.650  5760  5776 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-08 17:09:53.653  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:09:53.653  5760  5760 D A2dpService: Received start request. Starting profile...
,11-08 17:09:53.654  5760  5760 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-08 17:09:53.655  5760  5760 I bt_bluedroid: get_profile_interface avrcp
,11-08 17:09:53.661  5760  5760 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-08 17:09:53.661  5760  5760 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-08 17:09:53.661  5760  5760 D A2dpStateMachine: make
,11-08 17:09:53.662  5760  5760 I bt_bluedroid: get_profile_interface a2dp
,11-08 17:09:53.663  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-08 17:09:53.664  5760  5793 D A2dpStateMachine: Enter Disconnected: -2
,11-08 17:09:53.666  5760  5760 I BluetoothHidServiceJni: classInitNative: succeeds
11-08 17:09:53.667  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:09:53.667  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 17:09:53.669  5760  5760 D HidService: Received start request. Starting profile...
11-08 17:09:53.669  5760  5760 I bt_bluedroid: get_profile_interface hidhost
11-08 17:09:53.669  5760  5760 D HidService: setHidService(): set to: null
,11-08 17:09:53.669  5760  5776 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f5e56d
11-08 17:09:53.669  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-08 17:09:53.669  5760  5760 I BluetoothHealthServiceJni: classInitNative: succeeds
11-08 17:09:53.670  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:09:53.671  5760  5760 D HealthService: Received start request. Starting profile...
11-08 17:09:53.671  5716  5716 D BluetoothInputDevice: Proxy object connected
,11-08 17:09:53.672  5716  5716 D HidProfile: Bluetooth service connected
11-08 17:09:53.672  5760  5760 I bt_bluedroid: get_profile_interface health
11-08 17:09:53.673  5760  5760 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-08 17:09:53.674  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:09:53.675  5716  5716 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 17:09:53.675  5760  5760 D PanService: Received start request. Starting profile...
11-08 17:09:53.675  5760  5760 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 17:09:53.675  5760  5760 I bt_bluedroid: get_profile_interface pan
11-08 17:09:53.675  5716  5716 D PanProfile: Bluetooth service connected
11-08 17:09:53.676  5760  5776 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-08 17:09:53.678  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
,11-08 17:09:53.679  5716  5716 D BluetoothMap: Proxy object connected
,11-08 17:09:53.679  5716  5716 D MapProfile: Bluetooth service connected
11-08 17:09:53.679  5760  5760 D BluetoothMapService: Received start request. Starting profile...
11-08 17:09:53.679  5716  5716 D BluetoothMap: getConnectedDevices()
11-08 17:09:53.679  5760  5760 D BluetoothMapService: start()
11-08 17:09:53.680  5716  5716 D BluetoothMap: Bluetooth is Not enabled
,11-08 17:09:53.682  5760  5760 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-08 17:09:53.683  5760  5760 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-08 17:09:53.683  5760  5760 D BluetoothMapAppObserver: createReceiver()
,11-08 17:09:53.684  5760  5760 D BluetoothMapAppObserver: initObservers()
,11-08 17:09:53.684  5760  5760 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-08 17:09:53.693  5760  5760 V SapService: SapBinder()
11-08 17:09:53.693  5760  5760 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
,11-08 17:09:53.694  5760  5760 D SapService: Received start request. Starting profile...
11-08 17:09:53.694  5760  5760 V SapService: start()
,11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isTurningOn()=true
,11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.696  5760  5791 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:53.696  5760  5760 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:53.697  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.697  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.697  5760  5760 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:53.697  5760  5760 V BluetoothAdapterState: isTurningOn()=true
,11-08 17:09:53.697  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
,11-08 17:09:53.697  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.698  5760  5760 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:53.698  5760  5760 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:53.698  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.698  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.698  5760  5760 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:53.698  5760  5760 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:53.698  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.698  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.699  5760  5760 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:53.699  5760  5760 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:53.699  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.699  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.699  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-08 17:09:53.699  5760  5772 D BluetoothAdapterProperties: ScanMode =  20
11-08 17:09:53.699  5760  5772 D BluetoothAdapterProperties: State =  11
,11-08 17:09:53.700  5760  5772 D BluetoothAdapterProperties: Setting state to 12
11-08 17:09:53.700  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-08 17:09:53.700  5760  5772 I BluetoothAdapterState: Entering OnState
11-08 17:09:53.700  3132  3147 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:53.701  3762  3791 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:53.701  5716  5726 D BluetoothPan: onBluetoothStateChange on: true
11-08 17:09:53.702  5716  5727 D BluetoothMap: onBluetoothStateChange: up=true
11-08 17:09:53.702  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 17:09:53.702  5716  5726 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 17:09:53.703  3132  3146 D BluetoothMap: onBluetoothStateChange: up=true
11-08 17:09:53.703  5760  5776 D BluetoothAdapterProperties: Scan Mode:21
11-08 17:09:53.703  5760  5776 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 17:09:53.704  3132  3132 D BluetoothMap: Proxy object connected
11-08 17:09:53.704   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:53.704  3132  3132 D MapProfile: Bluetooth service connected
11-08 17:09:53.704  3132  3132 D BluetoothMap: getConnectedDevices()
11-08 17:09:53.704  3132  3374 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 17:09:53.705  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-08 17:09:53.706  3132  3147 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-08 17:09:53.708  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-08 17:09:53.708  3132  3132 D BluetoothA2dp: Proxy object connected
11-08 17:09:53.710   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-08 17:09:53.711  5760  5760 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 17:09:53.712  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:53.712  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:53.712  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:53.712  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:53.712  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:53.712  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:53.712  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:53.712  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:53.712  5760  5760 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-08 17:09:53.713  5760  5760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:09:53.713  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:53.714  3132  3132 D BluetoothInputDevice: Proxy object connected
11-08 17:09:53.714  3132  3132 D HidProfile: Bluetooth service connected
11-08 17:09:53.715  3132  3978 D BluetoothPan: onBluetoothStateChange on: true
11-08 17:09:53.715   931   931 D BluetoothA2dp: Proxy object connected
11-08 17:09:53.716  3132  3147 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 17:09:53.717  3132  3132 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 17:09:53.717  3132  3132 D PanProfile: Bluetooth service connected
11-08 17:09:53.717  5760  5760 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:09:53.718  5716  5727 D BluetoothPbap: onBluetoothStateChange: up=true
,11-08 17:09:53.720  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:53.720  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:53.720  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:53.720  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:53.720  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:53.720  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:53.720  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:53.720  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:53.720   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:53.721   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:53.722  5760  5760 D ObexServerSockets: Succeed to create listening sockets 
,11-08 17:09:53.722  5760  5760 D ObexServerSockets0: startAccept()
11-08 17:09:53.722  5760  5760 D ObexServerSockets0: prepareForNewConnect()
11-08 17:09:53.722  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:53.722  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Mode changed to 21
11-08 17:09:53.723  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterScanModeChanged: Bluetooth enabled, restarting BLE based peer discovery...
11-08 17:09:53.723  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-08 17:09:53.724  5760  5760 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-08 17:09:53.724  5760  5760 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-08 17:09:53.725  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 17:09:53.725  5609  5609 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:09:53.725  5609  5609 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 17:09:53.725  5760  5760 D BluetoothMapService: onReceive
11-08 17:09:53.726  5760  5760 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 17:09:53.726  5716  5716 D LocalBluetoothProfileManager: Adding local A2DP profile
11-08 17:09:53.726  5760  5760 D BluetoothMapService: STATE_ON
11-08 17:09:53.728  5760  5799 D ObexServerSockets0: Accepting socket connection...
11-08 17:09:53.729   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-08 17:09:53.730  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-08 17:09:53.730  5760  5802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:09:53.730  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:09:53.731  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:09:53.731  5760  5800 D ObexServerSockets0: Accepting socket connection...
,11-08 17:09:53.731  5716  5716 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-08 17:09:53.732  5760  5802 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 17:09:53.732  5760  5802 D BluetoothSdpJni: SDP Create record success - handle: 1
11-08 17:09:53.733  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.733  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:09:53.733  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:09:53.733  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-08 17:09:53.733  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:09:53.733  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.733  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.733  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.734  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.734  5609  5609 D BluetoothAdapter: STATE_ON
11-08 17:09:53.737  5760  5770 D BtGatt.GattService: registerClient() - UUID=f1d010b1-7b6f-414c-a8e2-3f5ee9546a05
11-08 17:09:53.737  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 17:09:53.738  5760  5776 D BtGatt.GattService: onClientRegistered() - UUID=f1d010b1-7b6f-414c-a8e2-3f5ee9546a05, clientIf=5
11-08 17:09:53.738  5609  5648 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-08 17:09:53.740  5760  5778 D BtGatt.AdvertiseManager: message : 0
11-08 17:09:53.740  5716  5716 D BluetoothA2dp: Proxy object connected
,11-08 17:09:53.742  5760  5778 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:09:53.745  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 17:09:53.745  5716  5716 D DockEventReceiver: finishStartingService: stopping service
,11-08 17:09:53.747  5760  5776 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:09:53.751  5760  5776 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:09:53.752  5760  5760 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-08 17:09:53.752  5760  5760 D ObexServerSockets0: prepareForNewConnect()
11-08 17:09:53.752  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.752  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.752  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 17:09:53.752  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.752  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.752  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.752  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.753  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.753  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 17:09:53.753  5716  5716 D BluetoothPbap: Proxy object connected
11-08 17:09:53.754  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:09:53.754  5716  5716 D PbapServerProfile: Bluetooth service connected
,11-08 17:09:53.754  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.755  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.755  3132  3132 D BluetoothPbap: Proxy object connected
11-08 17:09:53.755  3132  3132 D PbapServerProfile: Bluetooth service connected
11-08 17:09:53.755  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-08 17:09:53.755  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.755  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.760  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:53.760  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:53.760  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:53.760  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:53.760  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:53.760  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:53.760  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:53.760  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:53.763  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:53.763  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 17:09:53.764  5760  5806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:09:53.764  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:53.765  5609  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:53.766  5609  5657 D io.jxcore.node.ConnectivityMonitor: stop
,11-08 17:09:53.766  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 17:09:53.768  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.768  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: State changed to 12
11-08 17:09:53.768  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBluetoothAdapterStateChanged: Bluetooth enabled, restarting BLE based peer discovery...
11-08 17:09:53.769  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-08 17:09:53.769  5609  5657 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-08 17:09:53.769  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:09:53.769  5609  5609 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:09:53.770  5609  5657 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-08 17:09:53.771  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[main,5,main], id: 1
,11-08 17:09:53.771  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-08 17:09:53.771  5609  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.771  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-08 17:09:53.771  5609  5609 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-08 17:09:53.772  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.772  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.772  5760  5778 D BtGatt.AdvertiseManager: message : 1
11-08 17:09:53.773  5760  5778 D BtGatt.AdvertiseManager: stop advertise for client 5
11-08 17:09:53.773  5760  5772 D BluetoothAdapterState: Current state: ON, message: 23
11-08 17:09:53.773  5760  5772 D BluetoothAdapterProperties: Setting state to 13
11-08 17:09:53.773  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-08 17:09:53.774  5760  5772 D BluetoothAdapterProperties: onBluetoothDisable()
11-08 17:09:53.775  5760  5776 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 17:09:53.775  5760  5776 D BtGatt.GattService: Client app is not null!
11-08 17:09:53.775  5760  5772 I BluetoothAdapterState: Entering PendingCommandState
11-08 17:09:53.777  5760  5789 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:09:53.778  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 17:09:53.778  5760  5760 D BluetoothMapService: onReceive
11-08 17:09:53.779  5760  5760 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 17:09:53.779  5760  5760 D BluetoothMapService: STATE_TURNING_OFF
11-08 17:09:53.779  5760  5760 D BluetoothMapService: MAP Service closeService in
11-08 17:09:53.779  5760  5760 D BluetoothMapMasInstance0: MAP Service shutdown
11-08 17:09:53.779  5760  5760 D ObexServerSockets0: shutdown(block = true)
11-08 17:09:53.780  5760  5760 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 17:09:53.780  5760  5799 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-08 17:09:53.780  5760  5760 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-08 17:09:53.780  5760  5800 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-08 17:09:53.780  5760  5776 D BluetoothAdapterProperties: Scan Mode:20
11-08 17:09:53.781  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-08 17:09:53.781  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-08 17:09:53.781  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.781  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to NOT_STARTED
11-08 17:09:53.781  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.781  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.781  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.781  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.782  5609  5609 D BluetoothAdapter: STATE_OFF
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Failed to start advertising: BT Adapter is not turned ON
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: java.lang.IllegalStateException: BT Adapter is not turned ON
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.bluetooth.le.BluetoothLeUtils.checkAdapterStateOn(BluetoothLeUtils.java:136)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.bluetooth.le.BluetoothLeAdvertiser.startAdvertising(BluetoothLeAdvertiser.java:110)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.start(BleAdvertiser.java:158)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.setAdvertiseData(BleAdvertiser.java:113)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.startAdvertiser(BlePeerDiscoverer.java:463)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscoverer(DiscoveryManager.java:1192)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:500)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:451)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.onBluetoothAdapterStateChanged(DiscoveryManager.java:781)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver.onReceive(BluetoothManager.java:564)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bl,uetooth.le.BleAdvertiser: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:53.783  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:09:53.783  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.783  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.783  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.783  5760  5787 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-08 17:09:53.783  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.784  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.784  5716  5716 D DockEventReceiver: finishStartingService: stopping service
11-08 17:09:53.785  5609  5609 D BluetoothAdapter: STATE_OFF
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Failed to start advertising: BT Adapter is not turned ON
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: java.lang.IllegalStateException: BT Adapter is not turned ON
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.bluetooth.le.BluetoothLeUtils.checkAdapterStateOn(BluetoothLeUtils.java:136)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.bluetooth.le.BluetoothLeAdvertiser.startAdvertising(BluetoothLeAdvertiser.java:110)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.start(BleAdvertiser.java:158)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.startAdvertiser(BlePeerDiscoverer.java:464)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscoverer(DiscoveryManager.java:1192)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:500)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btco,nnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:451)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.onBluetoothAdapterStateChanged(DiscoveryManager.java:781)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver.onReceive(BluetoothManager.java:564)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:09:53.786  5609  5609 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:09:53.786  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = NOT_STARTEDCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.786  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.786  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = falseCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.786  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 17:09:53.787  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 17:09:53.787  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.789  5760  5760 D HeadsetService: Received stop request...Stopping profile...
11-08 17:09:53.789  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.790  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.790  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.790  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.790  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 17:09:53.792  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.792  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.792  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.794  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:53.794  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:53.794  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:53.794  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:53.794  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:53.794  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:09:53.794  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:53.794  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:53.794  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:53.795  5760  5760 D A2dpService: Received stop request...Stopping profile...
11-08 17:09:53.795  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:53.795  5760  5793 D A2dpStateMachine: Exit Disconnected: -1
11-08 17:09:53.795  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:53.795  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.795  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.795  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to RUNNING
11-08 17:09:53.795  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.795  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.795  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.795  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:09:53.795  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:09:53.795  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.796  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.796  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 17:09:53.796  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.796   931   931 D BluetoothA2dp: Proxy object disconnected
11-08 17:09:53.796  3132  3132 D BluetoothA2dp: Proxy object disconnected
11-08 17:09:53.798  5716  5716 D BluetoothA2dp: Proxy object disconnected
11-08 17:09:53.798  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.798  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:09:53.798  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.798  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.798  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:53.798  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:53.798  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:09:53.800  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:53.800  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:53.800  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:53.800  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:53.800  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:53.800  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:09:53.800  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:53.800  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:53.800  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:53.801  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:53.801  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:53.801  5760  5760 D HidService: Received stop request...Stopping profile...
11-08 17:09:53.801  5760  5760 D HidService: Stopping Bluetooth HidService
11-08 17:09:53.802  5716  5716 D BluetoothInputDevice: Proxy object disconnected
11-08 17:09:53.802  5716  5716 D HidProfile: Bluetooth service disconnected
11-08 17:09:53.803  5760  5760 D HealthService: Received stop request...Stopping profile...
11-08 17:09:53.803  3132  3132 D BluetoothInputDevice: Proxy object disconnected
11-08 17:09:53.803  3132  3132 D HidProfile: Bluetooth service disconnected
11-08 17:09:53.803  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:53.803  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:53.803  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:53.803  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:53.803  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:53.803  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-08 17:09:53.803  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:53.803  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:53.803  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:53.804  5609  5609 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-08 17:09:53.804  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:53.804  5760  5760 D PanService: Received stop request...Stopping profile...
11-08 17:09:53.805  3132  3132 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 17:09:53.805  3132  3132 D PanProfile: Bluetooth service disconnected
11-08 17:09:53.805  5716  5716 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-08 17:09:53.805  5716  5716 D PanProfile: Bluetooth service disconnected
11-08 17:09:53.806  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.806  3132  3132 D BluetoothPbap: Proxy object disconnected
11-08 17:09:53.806  3132  3132 D PbapServerProfile: Bluetooth service disconnected
11-08 17:09:53.807  5716  5716 D BluetoothPbap: Proxy object disconnected
11-08 17:09:53.807  5716  5716 D PbapServerProfile: Bluetooth service disconnected
11-08 17:09:53.807  5760  5760 D BluetoothMapService: Received stop request...Stopping profile...
11-08 17:09:53.807  5760  5760 D BluetoothMapService: stop()
11-08 17:09:53.808  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.808  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:09:53.808  5760  5760 D BluetoothMapAppObserver: deinitObservers()
11-08 17:09:53.808  5760  5760 D BluetoothMapAppObserver: removeReceiver()
11-08 17:09:53.809  3132  3132 D BluetoothMap: Proxy object disconnected
11-08 17:09:53.809  3132  3132 D MapProfile: Bluetooth service disconnected
11-08 17:09:53.809  5716  5716 D BluetoothMap: Proxy object disconnected
11-08 17:09:53.809  5716  5716 D MapProfile: Bluetooth service disconnected
11-08 17:09:53.810  5760  5760 D SapService: Received stop request...Stopping profile...
11-08 17:09:53.810  5760  5760 V SapService: stop()
11-08 17:09:53.811  5760  5760 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:53.811  5760  5760 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:53.811  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.811  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.815  5760  5760 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-08 17:09:53.815  5760  5760 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-08 17:09:53.815  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-08 17:09:53.815  5760  5760 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:53.815  5760  5760 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:53.815  5760  5785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:53.815  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.815  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.815  5760  5785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:53.815  5760  5785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:53.815  5760  5776 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-08 17:09:53.816  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-08 17:09:53.816  5760  5760 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:53.816  5760  5760 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:53.816  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.816  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.816  5760  5785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:53.816  5760  5785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:53.816  5760  5760 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-08 17:09:53.816  5760  5760 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-08 17:09:53.817  5760  5785 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 17:09:53.817  5760  5776 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-08 17:09:53.817  5760  5785 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 17:09:53.817  5760  5785 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-08 17:09:53.817  5760  5760 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:53.817  5760  5785 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-08 17:09:53.817  5760  5760 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:53.817  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.817  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.817  5760  5760 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-08 17:09:53.817  5760  5776 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-08 17:09:53.817  5760  5760 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-08 17:09:53.818  5760  5760 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:53.818  5760  5760 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:53.818  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.818  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.818  5760  5760 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-08 17:09:53.818  5760  5760 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-08 17:09:53.819  5760  5760 D BluetoothMapService: MAP Service closeService in
11-08 17:09:53.819  5760  5760 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:53.819  5760  5760 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:53.819  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.819  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.819  5760  5760 D BluetoothMapService: cleanup()
11-08 17:09:53.819  5760  5760 D BluetoothMapService: MAP Service closeService in
11-08 17:09:53.820  5760  5760 V BluetoothAdapterState: isTurningOff()=true
11-08 17:09:53.820  5760  5760 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:53.820  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:53.820  5760  5760 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:53.820  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-08 17:09:53.820  5760  5772 D BluetoothAdapterProperties: Setting state to 15
11-08 17:09:53.820  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-08 17:09:53.821  5760  5772 I BluetoothAdapterState: Entering BleOnState
11-08 17:09:53.821  3132  3374 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:53.821  5716  5727 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 17:09:53.822  3762  3794 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:53.822  5716  5726 D BluetoothPan: onBluetoothStateChange on: false
11-08 17:09:53.822  5716  5727 D BluetoothMap: onBluetoothStateChange: up=false
11-08 17:09:53.823  5716  5726 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 17:09:53.823  3132  3147 D BluetoothMap: onBluetoothStateChange: up=false
11-08 17:09:53.823   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:53.824  3132  3146 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 17:09:53.824  3132  3978 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-08 17:09:53.824   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
11-08 17:09:53.825  3132  3374 D BluetoothPan: onBluetoothStateChange on: false
11-08 17:09:53.825  3132  3147 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 17:09:53.825  5716  5727 D BluetoothPbap: onBluetoothStateChange: up=false
11-08 17:09:53.826   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:53.826  5716  5726 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:53.826   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
11-08 17:09:53.826  5760  5772 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-08 17:09:53.826  5760  5772 D BluetoothAdapterProperties: Setting state to 16
,11-08 17:09:53.826  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-08 17:09:53.827  5760  5772 D BluetoothAdapterProperties: onBleDisable
11-08 17:09:53.827  5760  5772 I BluetoothAdapterState: Entering PendingCommandState
11-08 17:09:53.828  5760  5773 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-08 17:09:53.828  5760  5776 D BluetoothAdapterProperties: Scan Mode:20
11-08 17:09:53.829  5760  5785 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-08 17:09:53.829  5760  5785 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-08 17:09:53.829  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.831  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-08 17:09:53.831  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.833  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.835  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:53.837  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 17:09:53.841  5716  5716 D DockEventReceiver: finishStartingService: stopping service
,11-08 17:09:54.029  5760  5776 I bt_hci  : shut_down
,11-08 17:09:54.029  5760  5781 D bt_hwcfg: hw_epilog_process
11-08 17:09:54.030  5760  5781 I bt_vendor: low_power_mode_cb
,11-08 17:09:54.032  5760  5781 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-08 17:09:54.032  5760  5781 I bt_vendor: epilog_cb
11-08 17:09:54.032  5760  5781 I bt_hci  : epilog_finished_callback
11-08 17:09:54.033  5760  5776 I bt_hci_h4: hal_close
,11-08 17:09:54.033  5760  5776 I bt_userial_vendor: device fd = 54 close
,11-08 17:09:54.157  5760  5773 D bt_stack_manager: event_shut_down_stack finished.
,11-08 17:09:54.158  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-08 17:09:54.161  5760  5772 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-08 17:09:54.161  5760  5760 D BtGatt.DebugUtils: handleDebugAction() action=null
11-08 17:09:54.163  5760  5760 D BtGatt.GattService: Received stop request...Stopping profile...
,11-08 17:09:54.163  5760  5760 D BtGatt.GattService: stop()
,11-08 17:09:54.164  5760  5760 D BtGatt.AdvertiseManager: advertise clients cleared
,11-08 17:09:54.168  5760  5760 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:09:54.168  5760  5760 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:54.168  5760  5760 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:54.169  5760  5760 V BluetoothAdapterState: isBleTurningOff()=true
11-08 17:09:54.169  5760  5772 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-08 17:09:54.169  5760  5772 D BluetoothAdapterProperties: Setting state to 10
,11-08 17:09:54.169  5760  5772 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-08 17:09:54.170  5760  5772 I BluetoothAdapterState: Entering OffState
11-08 17:09:54.171   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-08 17:09:54.183  5760  5760 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-08 17:09:54.183  5760  5760 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-08 17:09:54.184  5760  5760 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-08 17:09:54.186  5760  5773 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-08 17:09:54.194  5760  5760 I art     : System.exit called, status: 0
,11-08 17:09:54.194  5760  5760 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-08 17:09:54.225   931  3131 I ActivityManager: Process com.android.bluetooth (pid 5760) has died
,11-08 17:09:54.273  5609  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:54.277  5609  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:54.306   931   948 I ActivityManager: Start proc 5816:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-08 17:09:54.309  5609  5609 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-08 17:09:54.383  5816  5816 D AdapterServiceConfig: Adding HeadsetService
11-08 17:09:54.383  5816  5816 D AdapterServiceConfig: Adding A2dpService
11-08 17:09:54.383  5816  5816 D AdapterServiceConfig: Adding HidService
11-08 17:09:54.383  5816  5816 D AdapterServiceConfig: Adding HealthService
11-08 17:09:54.384  5816  5816 D AdapterServiceConfig: Adding PanService
11-08 17:09:54.384  5816  5816 D AdapterServiceConfig: Adding GattService
11-08 17:09:54.384  5816  5816 D AdapterServiceConfig: Adding BluetoothMapService
11-08 17:09:54.384  5816  5816 D AdapterServiceConfig: Adding SapService
,11-08 17:09:54.394   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fd2202f:true
,11-08 17:09:54.395  5816  5816 D BluetoothAdapterState: make() - Creating AdapterState
,11-08 17:09:54.397  5816  5816 I bt_bluedroid: init
11-08 17:09:54.398  5816  5828 I BluetoothAdapterState: Entering OffState
,11-08 17:09:54.399  5816  5829 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-08 17:09:54.399  5816  5829 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-08 17:09:54.400  5816  5829 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-08 17:09:54.400  5816  5829 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-08 17:09:54.400  5816  5816 I bt_bluedroid: get_profile_interface socket
11-08 17:09:54.401  5816  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-08 17:09:54.402  5816  5816 I bt_bluedroid: get_profile_interface sdp
,11-08 17:09:54.403  5816  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-08 17:09:54.406  5816  5827 I bt_bluedroid: config_hci_snoop_log
,11-08 17:09:54.408   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-08 17:09:54.417  5816  5828 D BluetoothAdapterState: Current state: OFF, message: 0
,11-08 17:09:54.417  5816  5828 D BluetoothAdapterProperties: Setting state to 14
11-08 17:09:54.417  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-08 17:09:54.418  5816  5828 D BluetoothBondStateMachine: make
,11-08 17:09:54.420  5816  5834 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-08 17:09:54.423  5816  5828 I BluetoothAdapterState: Entering PendingCommandState
,11-08 17:09:54.423  5816  5816 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-08 17:09:54.426  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
,11-08 17:09:54.426  5816  5816 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-08 17:09:54.427  5816  5816 D BtGatt.GattService: Received start request. Starting profile...
11-08 17:09:54.427  5816  5816 D BtGatt.GattService: start()
,11-08 17:09:54.427  5816  5816 I bt_bluedroid: get_profile_interface gatt
,11-08 17:09:54.428  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:09:54.428  5816  5816 D BtGatt.AdvertiseManager: advertise manager created
,11-08 17:09:54.433  5816  5816 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:09:54.434  5816  5816 V BluetoothAdapterState: isTurningOn()=false
11-08 17:09:54.434  5816  5816 V BluetoothAdapterState: isBleTurningOn()=true
11-08 17:09:54.434  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:54.434  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-08 17:09:54.435  5816  5828 I bt_bluedroid: bt_bluedroid
,11-08 17:09:54.435  5816  5829 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-08 17:09:54.436  5816  5829 I bt_hci  : start_up
,11-08 17:09:54.442  5816  5829 I bt_vendor: alloc value 0xf3fff871
,11-08 17:09:54.442  5816  5829 I bt_vendor: init
11-08 17:09:54.442  5816  5829 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-08 17:09:54.442  5816  5829 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-08 17:09:54.552  5816  5829 D bt_hci  : start_up starting async portion
11-08 17:09:54.553  5816  5837 I bt_hci  : event_finish_startup
,11-08 17:09:54.553  5816  5837 I bt_hci_h4: hal_open
11-08 17:09:54.553  5816  5837 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-08 17:09:54.549  5838  5838 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-08 17:09:54.555  5816  5837 I bt_userial_vendor: device fd = 54 open
,11-08 17:09:54.568  5816  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 17:09:54.571  5816  5837 D bt_hwcfg: Chipset BCM4358A3
,11-08 17:09:54.572  5816  5837 D bt_hwcfg: Target name = [BCM4358A3]
11-08 17:09:54.572  5816  5837 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-08 17:09:54.787  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-08 17:09:54.969  5816  5837 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-08 17:09:54.970  5816  5837 D bt_hwcfg: Settlement delay -- 100 ms
,11-08 17:09:54.970  5816  5837 I bt_hwcfg: Setting fw settlement delay to 100 
,11-08 17:09:55.093  5816  5837 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-08 17:09:55.094  5816  5837 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-08 17:09:55.097  5816  5837 I bt_hwcfg: vendor lib fwcfg completed
11-08 17:09:55.097  5816  5837 I bt_vendor: firmware callback
11-08 17:09:55.097  5816  5837 I bt_hci  : firmware_config_callback
,11-08 17:09:55.107  5816  5840 I bt_btu  : btu_task pending for preload complete event
11-08 17:09:55.107  5816  5840 I bt_btu_task: Bluetooth chip preload is complete
11-08 17:09:55.107  5816  5840 I bt_btu  : btu_task received preload complete event
,11-08 17:09:55.115  5816  5840 I         : BTE_InitTraceLevels -- TRC_HCI
11-08 17:09:55.115  5816  5840 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-08 17:09:55.115  5816  5840 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-08 17:09:55.115  5816  5840 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-08 17:09:55.115  5816  5840 I         : BTE_InitTraceLevels -- TRC_AVRC
11-08 17:09:55.115  5816  5840 I         : BTE_InitTraceLevels -- TRC_A2D
11-08 17:09:55.116  5816  5840 I         : BTE_InitTraceLevels -- TRC_BNEP
11-08 17:09:55.116  5816  5840 I         : BTE_InitTraceLevels -- TRC_BTM
,11-08 17:09:55.116  5816  5840 I         : BTE_InitTraceLevels -- TRC_GAP
11-08 17:09:55.116  5816  5840 I         : BTE_InitTraceLevels -- TRC_PAN
,11-08 17:09:55.116  5816  5840 I         : BTE_InitTraceLevels -- TRC_SDP
11-08 17:09:55.116  5816  5840 I         : BTE_InitTraceLevels -- TRC_GATT
,11-08 17:09:55.116  5816  5840 I         : BTE_InitTraceLevels -- TRC_SMP
11-08 17:09:55.116  5816  5840 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-08 17:09:55.117  5816  5840 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-08 17:09:55.198  5816  5840 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f7d549
11-08 17:09:55.198  5816  5840 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f7d549 
,11-08 17:09:55.204  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:09:55.209  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:09:55.216  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:09:55.218  5816  5832 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = true
,11-08 17:09:55.220  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-08 17:09:55.220  5816  5832 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-08 17:09:55.221  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-08 17:09:55.223  5816  5832 D BluetoothAdapterProperties: Name is: Nexus 6P
11-08 17:09:55.226  5816  5832 D BluetoothAdapterProperties: Scan Mode:20
,11-08 17:09:55.227  5816  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 17:09:55.227  5816  5832 D bt_hci  : do_postload posting postload work item
11-08 17:09:55.227  5816  5837 I bt_hci  : event_postload
11-08 17:09:55.227  5816  5837 I bt_vendor: sco_config_cb
11-08 17:09:55.227  5816  5837 I bt_hci  : sco_config_callback postload finished.
11-08 17:09:55.230  5816  5832 D bt_bte_conf: Device ID record 1 : primary
,11-08 17:09:55.230  5816  5832 D bt_bte_conf:   vendorId            = 000f
11-08 17:09:55.230  5816  5832 D bt_bte_conf:   vendorIdSource      = 0001
11-08 17:09:55.230  5816  5832 D bt_bte_conf:   product             = 1200
11-08 17:09:55.230  5816  5832 D bt_bte_conf:   version             = 1436
,11-08 17:09:55.230  5816  5832 D bt_bte_conf:   clientExecutableURL = 
11-08 17:09:55.230  5816  5832 D bt_bte_conf:   serviceDescription  = 
11-08 17:09:55.230  5816  5832 D bt_bte_conf:   documentationURL    = 
11-08 17:09:55.230  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:55.233  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:55.235  5816  5832 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-08 17:09:55.235  5816  5829 D bt_stack_manager: event_start_up_stack finished
11-08 17:09:55.236  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-08 17:09:55.236  5816  5828 D BluetoothAdapterProperties: Setting state to 15
11-08 17:09:55.236  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-08 17:09:55.238  5816  5828 I BluetoothAdapterState: Entering BleOnState
11-08 17:09:55.239  5816  5837 I bt_vendor: low_power_mode_cb
11-08 17:09:55.241  5816  5828 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-08 17:09:55.241  5816  5828 D BluetoothAdapterProperties: Setting state to 11
,11-08 17:09:55.241  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-08 17:09:55.246  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
,11-08 17:09:55.252   931   931 D BluetoothHeadset: Proxy object connected
11-08 17:09:55.252   931   931 D BluetoothHeadset: Proxy object connected
11-08 17:09:55.253  5816  5816 D HeadsetService: Received start request. Starting profile...
11-08 17:09:55.253  5716  5727 D BluetoothHeadset: Proxy object connected
11-08 17:09:55.256  5816  5816 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-08 17:09:55.256  5816  5816 D HeadsetStateMachine: make
11-08 17:09:55.256  3132  3374 D BluetoothHeadset: Proxy object connected
11-08 17:09:55.257   931   931 D BluetoothHeadset: Proxy object connected
11-08 17:09:55.257  3762  3791 D BluetoothHeadset: Proxy object connected
11-08 17:09:55.258  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:55.261  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:55.261  3132  3132 D HeadsetProfile: Bluetooth service connected
,11-08 17:09:55.261  5716  5716 D HeadsetProfile: Bluetooth service connected
,11-08 17:09:55.265  5816  5828 I BluetoothAdapterState: Entering PendingCommandState
11-08 17:09:55.268  5816  5816 D HeadsetStateMachine: max_hf_connections = 1
11-08 17:09:55.268  5816  5816 I bt_bluedroid: get_profile_interface handsfree
11-08 17:09:55.268  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-08 17:09:55.269  5816  5832 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-08 17:09:55.271  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:09:55.272  5816  5816 D A2dpService: Received start request. Starting profile...
11-08 17:09:55.273  5816  5816 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-08 17:09:55.273  5816  5816 I bt_bluedroid: get_profile_interface avrcp
,11-08 17:09:55.277   931  2952 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-08 17:09:55.278   931  2952 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-08 17:09:55.278   931  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:09:55.281  5816  5816 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-08 17:09:55.281  5816  5816 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-08 17:09:55.281  5816  5816 D A2dpStateMachine: make
11-08 17:09:55.282  5816  5816 I bt_bluedroid: get_profile_interface a2dp
11-08 17:09:55.283  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-08 17:09:55.285  5816  5847 D A2dpStateMachine: Enter Disconnected: -2
,11-08 17:09:55.285  5816  5816 I BluetoothHidServiceJni: classInitNative: succeeds
11-08 17:09:55.286  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:09:55.287  5816  5816 D HidService: Received start request. Starting profile...
11-08 17:09:55.287  5816  5816 I bt_bluedroid: get_profile_interface hidhost
11-08 17:09:55.287  5816  5816 D HidService: setHidService(): set to: null
11-08 17:09:55.287  5816  5832 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f5e56d
11-08 17:09:55.288  5816  5832 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-08 17:09:55.287   931  2952 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
11-08 17:09:55.289  5816  5816 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-08 17:09:55.290  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
,11-08 17:09:55.291  5816  5816 D HealthService: Received start request. Starting profile...
11-08 17:09:55.293  5816  5816 I bt_bluedroid: get_profile_interface health
11-08 17:09:55.293  5816  5816 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-08 17:09:55.294  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:09:55.295  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
11-08 17:09:55.295  5816  5816 D PanService: Received start request. Starting profile...
,11-08 17:09:55.295  5816  5816 D BluetoothPanServiceJni: initializeNative(L110): pan
11-08 17:09:55.295  5816  5816 I bt_bluedroid: get_profile_interface pan
11-08 17:09:55.296  5816  5832 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-08 17:09:55.299  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
,11-08 17:09:55.299  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-08 17:09:55.299  5816  5816 D BluetoothMapService: Received start request. Starting profile...
11-08 17:09:55.299  5816  5816 D BluetoothMapService: start()
11-08 17:09:55.301  5816  5816 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-08 17:09:55.302  5816  5816 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-08 17:09:55.302  5816  5816 D BluetoothMapAppObserver: createReceiver()
11-08 17:09:55.303  5816  5816 D BluetoothMapAppObserver: initObservers()
11-08 17:09:55.303  5816  5816 D BluetoothMapAppObserver: getEnabledAccountItems()
11-08 17:09:55.309  5816  5816 V SapService: SapBinder()
,11-08 17:09:55.309  5816  5816 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
,11-08 17:09:55.309  5816  5816 D SapService: Received start request. Starting profile...
,11-08 17:09:55.310  5816  5816 V SapService: start()
11-08 17:09:55.312  5816  5816 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:55.312  5816  5816 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:55.312  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:55.312  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
,11-08 17:09:55.312  5816  5816 V BluetoothAdapterState: isTurningOff()=false
,11-08 17:09:55.312  5816  5816 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:55.313  5816  5845 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isTurningOn()=true
,11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:55.313  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:55.314  5816  5816 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:55.314  5816  5816 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:55.314  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:55.314  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:55.315  5816  5816 V BluetoothAdapterState: isTurningOff()=false
11-08 17:09:55.315  5816  5816 V BluetoothAdapterState: isTurningOn()=true
11-08 17:09:55.315  5816  5816 V BluetoothAdapterState: isBleTurningOn()=false
11-08 17:09:55.315  5816  5816 V BluetoothAdapterState: isBleTurningOff()=false
11-08 17:09:55.315  5816  5828 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-08 17:09:55.315  5816  5828 D BluetoothAdapterProperties: ScanMode =  20
11-08 17:09:55.315  5816  5828 D BluetoothAdapterProperties: State =  11
11-08 17:09:55.316  5816  5828 D BluetoothAdapterProperties: Setting state to 12
11-08 17:09:55.316  5816  5828 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-08 17:09:55.316  3132  3978 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:55.317  5816  5828 I BluetoothAdapterState: Entering OnState
11-08 17:09:55.317  5716  5727 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-08 17:09:55.319  5816  5832 D BluetoothAdapterProperties: Scan Mode:21
,11-08 17:09:55.319  5816  5832 D BluetoothAdapterProperties: Discoverable Timeout:120
11-08 17:09:55.319  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-08 17:09:55.321  3762  3981 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:55.322   931  2952 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-08 17:09:55.322  5716  5726 D BluetoothPan: onBluetoothStateChange on: true
11-08 17:09:55.323  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:55.323  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:55.323  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:55.323  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:55.323  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:55.323  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:55.323  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:55.323  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:55.324  5716  5727 D BluetoothMap: onBluetoothStateChange: up=true
11-08 17:09:55.325  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:55.326  5716  5726 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 17:09:55.328  3132  3374 D BluetoothMap: onBluetoothStateChange: up=true
11-08 17:09:55.328  5712  5712 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
11-08 17:09:55.329  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:55.329  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:55.329  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:55.329  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:55.329  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:55.329  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:55.329  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:55.329  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:55.329   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:55.329  3132  3132 D BluetoothMap: Proxy object connected
,11-08 17:09:55.329  3132  3132 D MapProfile: Bluetooth service connected
11-08 17:09:55.329  3132  3132 D BluetoothMap: getConnectedDevices()
11-08 17:09:55.329  3132  3146 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 17:09:55.329  5716  5716 D BluetoothA2dp: Proxy object connected
11-08 17:09:55.330  5816  5816 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-08 17:09:55.330  5816  5816 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-08 17:09:55.331  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:55.332  3132  3132 D BluetoothA2dp: Proxy object connected
11-08 17:09:55.332  3132  3374 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-08 17:09:55.332  5716  5716 D BluetoothPan: BluetoothPAN Proxy object connected
,11-08 17:09:55.332  5716  5716 D PanProfile: Bluetooth service connected
11-08 17:09:55.332  5716  5716 D BluetoothMap: Proxy object connected
11-08 17:09:55.332  5716  5716 D MapProfile: Bluetooth service connected
11-08 17:09:55.332  5716  5716 D BluetoothMap: getConnectedDevices()
11-08 17:09:55.332  5816  5816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:09:55.334   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
11-08 17:09:55.335   931   931 D BluetoothA2dp: Proxy object connected
,11-08 17:09:55.336  3132  3978 D BluetoothPan: onBluetoothStateChange on: true
,11-08 17:09:55.336  5816  5816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:09:55.337  5816  5816 D ObexServerSockets: Succeed to create listening sockets 
11-08 17:09:55.338  5816  5816 D ObexServerSockets0: startAccept()
11-08 17:09:55.338  5816  5816 D ObexServerSockets0: prepareForNewConnect()
11-08 17:09:55.338  3132  3132 D BluetoothPan: BluetoothPAN Proxy object connected
11-08 17:09:55.338  3132  3132 D PanProfile: Bluetooth service connected
11-08 17:09:55.339  3132  3147 D BluetoothPbap: onBluetoothStateChange: up=true
,11-08 17:09:55.340  5816  5816 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-08 17:09:55.340  5716  5727 D BluetoothPbap: onBluetoothStateChange: up=true
11-08 17:09:55.340  5816  5816 D BluetoothSdpJni: SDP Create record success - handle: 0
11-08 17:09:55.341  5816  5855 D ObexServerSockets0: Accepting socket connection...
11-08 17:09:55.341  5816  5856 D ObexServerSockets0: Accepting socket connection...
,11-08 17:09:55.343  3132  3132 D BluetoothInputDevice: Proxy object connected
11-08 17:09:55.343   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:55.343  3132  3132 D HidProfile: Bluetooth service connected
,11-08 17:09:55.343  5716  5852 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:55.343   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
11-08 17:09:55.344  5716  5716 D BluetoothInputDevice: Proxy object connected
11-08 17:09:55.344  5716  5716 D HidProfile: Bluetooth service connected
,11-08 17:09:55.344   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
11-08 17:09:55.344   931   931 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-08 17:09:55.345  5816  5816 D BluetoothMapService: onReceive
11-08 17:09:55.345  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-08 17:09:55.345  5816  5816 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-08 17:09:55.345  5816  5816 D BluetoothMapService: STATE_ON
11-08 17:09:55.347  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:55.348  5816  5857 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:09:55.349  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:55.349  5816  5857 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-08 17:09:55.349  5816  5857 D BluetoothSdpJni: SDP Create record success - handle: 1
11-08 17:09:55.352  5716  5716 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-08 17:09:55.358  3592  3592 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-08 17:09:55.358  5716  5716 D DockEventReceiver: finishStartingService: stopping service
,11-08 17:09:55.364  3132  3132 D BluetoothPbap: Proxy object connected
,11-08 17:09:55.364  3132  3132 D PbapServerProfile: Bluetooth service connected
,11-08 17:09:55.366  5716  5716 D BluetoothPbap: Proxy object connected
,11-08 17:09:55.366  5716  5716 D PbapServerProfile: Bluetooth service connected
,11-08 17:09:55.370  5816  5816 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-08 17:09:55.370  5816  5816 D ObexServerSockets0: prepareForNewConnect()
11-08 17:09:55.372  5816  5861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:09:55.385  5816  5865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:09:55.386  5816  5865 I BtOppRfcommListener: Accept thread started.
,11-08 17:09:55.757  5712  5712 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-08 17:09:55.794  5712  5712 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-08 17:09:55.795  5712  5712 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-08 17:09:55.805   931  2952 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-08 17:09:55.806   931  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-08 17:09:55.806   931  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-08 17:09:55.807  5609  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:55.807  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:55.807  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:55.807  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:55.807  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:55.807  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:55.807  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:55.807  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:55.812  5609  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:55.814  5609  5657 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-08 17:09:55.816   931  3840 D WifiService: setWifiEnabled: false pid=5609, uid=10077
11-08 17:09:55.816   931  3840 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:09:55.819  5609  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:55.821   931  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:09:55.831   509   925 D CommandListener: Setting iface cfg
,11-08 17:09:55.836   931  2952 D WifiStateMachine: Start Dhcp Watchdog 2
,11-08 17:09:55.841   931  5870 D DhcpClient: Receive thread started
,11-08 17:09:55.845   931  2952 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{1}, ntable=[]
,11-08 17:09:55.845   931  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-08 17:09:55.845   931  2954 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
11-08 17:09:55.845   931  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 17:09:55.845   931  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:09:55.854   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-08 17:09:55.857   931  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED
,11-08 17:09:55.857   931  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 0
,11-08 17:09:55.861   931   931 D RttService: SCAN_AVAILABLE : 1
,11-08 17:09:55.861   931  3061 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 17:09:55.863   931  2954 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-08 17:09:55.863   931  2954 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-08 17:09:55.864   931  5870 D DhcpClient: Receive thread stopped
11-08 17:09:55.865   931  2952 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-08 17:09:55.868   931  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-08 17:09:55.869   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-08 17:09:55.871   931  2952 D DhcpClient: doQuit
11-08 17:09:55.872   931  2952 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-08 17:09:55.872   931  5869 D DhcpClient: onQuitting
11-08 17:09:55.872  5712  5712 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-08 17:09:55.878  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:55.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:55.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:55.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:09:55.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:55.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:55.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:55.878  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:55.880  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:55.883  5712  5712 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-08 17:09:55.886  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:55.886  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:55.886  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:55.886  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:09:55.886  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:55.886  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:55.886  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:55.886  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-08 17:09:55.886  5712  5712 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-08 17:09:55.888  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:55.898  5712  5712 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-08 17:09:55.908  5712  5712 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-08 17:09:56.011   931  2952 D wifi    : In wifi stop Hal
,11-08 17:09:56.011   931  2952 D wifi    : halHandle = 0x7f7f584080, mVM = 0x7f9bc0d140, mCls = 0x17c2
11-08 17:09:56.012   931  5711 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-08 17:09:56.012   931  5711 D WifiHAL : Got a signal to exit!!!
,11-08 17:09:56.012   931  5711 I WifiHAL : Exit wifi_event_loop
,11-08 17:09:56.014   931  2952 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-08 17:09:56.014   931  2952 E WifiHAL : Event processing terminated
11-08 17:09:56.017   931  2952 D wifi    : In wifi cleaned up handler
11-08 17:09:56.017   931  2952 I WifiHAL : Internal cleanup completed
,11-08 17:09:56.018  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:56.011  4521  4521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 17:09:56.021  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:56.024  3936  4222 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-08 17:09:56.049   931  5711 D wifi    : set interface wlan0 flags (DOWN)
,11-08 17:09:56.049   931  2952 D WifiNative-HAL: HAL event thread stopped successfully
,11-08 17:09:56.253   931   948 D Tethering: InitialState.processMessage what=4
,11-08 17:09:56.256   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-08 17:09:56.320  5609  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:56.320  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:56.320  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:56.320  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-08 17:09:56.320  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:56.320  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:56.320  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:56.320  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:56.322  5609  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:56.325   931  3802 D WifiService: setWifiEnabled: true pid=5609, uid=10077
11-08 17:09:56.325   931  3802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:09:56.327  5609  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:56.332   509   925 D SoftapController: Softap fwReload - Ok
,11-08 17:09:56.337   509   925 D CommandListener: Setting iface cfg
,11-08 17:09:56.339   509   925 D CommandListener: Trying to bring down wlan0
11-08 17:09:56.339   509   925 D CommandListener: Clearing all IP addresses on wlan0
,11-08 17:09:56.342   931  2952 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-08 17:09:56.676   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:09:56.832   931  3202 D WifiService: setWifiEnabled: true pid=5609, uid=10077
,11-08 17:09:56.832   931  3202 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:09:56.936   931  2952 D wifi    : set interface wlan0 flags (UP)
,11-08 17:09:56.936   931  2952 I WifiHAL : Initializing wifi
,11-08 17:09:56.936   931  2952 I WifiHAL : Creating socket
,11-08 17:09:56.943   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-08 17:09:56.946   931  2952 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-08 17:09:56.946   931  2952 D wifi    : Did set static halHandle = 0x7f7f584080
11-08 17:09:56.946   931  2952 D wifi    : halHandle = 0x7f7f584080, mVM = 0x7f9bc0d140, mCls = 0x101562
,11-08 17:09:56.946   931  2952 D wifi    : array field set
11-08 17:09:56.947   931  2952 I WifiNative-HAL: interface[0] = wlan0
,11-08 17:09:56.949   931  5873 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547597336704
11-08 17:09:56.949   931  5873 D wifi    : waitForHalEvents called, vm = 0x7f9bc0d140, obj = 0x101562, env = 0x7f7fa99700
,11-08 17:09:57.007  5874  5874 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-08 17:09:57.050   931  2952 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-08 17:09:57.051   931  2952 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-08 17:09:57.059  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:57.061  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-08 17:09:57.081  5874  5874 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-08 17:09:57.140  5874  5874 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-08 17:09:57.140  5874  5874 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-08 17:09:57.335   931  3802 D WifiService: setWifiEnabled: true pid=5609, uid=10077
,11-08 17:09:57.335   931  3802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:09:57.680   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:09:57.839   931  3425 D WifiService: setWifiEnabled: true pid=5609, uid=10077
,11-08 17:09:57.839   931  3425 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-08 17:09:58.073   931  2952 D WifiConfigStore: Loading config and enabling all networks 
,11-08 17:09:58.077  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:58.077  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:58.077  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:58.077  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:58.077  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:58.077  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:58.077  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:58.077  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:58.081  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:58.089  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:58.089  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:58.089  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:58.089  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:58.089  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:58.089  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:58.089  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:58.089  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:58.094  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:58.117   931  2952 D WifiConfigStore: loaded 0 passpoint configs
,11-08 17:09:58.118   931  2952 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-08 17:09:58.119   931  2952 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-08 17:09:58.120   931  2952 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-08 17:09:58.120   931  2952 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-08 17:09:58.121   931  2952 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-08 17:09:58.122   931  2952 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-08 17:09:58.123   931  2952 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-08 17:09:58.123   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-08 17:09:58.123   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-08 17:09:58.123   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-08 17:09:58.123   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-08 17:09:58.123   931  2952 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-08 17:09:58.142   931  2952 D WifiNative-HAL: Setting external_sim to 1
,11-08 17:09:58.142  4521  4521 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-08 17:09:58.142   931  2952 D wifi    : setting dfs flag to true, 0x7f84afd000
11-08 17:09:58.143   931  2952 D WifiStateMachine: Setting OUI to DA-A1-19
11-08 17:09:58.143   931  2952 D wifi    : setting scan oui 0x7f84afd000
11-08 17:09:58.143   931  2952 D WifiHAL : Sending mac address OUI
,11-08 17:09:58.148   931  2952 E native  : do suspend false
,11-08 17:09:58.155   931  2952 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-08 17:09:58.155   509   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-08 17:09:58.156   931   931 D RttService: SCAN_AVAILABLE : 3
11-08 17:09:58.156   931  3061 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-08 17:09:58.156   509   925 D CommandListener: Setting iface cfg
,11-08 17:09:58.160   931  2951 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '137 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 137 Failed to set address (No such device)'
,11-08 17:09:58.160   931  2951 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-08 17:09:58.166   931  2951 D WifiNative-HAL: p2pGetDeviceAddress
,11-08 17:09:58.171   931  2951 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-08 17:09:58.171   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=120287 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-08 17:09:58.349  5609  5670 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:09:58.349  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:58.349  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:58.349  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:58.349  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:58.349  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:58.349  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:58.349  5609  5670 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:58.355  5609  5670 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-08 17:09:58.357  5609  5657 D BluetoothAdapter: enable(): BT is already enabled..!
,11-08 17:09:58.358   931  3837 D WifiService: setWifiEnabled: true pid=5609, uid=10077
,11-08 17:09:58.359   931  3837 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-08 17:09:58.359  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-08 17:09:58.360  5609  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 17:09:58.360  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 17:09:58.360  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-08 17:09:58.360  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 17:09:58.360  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d97748 removed from the list
11-08 17:09:58.360  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 17:09:58.360  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f9fe9e1 removed from the list
,11-08 17:09:58.360  5609  5657 D io.jxcore.node.ConnectivityMonitor: stop
11-08 17:09:58.360  5609  5657 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-08 17:09:58.360  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 17:09:58.363  5609  5657 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-08 17:09:58.364  5609  5657 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,11-08 17:09:58.368  5609  5657 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-08 17:09:58.370  5609  5657 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-08 17:09:58.373  5609  5657 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-08 17:09:58.374  5609  5657 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-08 17:09:58.376  5609  5657 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,11-08 17:09:58.376  5609  5657 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-08 17:09:58.377  5609  5657 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-08 17:09:58.381  5609  5657 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-08 17:09:58.381  5609  5657 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ef95c95 Bundle[{}]
11-08 17:09:58.382  5609  5657 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-08 17:09:58.382  5609  5657 I io.jxcore.node.LifeCycleMonitor: start: OK
11-08 17:09:58.383  5609  5657 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-08 17:09:58.385  5609  5657 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-08 17:09:58.385  5609  5657 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-08 17:09:58.386  5609  5657 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-08 17:09:58.387  5609  5657 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-08 17:09:58.388  5609  5657 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,11-08 17:09:58.389  5609  5657 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-08 17:09:58.390  5609  5657 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,11-08 17:09:58.391  5609  5657 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-08 17:09:58.392  5609  5657 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-08 17:09:58.394  5609  5657 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-08 17:09:58.395  5609  5657 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-08 17:09:58.396  5609  5657 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-08 17:09:58.397  5609  5657 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-08 17:09:58.398  5609  5657 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-08 17:09:58.400  5609  5657 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-08 17:09:58.401  5609  5657 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-08 17:09:58.403  5609  5657 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-08 17:09:58.405  5609  5657 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
11-08 17:09:58.406  5609  5657 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-08 17:09:58.406  5609  5657 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-08 17:09:58.406  5609  5657 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 140)
11-08 17:09:58.407  5609  5657 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-08 17:09:58.407  5609  5657 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-08 17:09:58.407  5609  5657 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
,11-08 17:09:58.408  5609  5657 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-08 17:09:58.409  5609  5657 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-08 17:09:58.411  5609  5657 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-08 17:09:58.411  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-08 17:09:58.411  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e50431d added. We now have 3 listener(s)
11-08 17:09:58.413  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:09:58.413  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-08 17:09:58.413  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-08 17:09:58.413  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-08 17:09:58.413  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d9992 added. We now have 3 listener(s)
11-08 17:09:58.413  5609  5657 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-08 17:09:58.414  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-08 17:09:58.417  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:09:58.421  5609  5657 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-08 17:09:58.421  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:09:58.421  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:09:58.421  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:09:58.421  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:09:58.421  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-08 17:09:58.421  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-08 17:09:58.421  5609  5657 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-08 17:09:58.423  5609  5657 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-08 17:09:58.423  5609  5657 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-08 17:09:58.425  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:58.426  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-08 17:09:58.426  5609  5657 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-08 17:09:58.427  5609  5657 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-08 17:09:58.427  5609  5657 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-08 17:09:58.427  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-08 17:09:58.427  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:09:58.427  5609  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:09:58.427  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:09:58.427  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:09:58.428  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-08 17:09:58.429  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-08 17:09:58.429  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 17:09:58.429  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 17:09:58.429  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:09:58.429  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-08 17:09:58.429  5609  5876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 17:09:58.429  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-08 17:09:58.429  5609  5609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:09:58.429  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-08 17:09:58.430  5609  5876 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-08 17:09:58.433  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:09:58.434  5609  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:09:58.434  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-08 17:09:58.432  5853  5853 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32548]" dev="sockfs" ino=32548 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:09:58.432  5853  5853 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32548]" dev="sockfs" ino=32548 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-08 17:09:58.437  5609  5876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-08 17:09:58.439  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 17:09:58.440  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-08 17:09:58.440  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 17:09:58.443  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:58.443  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:09:58.443  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:09:58.443  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-08 17:09:58.443  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:09:58.443  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.444  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.444  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:58.444  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:58.445  5609  5657 D BluetoothAdapter: STATE_ON
,11-08 17:09:58.449  5816  5827 D BtGatt.GattService: registerClient() - UUID=f691b480-aa7e-4691-9ec7-ec9ee30d2121
,11-08 17:09:58.450  5816  5832 D BtGatt.GattService: onClientRegistered() - UUID=f691b480-aa7e-4691-9ec7-ec9ee30d2121, clientIf=5
,11-08 17:09:58.450  5609  5620 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-08 17:09:58.452  5816  5835 D BtGatt.AdvertiseManager: message : 0
,11-08 17:09:58.454  5816  5835 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:09:58.463  5816  5832 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-08 17:09:58.469  5816  5832 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-08 17:09:58.470  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:58.470  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.470  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 17:09:58.470  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.470  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.470  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.470  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.470  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.470  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-08 17:09:58.471  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:09:58.472  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:58.473  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:09:58.473  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.473  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:09:58.473  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:09:58.474  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:09:58.474  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-08 17:09:58.474  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-08 17:09:58.477  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-08 17:09:58.477  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:09:58.477  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:58.477  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:09:58.477  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:09:58.477  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:09:58.477  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-08 17:09:58.681   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:09:58.978  5609  5609 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-08 17:09:58.978  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 17:09:58.978  5609  5609 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 17:09:59.682   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:00.683   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:01.244  5874  5874 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-08 17:10:01.261  5874  5874 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:10:01.266  5874  5874 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:10:01.271  5874  5874 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:10:01.276  5874  5874 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-08 17:10:01.296   931  2952 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-08 17:10:01.298   931  2952 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-08 17:10:01.298   931  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:10:01.309   931  2952 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-08 17:10:01.344   931  2952 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-08 17:10:01.671  5874  5874 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-08 17:10:01.684   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-08 17:10:01.713  5874  5874 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-08 17:10:01.713  5874  5874 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-08 17:10:01.720   931  2952 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-08 17:10:01.720   931  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-08 17:10:01.721   931  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-08 17:10:01.735   931  2952 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-08 17:10:01.746   509   925 D CommandListener: Setting iface cfg
,11-08 17:10:01.750   931  2952 D WifiStateMachine: Start Dhcp Watchdog 3
,11-08 17:10:01.756   931  5881 D DhcpClient: Receive thread started
,11-08 17:10:01.761   931  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-08 17:10:01.761   931  2952 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-08 17:10:01.761   931  2954 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-08 17:10:01.842   931  2952 E native  : do suspend false
,11-08 17:10:01.855   931  5880 D DhcpClient: Broadcasting DHCPDISCOVER
,11-08 17:10:01.879   931  5881 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172717, domain null
,11-08 17:10:01.880   931  5880 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172717 seconds
,11-08 17:10:01.882   931  5880 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-08 17:10:01.896   931  5881 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-08 17:10:01.897   931  5880 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-08 17:10:01.899   509   925 D CommandListener: Setting iface cfg
,11-08 17:10:01.904   931  2952 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-08 17:10:01.907   931  5880 D DhcpClient: Scheduling renewal in 86399s
,11-08 17:10:01.917   931  2952 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-08 17:10:01.918   931  2952 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 17:10:01.919   931  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-08 17:10:01.920   931  2954 D ConnectivityService: Adding iface wlan0 to network 102
,11-08 17:10:01.924   931  2952 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-08 17:10:01.961   931  2954 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-08 17:10:01.962   931  2954 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-08 17:10:01.964   931  2954 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-08 17:10:01.966   931  2954 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-08 17:10:01.970   931  2954 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-08 17:10:01.976  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-08 17:10:01.976  5609  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-08 17:10:01.976  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-08 17:10:01.976  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-08 17:10:01.976  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-08 17:10:01.976  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-08 17:10:01.976  5609  5876 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:10:01.976  5609  5876 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 17:10:01.976  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 17:10:01.976  5609  5876 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-08 17:10:01.976  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 17:10:01.976  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-08 17:10:01.977  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 17:10:01.977  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-08 17:10:01.977  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 17:10:01.977  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:01.977  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.977  5609  5609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 17:10:01.977  5609  5609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 17:10:01.977  5609  5609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 17:10:01.978  5609  5657 D BluetoothAdapter: STATE_ON
11-08 17:10:01.978  5609  5657 D BluetoothLeScanner: could not find callback wrapper
11-08 17:10:01.978  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 17:10:01.978  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.978   931  2954 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-08 17:10:01.978  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:01.978  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 17:10:01.979  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.979  5816  5835 D BtGatt.AdvertiseManager: message : 1
11-08 17:10:01.980  5816  5835 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-08 17:10:01.983   931  2954 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-08 17:10:01.983   931  2954 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-08 17:10:01.983   931  2954 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-08 17:10:01.983   931  2954 D ConnectivityService:    accepting network in place of null
11-08 17:10:01.984   931  2954 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-08 17:10:01.984   931  2952 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-08 17:10:01.985   931  2952 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-08 17:10:01.988  5816  5832 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-08 17:10:01.988  5816  5832 D BtGatt.GattService: Client app is not null!
11-08 17:10:01.989  5816  5833 D BtGatt.GattService: unregisterClient() - clientIf=5
11-08 17:10:01.989  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 17:10:01.990  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.990  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:10:01.990  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.990  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.990  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.990  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-08 17:10:01.990  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:10:01.990  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.990  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.990  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 17:10:01.990  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.992  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.992  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:10:01.992  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.992  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.992  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.992  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.992  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.992  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 17:10:01.992  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-08 17:10:01.993  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 17:10:01.993  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.994  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.994  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:01.994  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: ,Thread[Thread-62,5,main], id: 62
,11-08 17:10:01.995  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-08 17:10:01.995  5609  5609 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-08 17:10:01.995  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:10:01.995  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-08 17:10:01.995  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:10:01.997  5609  5657 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-08 17:10:01.997  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 17:10:01.998  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 17:10:01.998  5609  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-08 17:10:01.998  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-08 17:10:01.998  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:10:01.998  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-08 17:10:02.002  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-08 17:10:02.002  5609  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:10:02.002  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-08 17:10:02.006  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 17:10:02.007  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-08 17:10:02.007  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-08 17:10:02.011  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.011  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-08 17:10:02.011  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 17:10:02.011  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-08 17:10:02.011   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-08 17:10:02.012  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 17:10:02.012  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.013  5609  5657 D BluetoothAdapter: STATE_ON
11-08 17:10:02.015  5816  5853 D BtGatt.GattService: registerClient() - UUID=236b6379-e931-4762-913e-a55246adc812
11-08 17:10:02.016  5816  5832 D BtGatt.GattService: onClientRegistered() - UUID=236b6379-e931-4762-913e-a55246adc812, clientIf=5
,11-08 17:10:02.016  5609  5648 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-08 17:10:02.017  5816  5827 D BtGatt.GattService: start scan with filters
11-08 17:10:02.020  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-08 17:10:02.020  5816  5836 D BtGatt.ScanManager: handling starting scan
11-08 17:10:02.020  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.020  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-08 17:10:02.021  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.021  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:02.021  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-08 17:10:02.021  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-08 17:10:02.021  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.022  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.022  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-08 17:10:02.022  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:02.023  5816  5836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72e99e
11-08 17:10:02.024  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.024  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-08 17:10:02.024  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.024  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.024  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-08 17:10:02.024  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.025  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 17:10:02.026  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:10:02.026  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.028  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.028  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:02.028  5816  5832 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-08 17:10:02.028  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:02.028  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:02.029  5816  5836 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-08 17:10:02.033   509   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-08 17:10:02.034  5816  5832 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-08 17:10:02.034  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:02.034  5816  5836 D BtGatt.ScanManager: Starting BLE batch scan
11-08 17:10:02.034  5816  5836 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-08 17:10:02.037   931  2954 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-08 17:10:02.037   931  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:10:02.037  3724  3864 W QCNEJ   : |CORE| network available: 102
,11-08 17:10:02.038   931  2954 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-08 17:10:02.042  3724  3864 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-08 17:10:02.043  3724  3864 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-08 17:10:02.043  3724  3864 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-08 17:10:02.045   931   948 D Tethering: MasterInitialState.processMessage what=3
11-08 17:10:02.048  5816  5832 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-08 17:10:02.048  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 17:10:02.050  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:10:02.050  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:10:02.050  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:10:02.050  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:10:02.050  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:10:02.050  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:10:02.050  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:10:02.050  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:10:02.053  3956  3956 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-08 17:10:02.053  5816  5832 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-08 17:10:02.053  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:02.053  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-08 17:10:02.054   931  5879 D NetlinkSocketObserver: NeighborEvent{elapsedMs=124169, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
11-08 17:10:02.055  4041  4041 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-08 17:10:02.057  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:10:02.057  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:10:02.057  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:10:02.057  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:10:02.057  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:10:02.057  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:10:02.057  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:10:02.057  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:10:02.060  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:10:02.061  4041  4041 D SystemUpdateService: onCreate
,11-08 17:10:02.065  4041  4041 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-08 17:10:02.065  5609  5609 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-08 17:10:02.065  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-08 17:10:02.065  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-08 17:10:02.065  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-08 17:10:02.065  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-08 17:10:02.065  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-08 17:10:02.065  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-08 17:10:02.065  5609  5609 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-08 17:10:02.067  5609  5609 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-08 17:10:02.074  4041  4041 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-08 17:10:02.080  4041  5891 I SystemUpdateService: active receiver: enabled
,11-08 17:10:02.081  4041  4254 I iu.UploadsManager: num queued entries: 0
,11-08 17:10:02.081  4041  4254 I iu.UploadsManager: num updated entries: 0
11-08 17:10:02.082  4041  4254 I iu.SyncManager: NEXT; no task
,11-08 17:10:02.085  4041  4041 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-08 17:10:02.086  4041  4041 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-08 17:10:02.088  5410  5410 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-08 17:10:02.091  5410  5410 D SprintDMHelper: simOperator: 
11-08 17:10:02.091  5410  5410 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-08 17:10:02.101  4041  5891 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-08 17:10:02.118  4041  5891 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-08 17:10:02.118  4041  5891 I SystemUpdateService: now status is 0 (complete)
11-08 17:10:02.118  4041  5891 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-08 17:10:02.118  4041  5891 I SystemUpdateService: file has been verified
11-08 17:10:02.118  4041  5891 I SystemUpdateService: OTA package size = 21989297
,11-08 17:10:02.122  4041  5891 I SystemUpdateService: showing system update notification
,11-08 17:10:02.130   931   931 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-08 17:10:02.131  4041  4041 D SystemUpdateService: onDestroy
,11-08 17:10:02.228   931  5878 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-08 17:10:02.407   931  5878 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 08 Nov 2016 16:10:02 GMT], X-Android-Received-Millis=[1478621402405], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478621402276]}
,11-08 17:10:02.409   931  2954 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-08 17:10:02.410   931  2954 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-08 17:10:02.410   931  2954 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-08 17:10:02.414   931  2954 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-08 17:10:02.526  5609  5609 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-08 17:10:02.526  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 17:10:02.526  5609  5609 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 17:10:02.584  5816  5816 D BtGatt.ScanManager: awakened up at time 124700
11-08 17:10:02.586  5816  5836 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 17:10:02.599  5816  5832 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-08 17:10:02.599  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:02.599  5816  5832 D BtGatt.GattService: current time is 124715038249
11-08 17:10:02.599  5816  5832 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-08 17:10:02.601  5816  5832 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-08 17:10:02.604  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
,11-08 17:10:02.604  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-08 17:10:02.604  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=E3:EC:A5:91:D5:74, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=124215385124}
,11-08 17:10:03.038   931  2954 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-08 17:10:05.030  5609  5657 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
11-08 17:10:05.031  5609  5657 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-08 17:10:05.031  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,11-08 17:10:05.032  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-08 17:10:05.032  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-08 17:10:05.035  5609  5657 D BluetoothAdapter: STATE_ON
,11-08 17:10:05.037  5816  5833 D BtGatt.GattService: stopScan() - queue size =1
,11-08 17:10:05.046  5816  5853 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 17:10:05.049  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-08 17:10:05.050  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:05.050  5816  5816 D BtGatt.ScanManager: awakened up at time 127165
11-08 17:10:05.050  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-08 17:10:05.050  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-08 17:10:05.050  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.050  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-08 17:10:05.050  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-08 17:10:05.051  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-08 17:10:05.051  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-08 17:10:05.051  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.053  5609  5657 D BluetoothAdapter: STATE_ON
,11-08 17:10:05.056  5816  5832 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-08 17:10:05.056  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 17:10:05.056  5816  5836 D BtGatt.ScanManager: stopping BLe Batch
,11-08 17:10:05.059  5816  5827 D BtGatt.GattService: registerClient() - UUID=32eef2e1-a8e0-441f-9e39-5a025c4dc148
11-08 17:10:05.059  5816  5832 D BtGatt.GattService: onClientRegistered() - UUID=32eef2e1-a8e0-441f-9e39-5a025c4dc148, clientIf=5
11-08 17:10:05.060  5609  5648 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-08 17:10:05.060  5816  5853 D BtGatt.GattService: start scan with filters
,11-08 17:10:05.065  5816  5832 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-08 17:10:05.066  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:05.066  5816  5836 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 17:10:05.067  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-08 17:10:05.067  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:05.067  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-08 17:10:05.067  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.068  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:05.068  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-08 17:10:05.068  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-08 17:10:05.068  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.068  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.068  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,11-08 17:10:05.069  5609  5657 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-08 17:10:05.069  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-08 17:10:05.069  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-08 17:10:05.070  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-08 17:10:05.071  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-08 17:10:05.071  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-08 17:10:05.071  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-08 17:10:05.072  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-08 17:10:05.072  5609  5609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-08 17:10:05.072  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-08 17:10:05.072  5609  5899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-08 17:10:05.073  5609  5899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-08 17:10:05.075  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-08 17:10:05.072  5854  5854 W Binder_5: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[30503]" dev="sockfs" ino=30503 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:10:05.075  5609  5657 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-08 17:10:05.072  5854  5854 W Binder_5: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[30503]" dev="sockfs" ino=30503 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-08 17:10:05.077  5609  5899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-08 17:10:05.083  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.083  5816  5832 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-08 17:10:05.083  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.083  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:05.083  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-08 17:10:05.083  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-08 17:10:05.083  5816  5832 D BtGatt.GattService: current time is 127199297658
11-08 17:10:05.083  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
,11-08 17:10:05.083  5816  5832 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -84, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -84, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -87, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
11-08 17:10:05.084  5609  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-08 17:10:05.084  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.084  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.084  5816  5832 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-08 17:10:05.084  5816  5832 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-08 17:10:05.085  5816  5832 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-08 17:10:05.085  5816  5832 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
11-08 17:10:05.085  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.085  5816  5836 D BtGatt.ScanManager: handling starting scan
11-08 17:10:05.085  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.086  5609  5657 D BluetoothAdapter: STATE_ON
,11-08 17:10:05.091  5816  5833 D BtGatt.GattService: registerClient() - UUID=9b2c3717-6f87-4dd4-af41-29a5a45d42fd
,11-08 17:10:05.092  5816  5832 D BtGatt.GattService: onClientRegistered() - UUID=9b2c3717-6f87-4dd4-af41-29a5a45d42fd, clientIf=6
11-08 17:10:05.092  5609  5619 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-08 17:10:05.093  5816  5832 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-08 17:10:05.093  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:05.094  5816  5835 D BtGatt.AdvertiseManager: message : 0
,11-08 17:10:05.094  5816  5836 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-08 17:10:05.097  5816  5835 D BtGatt.AdvertiseManager: starting multi advertising
,11-08 17:10:05.100  5816  5832 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-08 17:10:05.101  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:05.101  5816  5836 D BtGatt.ScanManager: Starting BLE batch scan
11-08 17:10:05.101  5816  5836 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-08 17:10:05.112  5816  5832 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-08 17:10:05.121  5816  5832 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-08 17:10:05.121  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 17:10:05.126  5816  5832 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
11-08 17:10:05.138  5816  5832 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-08 17:10:05.138  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-08 17:10:05.138  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:05.138  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.138  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-08 17:10:05.138  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.138  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.138  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.138  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.138  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.139  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.139  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.139  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.139  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-08 17:10:05.139  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-08 17:10:05.139  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-08 17:10:05.140  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-08 17:10:05.140  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.142  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.142  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.142  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:05.143  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-08 17:10:05.143  5609  5609 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,,5,main], id: 1
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-08 17:10:05.143  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-08 17:10:05.143  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-08 17:10:05.146  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-08 17:10:05.146  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-08 17:10:05.146  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-08 17:10:05.146  5609  5609 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-08 17:10:05.146  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-08 17:10:05.146  5609  5609 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-08 17:10:05.146  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-08 17:10:05.647  5609  5609 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-08 17:10:05.648  5609  5609 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-08 17:10:05.648  5609  5609 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-08 17:10:06.367   931  2952 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 10 -> obsolete
,11-08 17:10:06.685   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:07.141   931  2952 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 10 -> obsolete
,11-08 17:10:07.686   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:08.146  5609  5657 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-08 17:10:08.147  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-08 17:10:08.147  5609  5657 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-08 17:10:08.147  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-08 17:10:08.147  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-08 17:10:08.148  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,11-08 17:10:08.148  5609  5899 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-08 17:10:08.148  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-08 17:10:08.148  5609  5899 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-08 17:10:08.148  5609  5657 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-08 17:10:08.148  5609  5899 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-08 17:10:08.148  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-08 17:10:08.149  5609  5609 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-08 17:10:08.149  5609  5657 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e50431d removed from the list
11-08 17:10:08.149  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-08 17:10:08.149  5609  5609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-08 17:10:08.149  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-08 17:10:08.149  5609  5609 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-08 17:10:08.149  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-08 17:10:08.149  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-08 17:10:08.152  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.152  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.152  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-08 17:10:08.154  5609  5657 D BluetoothAdapter: STATE_ON
11-08 17:10:08.155  5816  5827 D BtGatt.GattService: stopScan() - queue size =1
11-08 17:10:08.157  5816  5853 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-08 17:10:08.159  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-08 17:10:08.159  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.159  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-08 17:10:08.159  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.160  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.160  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-08 17:10:08.160  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-08 17:10:08.160  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.160  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.160  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-08 17:10:08.161  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:08.165  5816  5816 D BtGatt.ScanManager: awakened up at time 130281
11-08 17:10:08.166  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.166  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:10:08.166  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.166  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.166  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.166  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:08.166  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-08 17:10:08.166  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.168  5816  5835 D BtGatt.AdvertiseManager: message : 1
11-08 17:10:08.169  5816  5835 D BtGatt.AdvertiseManager: stop advertise for client 6
11-08 17:10:08.170  5816  5832 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-08 17:10:08.170  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:08.171  5816  5836 D BtGatt.ScanManager: stopping BLe Batch
,11-08 17:10:08.177  5816  5832 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-08 17:10:08.177  5816  5832 D BtGatt.GattService: Client app is not null!
,11-08 17:10:08.178  5816  5827 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-08 17:10:08.179  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-08 17:10:08.179  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.179  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-08 17:10:08.179  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.180  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.180  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.180  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-08 17:10:08.180  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-08 17:10:08.180  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.180  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.180  5609  5657 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-08 17:10:08.180  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:08.182  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:08.182  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:10:08.182  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.182  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.183  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.183  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.183  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.183  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-08 17:10:08.183  5609  5657 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-08 17:10:08.184  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-08 17:10:08.185  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-08 17:10:08.186  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.186  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.186  5609  5657 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-08 17:10:08.187  5609  5657 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20d9992 removed from the list
,11-08 17:10:08.187  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:10:08.187  5609  5657 D io.jxcore.node.ConnectivityMonitor: stop
11-08 17:10:08.187  5609  5609 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-08 17:10:08.187  5609  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-08 17:10:08.187  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-08 17:10:08.187  5609  5609 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-08 17:10:08.188  5816  5832 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-08 17:10:08.189  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:08.189  5816  5836 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-08 17:10:08.189  5609  5657 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
,11-08 17:10:08.189  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-08 17:10:08.190  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-08 17:10:08.190  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-08 17:10:08.190  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-08 17:10:08.190  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-08 17:10:08.190  5609  5657 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-08 17:10:08.190  5609  5657 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-08 17:10:08.192  5609  5657 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-08 17:10:08.193  5609  5657 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,11-08 17:10:08.193  5609  5657 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-08 17:10:08.195  5609  5657 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-08 17:10:08.195  5609  5657 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-08 17:10:08.196  5609  5657 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-08 17:10:08.196  5609  5657 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-08 17:10:08.208  5816  5832 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-08 17:10:08.208  5816  5832 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-08 17:10:08.209  5816  5832 D BtGatt.GattService: current time is 130324729281
11-08 17:10:08.209  5816  5832 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -84, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -88, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -83, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-08 17:10:08.209  5816  5832 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-08 17:10:08.209  5816  5832 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-08 17:10:08.209  5816  5832 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-08 17:10:08.210  5816  5832 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-08 17:10:08.687   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:08.688  5609  5609 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-08 17:10:09.688   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:09.989   931  2954 D ConnectivityService: handlePromptUnvalidated 102
,11-08 17:10:10.201  5609  5657 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-08 17:10:10.344  5609  5901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 17:10:10.344  5609  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:10:10.689   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:11.168  5609  5901 W !!      : call onHalfStreamCopied
,11-08 17:10:11.169  5609  5901 I testCopyDataAndClose: closing input stream
,11-08 17:10:11.690   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 154, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-08 17:10:11.944  5609  5901 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 17:10:13.174   931  2952 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-08 17:10:13.782  3654  3820 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-08 17:10:13.783  3654  3820 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-08 17:10:13.814  3592  3592 I ConfigService: onCreate
,11-08 17:10:16.367  5609  5657 I StreamCopyingThreadTest: Starting test: testRun
,11-08 17:10:16.370  5609  5903 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:10:16.370  5609  5903 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:10:18.856  3592  3592 I ConfigService: onDestroy
,11-08 17:10:21.377  5609  5904 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-08 17:10:21.380  5609  5657 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-08 17:10:21.518  5609  5905 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 17:10:21.518  5609  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:10:21.693   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:22.695   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-08 17:10:23.148  5609  5905 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-08 17:10:23.696   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:24.697   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:25.699   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:26.700   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-08 17:10:27.525  5609  5657 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-08 17:10:27.527  5609  5906 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:10:27.527  5609  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:10:27.528  5609  5906 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:10:27.528  5609  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-08 17:10:27.528  5609  5906 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-08 17:10:27.528  5609  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:10:27.528  5609  5906 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-08 17:10:27.528  5609  5906 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-08 17:10:27.528  5609  5906 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-08 17:10:27.528  5609  5906 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-08 17:10:27.528  5609  5906 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-08 17:10:27.529  5609  5906 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:10:27.529  5609  5906 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-08 17:10:27.530  5609  5657 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-08 17:10:27.530  5609  5657 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-08 17:10:27.531  5609  5657 I StreamCopyingThreadTest: Starting test: testRunWithException
11-08 17:10:27.533  5609  5907 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:10:27.533  5609  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-08 17:10:27.535  5609  5907 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 166, thread name: My test thread name): Test exception.
11-08 17:10:27.535  5609  5907 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 166, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:10:27.535  5609  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-08 17:10:27.535  5609  5907 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-08 17:10:27.536  5609  5907 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: My test thread name). Connection data: Peer properties: [null null].
11-08 17:10:27.536  5609  5907 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-08 17:10:27.538  5609  5657 E com.test.thalitest.ThaliTestRunner: testStart(io.jxcore.node.ConnectionHelperTest)
11-08 17:10:27.538  5609  5657 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
11-08 17:10:27.538  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:10:27.538  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testStart(ConnectionHelperTest.java:287)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at o,rg.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: testStop(io.jxcore.node.ConnectionHelperTest)
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:10:27.539  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 17:10:27.540  5609  5657 E com.test.thalitest.Tha,liTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testStop(ConnectionHelperTest.java:315)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: 
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 17:10:27.540  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: testDispose(io.jxcore.node.ConnectionHelperTest)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: DiscoveryManager should be running
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: DiscoveryManager should be running
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testDispose(ConnectionHelperTest.java:191)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:27.541  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: testIsRunning(io.jxcore.node.ConnectionHelperTest)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: ConnectionManager state is different than NOT_STARTED
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is not <NOT_STARTED>
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <NOT_STARTED>
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: ConnectionManager state is different than NOT_STARTED
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is not <NOT_STARTED>
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <NOT_STARTED>
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testIsRunning(ConnectionHelperTest.java:413)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:10:27.542  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:27.543  5609  5657 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-08 17:10:27.546  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG UnitTest_app: 'Running unit tests'
11-08 17:10:27.546  5609  5657 I jxcore-log: 
11-08 17:10:27.547  5609  5657 I jxcore-log: *Native tests were executed*
11-08 17:10:27.547  5609  5657 I jxcore-log: 
11-08 17:10:27.547  5609  5657 I jxcore-log: Total number of executed tests:  82
11-08 17:10:27.547  5609  5657 I jxcore-log: 
11-08 17:10:27.547  5609  5657 I jxcore-log: Number of passed tests:  76
11-08 17:10:27.547  5609  5657 I jxcore-log: 
11-08 17:10:27.547  5609  5657 I jxcore-log: Number of failed tests:  6
11-08 17:10:27.547  5609  5657 I jxcore-log: 
11-08 17:10:27.547  5609  5657 I jxcore-log: Number of ignored tests:  0
11-08 17:10:27.547  5609  5657 I jxcore-log: 
11-08 17:10:27.548  5609  5657 I jxcore-log: Total duration:  52754
11-08 17:10:27.548  5609  5657 I jxcore-log: 
11-08 17:10:27.548  5609  5657 I jxcore-log: Failed to execute UT.
11-08 17:10:27.548  5609  5657 I jxcore-log: 
11-08 17:10:27.549  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-08 17:10:27.549  5609  5657 I jxcore-log: 
11-08 17:10:27.550  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-08 17:10:27.550  5609  5657 I jxcore-log: 
11-08 17:10:27.553  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:10:27.553  5609  5657 I jxcore-log: 
11-08 17:10:27.554  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.554  5609  5657 I jxcore-log: 
11-08 17:10:27.555  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:10:27.555  5609  5657 I jxcore-log: 
11-08 17:10:27.555   931  5879 D NetlinkSocketObserver: NeighborEvent{elapsedMs=149670, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
11-08 17:10:27.555  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.555  5609  5657 I jxcore-log: 
11-08 17:10:27.556  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:10:27.556  5609  5657 I jxcore-log: 
11-08 17:10:27.556  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.556  5609  5657 I jxcore-log: 
11-08 17:10:27.556  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 17:10:27.556  5609  5657 I jxcore-log: 
11-08 17:10:27.557  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 17:10:27.557  5609  5657 I jxcore-log: 
11-08 17:10:27.557  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:10:27.557  5609  5657 I jxcore-log: 
11-08 17:10:27.557  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.557  5609  5657 I jxcore-log: 
11-08 17:10:27.558  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.558  5609  5657 I jxcore-log: 
11-08 17:10:27.558  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.558  5609  5657 I jxcore-log: 
11-08 17:10:27.558  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:10:27.558  5609  5657 I jxcore-log: 
11-08 17:10:27.558  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.558  5609  5657 I jxcore-log: 
11-08 17:10:27.558  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:10:27.558  5609  5657 I jxcore-log: 
11-08 17:10:27.559  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.559  5609  5657 I jxcore-log: 
11-08 17:10:27.559  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:10:27.559  5609  5657 I jxcore-log: 
11-08 17:10:27.559  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.559  5609  5657 I jxcore-log: 
11-08 17:10:27.559  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.559  5609  5657 I jxcore-log: 
11-08 17:10:27.559  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.559  5609  5657 I jxcore-log: 
11-08 17:10:27.560  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.560  5609  5657 I jxcore-log: 
11-08 17:10:27.560  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.560  5609  5657 I jxcore-log: 
11-08 17:10:27.560  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.560  5609  5657 I jxcore-log: 
11-08 17:10:27.560  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.560  5609  5657 I jxcore-log: 
11-08 17:10:27.561  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.561  5609  5657 I jxcore-log: 
11-08 17:10:27.561  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.561  5609  5657 I jxcore-log: 
11-08 17:10:27.561  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.561  5609  5657 I jxcore-log: 
11-08 17:10:27.561  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.561  5609  5657 I jxcore-log: 
11-08 17:10:27.561  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.561  5609  5657 I jxcore-log: 
11-08 17:10:27.563  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.563  5609  5657 I jxcore-log: 
11-08 17:10:27.563  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 17:10:27.563  5609  5657 I jxcore-log: 
11-08 17:10:27.563  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.563  5609  5657 I jxcore-log: 
11-08 17:10:27.564  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.564  5609  5657 I jxcore-log: 
11-08 17:10:27.564  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.564  5609  5657 I jxcore-log: 
11-08 17:10:27.564  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.564  5609  5657 I jxcore-log: 
11-08 17:10:27.564  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.564  5609  5657 I jxcore-log: 
11-08 17:10:27.564  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.564  5609  5657 I jxcore-log: 
11-08 17:10:27.564  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.564  5609  5657 I jxcore-log: 
11-08 17:10:27.565  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.565  5609  5657 I jxcore-log: 
11-08 17:10:27.565  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.565  5609  5657 I jxcore-log: 
11-08 17:10:27.565  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.565  5609  5657 I jxcore-log: 
11-08 17:10:27.565  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.565  5609  5657 I jxcore-log: 
11-08 17:10:27.565  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.565  5609  5657 I jxcore-log: 
11-08 17:10:27.566  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 17:10:27.566  5609  5657 I jxcore-log: 
11-08 17:10:27.566  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.566  5609  5657 I jxcore-log: 
,11-08 17:10:27.566  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.566  5609  5657 I jxcore-log: 
11-08 17:10:27.566  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.566  5609  5657 I jxcore-log: 
11-08 17:10:27.566  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.566  5609  5657 I jxcore-log: 
11-08 17:10:27.567  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.567  5609  5657 I jxcore-log: 
11-08 17:10:27.567  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.567  5609  5657 I jxcore-log: 
11-08 17:10:27.567  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:10:27.567  5609  5657 I jxcore-log: 
11-08 17:10:27.567  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.567  5609  5657 I jxcore-log: 
11-08 17:10:27.567  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:10:27.567  5609  5657 I jxcore-log: 
11-08 17:10:27.567  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.567  5609  5657 I jxcore-log: 
11-08 17:10:27.568  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-08 17:10:27.568  5609  5657 I jxcore-log: 
11-08 17:10:27.568  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.568  5609  5657 I jxcore-log: 
11-08 17:10:27.568  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.568  5609  5657 I jxcore-log: 
11-08 17:10:27.568  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.568  5609  5657 I jxcore-log: 
11-08 17:10:27.568  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.568  5609  5657 I jxcore-log: 
11-08 17:10:27.569  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.569  5609  5657 I jxcore-log: 
11-08 17:10:27.569  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.569  5609  5657 I jxcore-log: 
11-08 17:10:27.569  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.569  5609  5657 I jxcore-log: 
11-08 17:10:27.569  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-08 17:10:27.569  5609  5657 I jxcore-log: 
11-08 17:10:27.569  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.569  5609  5657 I jxcore-log: 
11-08 17:10:27.569  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-08 17:10:27.569  5609  5657 I jxcore-log: 
11-08 17:10:27.570  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:10:27.570  5609  5657 I jxcore-log: 
11-08 17:10:27.570  5609  5609 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-08 17:10:27.570  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.570  5609  5657 I jxcore-log: 
11-08 17:10:27.570  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:10:27.570  5609  5657 I jxcore-log: 
11-08 17:10:27.570  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.570  5609  5657 I jxcore-log: 
11-08 17:10:27.570  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-08 17:10:27.570  5609  5657 I jxcore-log: 
11-08 17:10:27.571  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-08 17:10:27.571  5609  5657 I jxcore-log: 
11-08 17:10:27.571  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-08 17:10:27.571  5609  5657 I jxcore-log: 
11-08 17:10:27.571  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-08 17:10:27.571  5609  5657 I jxcore-log: 
11-08 17:10:27.571  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-08 17:10:27.571  5609  5657 I jxcore-log: 
11-08 17:10:27.576  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-08 17:10:27.576  5609  5657 I jxcore-log: 
11-08 17:10:27.576  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - WARN testUtils: 'myNameCallback not set!'
11-08 17:10:27.576  5609  5657 I jxcore-log: 
11-08 17:10:27.577  5609  5657 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-08 17:10:27.578  5609  5657 I jxcore-log: 2016-11-08 16:10:27 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-08 17:10:27.578  5609  5657 I jxcore-log: 
,11-08 17:10:29.572  5609  5657 I jxcore-log: 2016-11-08 16:10:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-08 17:10:29.572  5609  5657 I jxcore-log: 
,11-08 17:10:29.674   931   951 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-08 17:10:29.675   942   942 W Binder_2: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33350]" dev="sockfs" ino=33350 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:29.684  3654  3654 I Keyboard.Facilitator: onFinishInput()
11-08 17:10:29.679   942   942 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33350]" dev="sockfs" ino=33350 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:29.702   931   951 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 17:10:29.702   931   951 I Adreno  : Build Date                       : 12/06/15
11-08 17:10:29.702   931   951 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 17:10:29.702   931   951 I Adreno  : Local Branch                     : mybranch17112971
11-08 17:10:29.702   931   951 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 17:10:29.702   931   951 I Adreno  : Remote Branch                    : NONE
11-08 17:10:29.702   931   951 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 17:10:29.731   383   765 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (186 us)
,11-08 17:10:29.887  5609  5657 I jxcore-log: 2016-11-08 16:10:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-08 17:10:29.887  5609  5657 I jxcore-log: 
,11-08 17:10:29.900  5609  5657 I jxcore-log: 2016-11-08 16:10:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-08 17:10:29.900  5609  5657 I jxcore-log: 
,11-08 17:10:30.376  5609  5609 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-08 17:10:30.376  5609  5609 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-08 17:10:30.408   931   951 I sensors : batch
,11-08 17:10:30.408   931   951 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-08 17:10:30.410  5609  5609 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ef95c95 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@32889b6, 16908290=android.view.AbsSavedState$1@32889b6}, android:focusedViewId=100}]}]
11-08 17:10:30.410  5609  5609 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-08 17:10:30.410  5609  5609 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-08 17:10:30.410  5609  5609 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
11-08 17:10:30.411   931   951 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,11-08 17:10:30.412   931   951 I sensors : activate
,11-08 17:10:30.412   931   949 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
11-08 17:10:30.412   383   383 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f98443c00
,11-08 17:10:30.413   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
11-08 17:10:30.415   931  2671 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-08 17:10:30.417   931  2671 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-08 17:10:30.615   509   925 D TetherController: Setting IP forward enable = 1
,11-08 17:10:30.699   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-08 17:10:30.700   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-08 17:10:30.701   931  3090 D SurfaceControl: Excessive delay in setPowerMode(): 288ms
,11-08 17:10:30.704   931   951 I DreamManagerService: Entering dreamland.
,11-08 17:10:30.705   931   951 I PowerManagerService: Dozing...
,11-08 17:10:30.705   931   946 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-08 17:10:30.719  3131  3131 W Binder_3: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[31526]" dev="sockfs" ino=31526 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:30.719  3131  3131 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[31526]" dev="sockfs" ino=31526 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:10:30.722   931  3802 I sensors : batch
11-08 17:10:30.722   931  3802 I sensors : activate
,11-08 17:10:30.726   931  2671 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-08 17:10:30.727   931  2671 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-08 17:10:30.729   514  3004 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-08 17:10:30.734   931  2952 E native  : do suspend false
,11-08 17:10:30.740   931  2952 D WifiConfigStore: No blacklist allowed without epno enabled
,11-08 17:10:30.746  3762  4762 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-08 17:10:30.746  3762  4762 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-08 17:10:30.746  3762  4762 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 17:10:30.746   527  1366 D         : oem-qmi: Connection accepted
11-08 17:10:30.746   527  1366 D         : oem-qmi: Waiting to accept connection
,11-08 17:10:30.748   931   931 I sensors : activate
,11-08 17:10:30.748   514  3002 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
11-08 17:10:30.749  3762  4762 D         : oem_qmi_lib:output 0
11-08 17:10:30.749  3762  4762 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-08 17:10:30.750   931  2952 E native  : do suspend true
11-08 17:10:30.750   931  2671 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-08 17:10:30.767  3762  4762 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-08 17:10:30.768  3762  4762 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-08 17:10:30.768  3762  4762 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-08 17:10:30.768   527  1366 D         : oem-qmi: Connection accepted
11-08 17:10:30.768   527  1366 D         : oem-qmi: Waiting to accept connection
,11-08 17:10:30.770  3762  4762 D         : oem_qmi_lib:output 0
11-08 17:10:30.770  3762  4762 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-08 17:10:30.913  5609  5657 I jxcore-log: 2016-11-08 16:10:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-08 17:10:30.913  5609  5657 I jxcore-log: 
,11-08 17:10:31.078  5609  5657 I jxcore-log: 2016-11-08 16:10:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-08 17:10:31.078  5609  5657 I jxcore-log: 
,11-08 17:10:31.084  5609  5657 I jxcore-log: 2016-11-08 16:10:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-08 17:10:31.084  5609  5657 I jxcore-log: 
,11-08 17:10:31.089  5609  5657 I jxcore-log: 2016-11-08 16:10:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-08 17:10:31.089  5609  5657 I jxcore-log: 
,11-08 17:10:31.233   931  2952 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,11-08 17:10:31.563  5609  5657 I jxcore-log: 2016-11-08 16:10:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-08 17:10:31.563  5609  5657 I jxcore-log: 
,11-08 17:10:31.605  5609  5657 I jxcore-log: 2016-11-08 16:10:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-08 17:10:31.605  5609  5657 I jxcore-log: 
,11-08 17:10:31.618  5609  5657 I jxcore-log: 2016-11-08 16:10:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-08 17:10:31.618  5609  5657 I jxcore-log: 
,11-08 17:10:31.622  5609  5657 I jxcore-log: 2016-11-08 16:10:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-08 17:10:31.622  5609  5657 I jxcore-log: 
,11-08 17:10:31.904  5609  5657 I jxcore-log: 2016-11-08 16:10:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-08 17:10:31.904  5609  5657 I jxcore-log: 
,11-08 17:10:32.041  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-08 17:10:32.041  5609  5657 I jxcore-log: 
,11-08 17:10:32.403  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-08 17:10:32.403  5609  5657 I jxcore-log: 
,11-08 17:10:32.437  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-08 17:10:32.437  5609  5657 I jxcore-log: 
,11-08 17:10:32.443  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-08 17:10:32.443  5609  5657 I jxcore-log: 
,11-08 17:10:32.448  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-08 17:10:32.448  5609  5657 I jxcore-log: 
,11-08 17:10:32.456  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-08 17:10:32.456  5609  5657 I jxcore-log: 
,11-08 17:10:32.468  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-08 17:10:32.468  5609  5657 I jxcore-log: 
,11-08 17:10:32.473  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-08 17:10:32.473  5609  5657 I jxcore-log: 
,11-08 17:10:32.499  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-08 17:10:32.499  5609  5657 I jxcore-log: 
,11-08 17:10:32.535  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-08 17:10:32.535  5609  5657 I jxcore-log: 
,11-08 17:10:32.543  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-08 17:10:32.543  5609  5657 I jxcore-log: 
,11-08 17:10:32.549  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-08 17:10:32.549  5609  5657 I jxcore-log: 
,11-08 17:10:32.564  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-08 17:10:32.564  5609  5657 I jxcore-log: 
,11-08 17:10:32.568  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-08 17:10:32.568  5609  5657 I jxcore-log: 
,11-08 17:10:32.574  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-08 17:10:32.574  5609  5657 I jxcore-log: 
,11-08 17:10:32.579  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-08 17:10:32.579  5609  5657 I jxcore-log: 
,11-08 17:10:32.592  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-08 17:10:32.592  5609  5657 I jxcore-log: 
,11-08 17:10:32.599  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-08 17:10:32.599  5609  5657 I jxcore-log: 
,11-08 17:10:32.621  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-08 17:10:32.621  5609  5657 I jxcore-log: 
,11-08 17:10:32.632  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-08 17:10:32.632  5609  5657 I jxcore-log: 
,11-08 17:10:32.644  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-08 17:10:32.644  5609  5657 I jxcore-log: 
,11-08 17:10:32.654  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-08 17:10:32.654  5609  5657 I jxcore-log: 
,11-08 17:10:32.666  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-08 17:10:32.666  5609  5657 I jxcore-log: 
,11-08 17:10:32.676  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-08 17:10:32.676  5609  5657 I jxcore-log: 
,11-08 17:10:32.683  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-08 17:10:32.683  5609  5657 I jxcore-log: 
,11-08 17:10:32.689  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-08 17:10:32.689  5609  5657 I jxcore-log: 
,11-08 17:10:32.695  5609  5657 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-08 17:10:32.696  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - INFO testUtils: 'BLE multiple advertisement supported'
11-08 17:10:32.696  5609  5657 I jxcore-log: 
,11-08 17:10:32.773  5609  5657 I jxcore-log: 2016-11-08 16:10:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:32.773  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:32.773  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:32.773  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:32.773  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:32.773  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:32.773  5609  5657 I jxcore-log: 
,11-08 17:10:33.075  5609  5657 I jxcore-log: 2016-11-08 16:10:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:33.075  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:33.075  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:33.075  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:33.075  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:33.075  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:33.075  5609  5657 I jxcore-log: 
,11-08 17:10:33.079  5609  5657 I jxcore-log: 2016-11-08 16:10:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:33.079  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:33.079  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:33.079  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:33.079  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:33.079  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:33.079  5609  5657 I jxcore-log: 
,11-08 17:10:33.573  5609  5657 I jxcore-log: 2016-11-08 16:10:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:33.573  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:33.573  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:33.573  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:33.573  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:33.573  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:33.573  5609  5657 I jxcore-log: 
,11-08 17:10:33.575  5609  5657 I jxcore-log: 2016-11-08 16:10:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:33.575  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:33.575  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:33.575  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:33.575  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:33.575  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:33.575  5609  5657 I jxcore-log: 
,11-08 17:10:34.424  3936  4447 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-08 17:10:34.611  5609  5657 I jxcore-log: 2016-11-08 16:10:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:34.611  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:34.611  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:34.611  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:34.611  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:34.611  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:34.611  5609  5657 I jxcore-log: 
,11-08 17:10:34.615  5609  5657 I jxcore-log: 2016-11-08 16:10:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:34.615  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:34.615  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:34.615  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:34.615  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:34.615  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:34.615  5609  5657 I jxcore-log: 
,11-08 17:10:35.652  5609  5657 I jxcore-log: 2016-11-08 16:10:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:35.652  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:35.652  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:35.652  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:35.652  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:35.652  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:35.652  5609  5657 I jxcore-log: 
,11-08 17:10:35.665  5609  5657 I jxcore-log: 2016-11-08 16:10:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:35.665  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:35.665  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:35.665  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:35.665  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:35.665  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:35.665  5609  5657 I jxcore-log: 
,11-08 17:10:36.705  5609  5657 I jxcore-log: 2016-11-08 16:10:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:36.705  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:36.705  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:36.705  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:36.705  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:36.705  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:36.705  5609  5657 I jxcore-log: 
,11-08 17:10:36.709  5609  5657 I jxcore-log: 2016-11-08 16:10:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:36.709  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:36.709  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:36.709  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:36.709  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:36.709  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:36.709  5609  5657 I jxcore-log: 
,11-08 17:10:37.742  5609  5657 I jxcore-log: 2016-11-08 16:10:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:37.742  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:37.742  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:37.742  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:37.742  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:37.742  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:37.742  5609  5657 I jxcore-log: 
,11-08 17:10:37.746  5609  5657 I jxcore-log: 2016-11-08 16:10:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:37.746  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:37.746  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:37.746  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:37.746  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:37.746  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:37.746  5609  5657 I jxcore-log: 
,11-08 17:10:37.775   931  5879 D NetlinkSocketObserver: NeighborEvent{elapsedMs=159890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-08 17:10:38.778  5609  5657 I jxcore-log: 2016-11-08 16:10:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:38.778  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:38.778  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:38.778  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:38.778  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:38.778  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:38.778  5609  5657 I jxcore-log: 
,11-08 17:10:38.781  5609  5657 I jxcore-log: 2016-11-08 16:10:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:38.781  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:38.781  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:38.781  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:38.781  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:38.781  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:38.781  5609  5657 I jxcore-log: 
,11-08 17:10:39.813  5609  5657 I jxcore-log: 2016-11-08 16:10:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:39.813  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:39.813  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:39.813  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:39.813  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:39.813  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:39.813  5609  5657 I jxcore-log: 
,11-08 17:10:39.820  5609  5657 I jxcore-log: 2016-11-08 16:10:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:39.820  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:39.820  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:39.820  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:39.820  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:39.820  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:39.820  5609  5657 I jxcore-log: 
,11-08 17:10:40.850  5609  5657 I jxcore-log: 2016-11-08 16:10:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:40.850  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:40.850  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:40.850  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:40.850  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:40.850  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:40.850  5609  5657 I jxcore-log: 
,11-08 17:10:40.855  5609  5657 I jxcore-log: 2016-11-08 16:10:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:40.855  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:40.855  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:40.855  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:40.855  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:40.855  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:40.855  5609  5657 I jxcore-log: 
,11-08 17:10:41.701   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:41.935  5609  5657 I jxcore-log: 2016-11-08 16:10:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:41.935  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:41.935  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:41.935  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:41.935  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:41.935  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:41.935  5609  5657 I jxcore-log: 
11-08 17:10:41.939  5609  5657 I jxcore-log: 2016-11-08 16:10:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:41.939  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:41.939  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:41.939  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:41.939  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:41.939  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:41.939  5609  5657 I jxcore-log: 
,11-08 17:10:41.962   931  2952 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,11-08 17:10:42.703   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:42.974  5609  5657 I jxcore-log: 2016-11-08 16:10:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:42.974  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:42.974  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:42.974  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:42.974  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:42.974  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:42.974  5609  5657 I jxcore-log: 
11-08 17:10:42.979  5609  5657 I jxcore-log: 2016-11-08 16:10:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:42.979  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:42.979  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:42.979  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:42.979  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:42.979  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:42.979  5609  5657 I jxcore-log: 
,11-08 17:10:43.704   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:44.010  5609  5657 I jxcore-log: 2016-11-08 16:10:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:44.010  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:44.010  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:44.010  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:44.010  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:44.010  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:44.010  5609  5657 I jxcore-log: 
,11-08 17:10:44.015  5609  5657 I jxcore-log: 2016-11-08 16:10:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:44.015  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:44.015  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:44.015  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:44.015  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:44.015  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:44.015  5609  5657 I jxcore-log: 
,11-08 17:10:44.705   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:45.044  5609  5657 I jxcore-log: 2016-11-08 16:10:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:45.044  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:45.044  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:45.044  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:45.044  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:45.044  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:45.044  5609  5657 I jxcore-log: 
,11-08 17:10:45.049  5609  5657 I jxcore-log: 2016-11-08 16:10:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:45.049  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:45.049  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:45.049  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:45.049  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:45.049  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:45.049  5609  5657 I jxcore-log: 
,11-08 17:10:45.707   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,11-08 17:10:46.079  5609  5657 I jxcore-log: 2016-11-08 16:10:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:46.079  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:46.079  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:46.079  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:46.079  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:46.079  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:46.079  5609  5657 I jxcore-log: 
,11-08 17:10:46.082  5609  5657 I jxcore-log: 2016-11-08 16:10:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:46.082  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:46.082  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:46.082  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:46.082  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:46.082  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:46.082  5609  5657 I jxcore-log: 
,11-08 17:10:46.707   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-08 17:10:47.115  5609  5657 I jxcore-log: 2016-11-08 16:10:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-08 17:10:47.115  5609  5657 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-08 17:10:47.115  5609  5657 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-08 17:10:47.115  5609  5657 I jxcore-log: emit@events.js:82:1
11-08 17:10:47.115  5609  5657 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-08 17:10:47.115  5609  5657 I jxcore-log: emit@events.js:82:1'
11-08 17:10:47.115  5609  5657 I jxcore-log: 
,11-08 17:10:47.126  5609  5657 E jxcore  : Error!: error is undefined
11-08 17:10:47.126  5609  5657 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-08 17:10:47.129  5609  5657 I jxcore-log: 2016-11-08 16:10:47 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-08 17:10:47.129  5609  5657 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-08 17:10:47.129  5609  5657 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-08 17:10:47.129  5609  5657 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-08 17:10:47.129  5609  5657 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-08 17:10:47.129  5609  5657 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-08 17:10:47.129  5609  5657 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-08 17:10:47.129  5609  5657 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-08 17:10:47.130  5609  5657 I jxcore-log: 2016-11-08 16:10:47 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-08 17:10:47.130  5609  5657 I jxcore-log: 
,11-08 17:10:47.133  5609  5657 E jxcore-log: TypeError: 
11-08 17:10:47.133  5609  5657 E jxcore-log: error is undefined
11-08 17:10:47.133  5609  5657 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-08 17:10:47.133  5609  5657 E jxcore-log: 
,11-08 17:10:47.200   931  2943 W InputDispatcher: channel 'bd006f4 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-08 17:10:47.200   931  2943 E InputDispatcher: channel 'bd006f4 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-08 17:10:47.209   931   941 D GraphicsStats: Buffer count: 2
,11-08 17:10:47.210   931  3131 I WindowState: WIN DEATH: Window{bd006f4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-08 17:10:47.210   931  3131 W InputDispatcher: Attempted to unregister already unregistered input channel 'bd006f4 com.test.thalitest/com.test.thalitest.MainActivity (server)'
11-08 17:10:47.213   931  2953 D WifiService: Client connection lost with reason: 4
,11-08 17:10:47.218   529   529 I Zygote  : Process 5609 exited cleanly (139)
,11-08 17:10:47.222   931   941 I ActivityManager: Process com.test.thalitest (pid 5609) has died
,11-08 17:10:47.244   931   941 I ActivityManager: Start proc 5953:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-08 17:10:47.325  5953  5953 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-08 17:10:47.347  5953  5953 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-08 17:10:47.353  5953  5953 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9466-9469)
,11-08 17:10:47.353  5953  5953 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-08 17:10:47.363  5953  5953 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4aca7c6}
,11-08 17:10:47.363  5953  5953 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-08 17:10:47.364  5953  5953 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-08 17:10:47.367  5953  5953 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-08 17:10:47.368  5953  5953 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-08 17:10:47.382  5953  5953 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-08 17:10:47.389  5953  5953 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-08 17:10:47.389  5953  5953 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-08 17:10:47.389  5953  5953 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-08 17:10:47.389  5953  5953 I Adreno  : Build Date                       : 12/06/15
11-08 17:10:47.389  5953  5953 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-08 17:10:47.389  5953  5953 I Adreno  : Local Branch                     : mybranch17112971
11-08 17:10:47.389  5953  5953 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-08 17:10:47.389  5953  5953 I Adreno  : Remote Branch                    : NONE
11-08 17:10:47.389  5953  5953 I Adreno  : Reconstruct Branch               : NOTHING
,11-08 17:10:47.434   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f799549:true
,11-08 17:10:47.445   404   404 W Binder_1: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[14023]" dev="sockfs" ino=14023 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:47.445   404   404 W Binder_1: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[14023]" dev="sockfs" ino=14023 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:47.459  5953  5953 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-08 17:10:47.467  5953  5953 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-08 17:10:47.503  5953  5989 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-08 17:10:47.499   765   765 W Binder_3: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[36471]" dev="sockfs" ino=36471 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-08 17:10:47.499   765   765 W Binder_3: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[36471]" dev="sockfs" ino=36471 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:47.505  3840  3840 W Binder_A: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[14738]" dev="sockfs" ino=14738 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:47.505  3840  3840 W Binder_A: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[14738]" dev="sockfs" ino=14738 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:47.510  5953  5976 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-08 17:10:47.547  5953  5989 I OpenGLRenderer: Initialized EGL, version 1.4
,11-08 17:10:47.575  5951  5951 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-08 17:10:47.578  5951  5951 D AndroidRuntime: CheckJNI is OFF
,11-08 17:10:47.600  5951  5951 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-08 17:10:47.610   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +340ms (total +383ms)
,11-08 17:10:47.610   931   941 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5609 uid 10077
,11-08 17:10:47.609   941   941 W Binder_1: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[31560]" dev="sockfs" ino=31560 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:47.609   941   941 W Binder_1: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[31560]" dev="sockfs" ino=31560 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-08 17:10:47.609  3837  3837 W Binder_9: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[31559]" dev="sockfs" ino=31559 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:47.609  3837  3837 W Binder_9: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[31559]" dev="sockfs" ino=31559 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-08 17:10:47.614  3654  3654 I Keyboard.Facilitator: onFinishInput()
,11-08 17:10:47.626  5951  5951 I Radio-JNI: register_android_hardware_Radio DONE
,11-08 17:10:47.630  5953  5953 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5953
,11-08 17:10:47.640  5951  5951 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-08 17:10:47.650   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-08 17:10:47.651   931   944 I ActivityManager: Killing 5953:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-08 17:10:47.685   931  3785 D GraphicsStats: Buffer count: 2
,11-08 17:10:47.685   931  3837 I WindowState: WIN DEATH: Window{2b7d0ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-08 17:10:47.762   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-08 17:10:47.763   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-08 17:10:47.764   931   944 E ActivityManager: Failure starting process com.test.thalitest
11-08 17:10:47.764   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-08 17:10:47.764   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:10:47.764   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:47.764   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-08 17:10:47.764   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-08 17:10:47.765   931   954 I art     : Starting a blocking GC Explicit
11-08 17:10:47.765   931   944 I ActivityManager:   Force finishing activity ActivityRecord{6bba285 u0 com.test.thalitest/.MainActivity t68}
,11-08 17:10:47.780   931  3426 W ActivityManager: Spurious death for ProcessRecord{9a0250a 0:com.test.thalitest/u0a77}, curProc for 5953: null
,11-08 17:10:47.851   931   954 I art     : Explicit concurrent mark sweep GC freed 15785(1064KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 1.596ms total 85.217ms
,11-08 17:10:47.873   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-08 17:10:47.877  5951  5951 I art     : System.exit called, status: 0
11-08 17:10:47.877  5951  5951 I AndroidRuntime: VM exiting with result code 0.
,11-08 17:10:47.887   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-08 17:10:47.896   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-08 17:10:47.901  3654  3654 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-08 17:10:47.903  5816  5816 D BluetoothMapAppObserver: onReceive
,11-08 17:10:47.903  5816  5816 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-08 17:10:47.908  3936  4142 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-08 17:10:47.920   931  2944 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-08 17:10:47.950  3408  6005 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
11-08 17:10:47.952  3762  3762 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-08 17:10:47.953  3654  6003 I Keyboard.Facilitator.DecoderInitializer: run()
,11-08 17:10:47.965    29    29 W kworker/3:1: type=1400 audit(0.0:137): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 17:10:47.969    29    29 W kworker/3:1: type=1400 audit(0.0:138): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 17:10:47.971  3592  3592 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-08 17:10:47.971  3592  3592 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-08 17:10:47.983  3654  6003 I Decoder : createOrResetDecoder
11-08 17:10:47.985  3797  3922 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-08 17:10:47.986   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-08 17:10:47.989    29    29 W kworker/3:1: type=1400 audit(0.0:139): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-08 17:10:47.998   931  3785 I ActivityManager: Start proc 6009:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-08 17:10:48.000  3797  3922 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-08 17:10:48.000  3797  3922 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3797
11-08 17:10:48.000  3797  3922 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:48.000  3797  3922 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-08 17:10:48.008   931  3802 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-08 17:10:48.011   931  6019 E DropBoxManagerService: Can't write: system_app_crash
11-08 17:10:48.011   931  6019 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 17:10:48.011   931  6019 E DropBoxManagerService: 	... 5 more
,11-08 17:10:48.020  3797  3922 I Process : Sending signal. PID: 3797 SIG: 9
,11-08 17:10:48.032  3592  3592 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/ns.db'.
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:10:48.032  3592  3592 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-08 17:10:48.033  3592  3592 D AndroidRuntime: Shutting down VM
,11-08 17:10:48.033  3592  3592 E AndroidRuntime: FATAL EXCEPTION: main
11-08 17:10:48.033  3592  3592 E AndroidRuntime: Process: com.google.process.gapps, PID: 3592
11-08 17:10:48.033  3592  3592 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-08 17:10:48.033  3592  3592 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: Can't write: system_app_crash
11-08 17:10:48.036   931  6024 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: Caused by,: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-08 17:10:48.036   931  6024 E DropBoxManagerService: 	... 5 more
11-08 17:10:48.037  3592  3592 I Process : Sending signal. PID: 3592 SIG: 9
11-08 17:10:48.047   381   381 E lowmemorykiller: Error writing /proc/3592/oom_score_adj; errno=22
11-08 17:10:48.055  3408  3435 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjECD716931) - 
11-08 17:10:48.058  4041  6023 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-08 17:10:48.058  4041  6023 D AccountUtils: Clearing selected account for com.test.thalitest

```
