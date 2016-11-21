#### Test 935721672bafbe2_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-21 16:49:26.875   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:49:27.344  5731  5731 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-21 16:49:27.349  5731  5731 D AndroidRuntime: CheckJNI is OFF
11-21 16:49:27.376  5731  5731 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-21 16:49:27.414  5731  5731 I Radio-JNI: register_android_hardware_Radio DONE
11-21 16:49:27.430  5731  5731 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-21 16:49:27.444   934  3920 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-21 16:49:27.461  5731  5731 D AndroidRuntime: Shutting down VM
11-21 16:49:27.470  4023  5637 W SearchService: Abort, client detached.
11-21 16:49:27.479  4023  4023 I HotwordDetector: Closing mic
11-21 16:49:27.479  4023  4250 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c4746e9
11-21 16:49:27.480  4023  4263 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-21 16:49:27.500   934  3859 I ActivityManager: Start proc 5740:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-21 16:49:27.559   516  4268 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-21 16:49:27.560   516  4268 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-21 16:49:27.568   516  4268 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-21 16:49:27.569   516  4268 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-21 16:49:27.570   516  3044 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-21 16:49:27.573  4023  4253 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-21 16:49:27.573  4023  4261 I MicroRecognitionRnrImpl: Detection finished
11-21 16:49:27.595  5740  5740 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-21 16:49:27.621  5740  5740 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-21 16:49:27.691  5740  5740 I LibraryLoader: Time to load native libraries: 66 ms (timestamps 5987-6053)
11-21 16:49:27.691  5740  5740 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-21 16:49:27.729  5740  5740 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f7581f}
,11-21 16:49:27.730  5740  5740 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-21 16:49:27.730  5740  5740 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-21 16:49:27.736  5740  5740 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-21 16:49:27.737  5740  5740 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-21 16:49:27.774  5740  5740 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-21 16:49:27.791  5740  5740 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-21 16:49:27.791  5740  5740 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-21 16:49:27.791  5740  5740 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-21 16:49:27.791  5740  5740 I Adreno  : Build Date                       : 12/06/15
11-21 16:49:27.791  5740  5740 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-21 16:49:27.791  5740  5740 I Adreno  : Local Branch                     : mybranch17112971
11-21 16:49:27.791  5740  5740 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-21 16:49:27.791  5740  5740 I Adreno  : Remote Branch                    : NONE
11-21 16:49:27.791  5740  5740 I Adreno  : Reconstruct Branch               : NOTHING
,11-21 16:49:27.846   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9bd775e:true
,11-21 16:49:27.875   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:49:27.884   772   772 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[26263]" dev="sockfs" ino=26263 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:27.884   772   772 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26263]" dev="sockfs" ino=26263 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:27.895  5740  5740 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-21 16:49:27.905  5740  5740 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-21 16:49:27.934   772   772 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33193]" dev="sockfs" ino=33193 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:27.934   772   772 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33193]" dev="sockfs" ino=33193 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:27.934  5740  5777 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-21 16:49:27.937  3467  3467 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[15085]" dev="sockfs" ino=15085 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:27.937  3467  3467 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[15085]" dev="sockfs" ino=15085 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:27.940  5740  5764 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-21 16:49:27.966  5740  5777 I OpenGLRenderer: Initialized EGL, version 1.4
,11-21 16:49:28.040  3927  3927 W Binder_E: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32257]" dev="sockfs" ino=32257 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:28.040  3927  3927 W Binder_E: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32257]" dev="sockfs" ino=32257 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:28.042   934   952 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +566ms
,11-21 16:49:28.044  3909  3909 W Binder_A: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32256]" dev="sockfs" ino=32256 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:28.044  3909  3909 W Binder_A: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32256]" dev="sockfs" ino=32256 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:28.048  3711  3711 I Keyboard.Facilitator: onFinishInput()
,11-21 16:49:28.079  5740  5740 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5740
,11-21 16:49:28.172  5740  5740 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-21 16:49:28.295   934   944 I ActivityManager: Killing 5106:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-21 16:49:28.321   934   944 I ActivityManager: Killing 5331:com.android.settings/1000 (adj 15): empty #18
,11-21 16:49:28.789  5740  5779 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -577504976
,11-21 16:49:28.830  5740  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-21 16:49:28.830  5740  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-21 16:49:28.830  5740  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-21 16:49:28.830  5740  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-21 16:49:28.830  5740  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-21 16:49:28.831  5740  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b8d6e2 added. We now have 1 listener(s)
,11-21 16:49:28.843  5740  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-21 16:49:28.846  5740  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 16:49:28.848  5740  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 16:49:28.849  5740  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-21 16:49:28.859  5740  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc0da9 added. We now have 1 listener(s)
11-21 16:49:28.860  5740  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:49:28.869   934  3023 D WifiService: New client listening to asynchronous messages
,11-21 16:49:28.870  5740  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 16:49:28.870  5740  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-21 16:49:28.871  5740  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-21 16:49:28.871  5740  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-21 16:49:28.872  5740  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-21 16:49:28.872  5740  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-21 16:49:28.872  5740  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-21 16:49:28.876  5740  5779 I io.jxcore.node.LifeCycleMonitor: start: OK
11-21 16:49:28.877   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:49:28.934  5740  5740 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-21 16:49:29.374  5740  5788 W jxcore-log: Initializing JXcore engine
,11-21 16:49:29.375  5740  5788 W jxcore-log: JXcore engine is ready
,11-21 16:49:29.400  5788  5788 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11647 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-21 16:49:29.400  5788  5788 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13353]" dev="sockfs" ino=13353 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-21 16:49:29.400  5788  5788 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-21 16:49:29.400  5788  5788 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33819]" dev="sockfs" ino=33819 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-21 16:49:29.407  5740  5788 W jxcore-log: Starting JXcore engine
,11-21 16:49:29.457  5740  5788 W jxcore-log: Platform android
11-21 16:49:29.457  5740  5788 W jxcore-log: 
,11-21 16:49:29.457  5740  5788 W jxcore-log: Process ARCH arm
11-21 16:49:29.457  5740  5788 W jxcore-log: 
,11-21 16:49:29.602  5740  5788 I jxcore-log: JXcore Cordova bridge is ready!
11-21 16:49:29.602  5740  5788 I jxcore-log: 
,11-21 16:49:29.602  5740  5788 W jxcore-log: JXcore engine is started
11-21 16:49:29.609  5740  5779 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
11-21 16:49:29.620  5740  5740 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-21 16:49:29.877   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-21 16:49:30.754   934  5421 D NetlinkSocketObserver: NeighborEvent{elapsedMs=149117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:49:39.062  4091  4521 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-21 16:49:39.235  5740  5788 I jxcore-log: 2016-11-21 15:49:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-21 16:49:39.235  5740  5788 I jxcore-log: 
,11-21 16:49:39.237  5740  5788 I jxcore-log: 2016-11-21 15:49:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-21 16:49:39.237  5740  5788 I jxcore-log: 
,11-21 16:49:39.243  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-21 16:49:39.243  5740  5788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 16:49:39.243  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:49:39.243  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:49:39.243  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:49:39.243  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:49:39.243  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:49:39.243  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:49:39.243  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:49:39.243  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 16:49:39.260  5740  5788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:49:39.262  5740  5788 I jxcore-log: 2016-11-21 15:49:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-21 16:49:39.262  5740  5788 I jxcore-log: 
,11-21 16:49:39.263  5740  5788 I jxcore-log: 2016-11-21 15:49:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-21 16:49:39.263  5740  5788 I jxcore-log: 
,11-21 16:49:39.504  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 16:49:39.504  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7eb2073 added. We now have 2 listener(s)
11-21 16:49:39.505  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 16:49:39.505  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-21 16:49:39.505  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 16:49:39.505  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:49:39.505  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef20b30 added. We now have 2 listener(s)
11-21 16:49:39.505  5740  5788 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:49:39.506  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-21 16:49:39.507  5740  5788 D ExecuteNativeTests: Running unit tests
11-21 16:49:39.508  5740  5788 D BluetoothAdapter: enable(): BT is already enabled..!
11-21 16:49:39.508   934  3203 D WifiService: setWifiEnabled: true pid=5740, uid=10077
11-21 16:49:39.508   934  3203 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:49:42.908  4023  5791 W CronetSyncConnectionRcs: Upload content type not set.
,11-21 16:49:42.993  3626  5798 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-21 16:49:43.032  3626  5796 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-21 16:49:43.035  3626  5796 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-21 16:49:43.063  3626  5796 W Uploader:  no longer exists, so no auth token.
,11-21 16:49:43.071  3626  5798 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:49:43.737   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:49:43.958  3626  5805 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:49:44.235  3626  5796 W Uploader:  no longer exists, so no auth token.
,11-21 16:49:44.246  3626  5806 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:49:44.330  3626  5805 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:49:44.404  3626  5806 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:49:44.484  3626  5805 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-21 16:49:44.878   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:49:45.880   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:49:46.771   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-21 16:49:46.881   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:49:47.882   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:49:47.928   934  5421 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:49:48.884   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:49:49.513  5740  5788 I com.test.thalitest.ThaliTestRunner: Running UT
,11-21 16:49:49.581  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 16:49:49.582  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4b9c42 added. We now have 3 listener(s)
11-21 16:49:49.582  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:49:49.583  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:49:49.583  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-21 16:49:49.583  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:49:49.583  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d9d453 added. We now have 3 listener(s)
11-21 16:49:49.583  5740  5788 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 16:49:49.584  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:49:49.588  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
11-21 16:49:49.588  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 16:49:49.588  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:49:49.588  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:49:49.588  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:49:49.589  5740  5788 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-21 16:49:49.589  5740  5788 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 16:49:49.589  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 16:49:49.589  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:49:49.589  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-21 16:49:49.589  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:49:49.590  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,11-21 16:49:49.591  5740  5788 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-21 16:49:49.592  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-21 16:49:49.594  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-21 16:49:49.594  5740  5788 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 16:49:49.596  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:49:49.596  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-21 16:49:49.601  5740  5788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-21 16:49:49.601  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:49:49.601  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:49:49.601  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:49:49.601  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:49:49.601  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:49:49.601  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:49:49.601  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:49:49.601  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 16:49:49.602  5740  5788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-21 16:49:49.603  5740  5788 D io.jxcore.node.ConnectivityMonitor: start: OK
11-21 16:49:49.603  5740  5788 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-21 16:49:49.603  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,11-21 16:49:49.603  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.603  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.603  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.603  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:49:49.603  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:49:49.603  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-21 16:49:49.603  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 16:49:49.604  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:49:49.604  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:49:49.604  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:49:49.604  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 16:49:49.605  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:49:49.605  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 16:49:49.605  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:49:49.605  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:49:49.605  5740  5808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:49:49.607  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:49:49.607  5740  5788 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:49:49.607  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 16:49:49.608  5740  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 16:49:49.609  5740  5808 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:49:49.607  4709  4709 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[16735]" dev="sockfs" ino=16735 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:49.610  5740  5808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:49:49.611  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.607  4709  4709 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[16735]" dev="sockfs" ino=16735 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:49.611  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:49:49.611  5740  5740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 16:49:49.611  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:49:49.613  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:49:49.614  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:49:49.614  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-21 16:49:49.615  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.615  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.615  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:49:49.615  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:49:49.616  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:49:49.616  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-21 16:49:49.616  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:49.616  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:49.616  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.616  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:49:49.616  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:49.616  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.616  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.617  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a4,4ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.617  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:49:49.620  4689  4706 D BtGatt.GattService: registerClient() - UUID=64b68e5c-35ce-40ff-b5d0-9cf4c65738e3
,11-21 16:49:49.621  4689  4761 D BtGatt.GattService: onClientRegistered() - UUID=64b68e5c-35ce-40ff-b5d0-9cf4c65738e3, clientIf=5
11-21 16:49:49.622  5740  5750 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 16:49:49.625  4689  4765 D BtGatt.AdvertiseManager: message : 0
11-21 16:49:49.628  4689  4765 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:49:49.645  4689  4761 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:49:49.654  4689  4761 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:49:49.655  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.655  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:49.655  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:49:49.656  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.656  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.656  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.656  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.656  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.656  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 16:49:49.656  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:49:49.656  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.657  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.657  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:49.657  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:49.657  5740  5788 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:49:49.658  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:49:49.659  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:49:49.659  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:49.659  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-21 16:49:49.659  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:49:49.660  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-21 16:49:49.660  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:49.660  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:49:49.661  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-21 16:49:49.661  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:49:49.661  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 16:49:49.661  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:49:49.661  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:49:49.661  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:49:49.666  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:49:49.666  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:49:49.666  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:49.666  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:49.667  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:49:49.667  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:49:49.885   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 16:49:50.161  5740  5788 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-21 16:49:50.161  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-21 16:49:50.161  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-21 16:49:50.161  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-21 16:49:50.162  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-21 16:49:50.162  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-21 16:49:50.162  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 16:49:50.162  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-21 16:49:50.162  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-21 16:49:50.162  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-21 16:49:50.162  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 16:49:50.162  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-21 16:49:50.162  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-21 16:49:50.163  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 16:49:50.164  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-21 16:49:50.164  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-21 16:49:50.164  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 16:49:50.164  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-21 16:49:50.164  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-21 16:49:50.164  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-21 16:49:50.164  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-21 16:49:50.164  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 16:49:50.165  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-21 16:49:50.165  5740  5788 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 16:49:50.165  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 16:49:50.165  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 16:49:50.165  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:49:50.165  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:49:50.166  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:49:50.166  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 16:49:50.166  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:49:50.166  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:49:50.166  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-21 16:49:50.167  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:49:50.167  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:49:50.167  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:49:50.167  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:49:50.168  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.168  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.168  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.168  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.169  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:49:50.170  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:49:50.169  5740  5808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:49:50.170  5740  5808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:49:50.170  5740  5808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-21 16:49:50.170  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:49:50.171  5740  5788 D BluetoothLeScanner: could not find callback wrapper
11-21 16:49:50.171  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:49:50.171  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.171  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.171  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.171  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-21 16:49:50.171  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.173  4689  4765 D BtGatt.AdvertiseManager: message : 1
11-21 16:49:50.175  4689  4765 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:49:50.188  4689  4761 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 16:49:50.188  4689  4761 D BtGatt.GattService: Client app is not null!
11-21 16:49:50.189  4689  4709 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:49:50.190  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:49:50.191  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.191  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:49:50.191  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.191  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.191  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.191  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:49:50.192  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:49:50.193  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:49:50.194  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.196  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.196  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:49:50.196  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.196  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.197  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 16:49:50.197  5740  5740 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:49:50.200  5740  5740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 16:49:50.201  5740  5788 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,11-21 16:49:50.201  5740  5788 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-21 16:49:50.201  5740  5788 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,11-21 16:49:50.201  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-21 16:49:50.201  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-21 16:49:50.201  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:49:50.201  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:49:50.201  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:49:50.202  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:50.202  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.202  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 16:49:50.202  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.202  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-21 16:49:50.202  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.202  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-21 16:49:50.202  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:49:50.202  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.202  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-21 16:49:50.202  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:49:50.202  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.202  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:49:50.202  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:49:50.202  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.203  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:49:50.204  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:49:50.204  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:49:50.204  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:49:50.204  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-21 16:49:50.204  5740  5811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:49:50.206  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.206  5740  5811 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:49:50.207  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.207  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.207  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.207  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 16:49:50.207  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 16:49:50.207  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:49:50.207  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:49:50.207  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:49:50.210  4921  4921 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31383]" dev="sockfs" ino=31383 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:50.210  4921  4921 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31383]" dev="sockfs" ino=31383 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:50.212  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:49:50.212  5740  5788 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-21 16:49:50.212  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-21 16:49:50.213  5740  5811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 16:49:50.218  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.218  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:49:50.219  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:49:50.219  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:49:50.219  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
,11-21 16:49:50.221  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.221  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.221  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:49:50.221  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:49:50.222  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:49:50.222  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-21 16:49:50.222  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:50.222  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:50.222  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.222  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-21 16:49:50.222  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:50.222  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.222  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.223  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.224  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:49:50.227  4689  4909 D BtGatt.GattService: registerClient() - UUID=0ecd24ae-daca-4c1e-8412-9e7e139d347c
,11-21 16:49:50.228  4689  4761 D BtGatt.GattService: onClientRegistered() - UUID=0ecd24ae-daca-4c1e-8412-9e7e139d347c, clientIf=5
11-21 16:49:50.228  5740  5784 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 16:49:50.229  4689  4765 D BtGatt.AdvertiseManager: message : 0
,11-21 16:49:50.233  4689  4765 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:49:50.245  4689  4761 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:49:50.253  4689  4761 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:49:50.253  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.254  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.254  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:49:50.254  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.254  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.254  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.254  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.254  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.254  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 16:49:50.256  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-21 16:49:50.256  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.257  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.257  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.258  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.258  5740  5788 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:49:50.258  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:49:50.258  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.258  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:50.258  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:49:50.259  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-21 16:49:50.259  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.259  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:50.259  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.259  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:49:50.259  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:49:50.259  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-21 16:49:50.259  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.260  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:49:50.260  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:49:50.263  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-21 16:49:50.263  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:49:50.263  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.263  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.263  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.263  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:49:50.762  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,11-21 16:49:50.763  5740  5788 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 16:49:50.763  5740  5788 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 16:49:50.763  5740  5788 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-21 16:49:50.763  5740  5788 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-21 16:49:50.763  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,11-21 16:49:50.764  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.764  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.764  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.765  5740  5740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 16:49:50.768  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.770  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
,11-21 16:49:50.774  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.774  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.775  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.782  4689  4765 D BtGatt.AdvertiseManager: message : 1
,11-21 16:49:50.782  4689  4765 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:49:50.794  4689  4761 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 16:49:50.794  4689  4761 D BtGatt.GattService: Client app is not null!
,11-21 16:49:50.797  4689  4921 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:49:50.798  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:49:50.798  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.798  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:49:50.798  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.799  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.799  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.799  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:49:50.799  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.799  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.799  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.799  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:49:50.799  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:49:50.799  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:49:50.800  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
,11-21 16:49:50.800  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-21 16:49:50.800  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:50.800  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.800  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:49:50.801  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:50.801  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.801  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.801  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.802  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:49:50.805  4689  4921 D BtGatt.GattService: registerClient() - UUID=f0096b16-d696-4060-8e7e-e0d105ce4863
11-21 16:49:50.805  4689  4761 D BtGatt.GattService: onClientRegistered() - UUID=f0096b16-d696-4060-8e7e-e0d105ce4863, clientIf=5
11-21 16:49:50.806  5740  5784 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 16:49:50.807  4689  4765 D BtGatt.AdvertiseManager: message : 0
,11-21 16:49:50.809  4689  4765 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:49:50.820  4689  4761 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:49:50.826  4689  4761 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:49:50.827  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.827  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.827  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:49:50.827  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.827  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.827  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.827  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.827  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.828  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.828  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:49:50.828  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.828  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:49:50.828  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 16:49:50.828  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-21 16:49:50.828  5740  5788 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:49:50.828  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.828  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:50.829  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:49:50.829  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.829  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.829  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:50.829  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.829  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:49:50.829  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:49:50.829  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.829  5740  5788 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-21 16:49:50.829  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.829  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-21 16:49:50.829  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-21 16:49:50.829  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:49:50.829  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:49:50.829  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:49:50.830  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 16:49:50.830  5740  5811 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:49:50.830  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:49:50.830  5740  5811 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:49:50.830  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:49:50.830  5740  5811 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:49:50.830  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-21 16:49:50.830  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:49:50.830  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:49:50.830  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:49:50.830  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:49:50.830  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.830  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.830  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.830  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.831  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:49:50.831  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:49:50.832  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:49:50.832  5740  5788 D BluetoothLeScanner: could not find callback wrapper
11-21 16:49:50.832  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:49:50.832  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.832  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.832  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.832  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:49:50.832  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.833  4689  4765 D BtGatt.AdvertiseManager: message : 1
11-21 16:49:50.833  4689  4765 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-21 16:49:50.846  4689  4761 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 16:49:50.846  4689  4761 D BtGatt.GattService: Client app is not null!
,11-21 16:49:50.847  4689  4709 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:49:50.847  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:49:50.848  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.848  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:49:50.848  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.848  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.848  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.848  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:49:50.848  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:49:50.849  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:49:50.849  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.850  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.850  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:49:50.850  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.850  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.850  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 16:49:50.850  5740  5740 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 16:49:50.850  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:49:50.850  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:49:50.850  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:49:50.850  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:49:50.851  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:50.851  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.851  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-21 16:49:50.851  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:49:50.851  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.851  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.851  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:49:50.851  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:49:50.852  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
,11-21 16:49:50.852  5740  5788 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-21 16:49:50.853  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.853  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.853  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.853  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.853  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:49:50.853  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-21 16:49:50.853  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-21 16:49:50.854  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-21 16:49:50.854  5740  5788 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-21 16:49:50.855  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-21 16:49:50.855  5740  5788 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-21 16:49:50.855  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-21 16:49:50.856  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-21 16:49:50.856  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:49:50.856  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:49:50.856  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:49:50.856  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 16:49:50.856  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:49:50.856  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-21 16:49:50.856  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:49:50.856  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-21 16:49:50.856  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:49:50.856  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:49:50.856  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-21 16:49:50.857  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-21 16:49:50.857  5740  5788 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 16:49:50.857  5740  5788 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 16:49:50.857  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-21 16:49:50.860  5740  5788 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 16:49:50.860  5740  5788 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-21 16:49:50.860  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-21 16:49:50.860  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-21 16:49:50.861  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-21 16:49:50.862  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-21 16:49:50.862  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-21 16:49:50.862  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-21 16:49:50.862  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-21 16:49:50.862  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-21 16:49:50.862  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-21 16:49:50.862  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-21 16:49:50.862  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-21 16:49:50.862  5740  5788 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-21 16:49:50.862  5740  5788 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-21 16:49:50.862  5740  5788 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-21 16:49:50.862  5740  5788 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 16:49:50.863  5740  5788 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-21 16:49:50.863  5740  5788 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-21 16:49:50.863  5740  5788 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 16:49:50.863  5740  5788 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-21 16:49:50.863  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-21 16:49:50.870  4709  4709 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33889]" dev="sockfs" ino=33889 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:50.870  4709  4709 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[33889]" dev="sockfs" ino=33889 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:50.867  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-21 16:49:50.867  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-21 16:49:50.867  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-21 16:49:50.868  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-21 16:49:50.868  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-21 16:49:50.868  5740  5788 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,11-21 16:49:50.868  5740  5788 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-21 16:49:50.869  5740  5788 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-21 16:49:50.869  5740  5815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 134)
11-21 16:49:50.869  5740  5815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-21 16:49:50.869  5740  5815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,11-21 16:49:50.869  5740  5815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-21 16:49:50.869  5740  5815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-21 16:49:50.869  5740  5815 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-21 16:49:50.869  5740  5815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:49:50.870  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-21 16:49:50.871  5740  5788 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-21 16:49:50.873  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-21 16:49:50.873  5740  5788 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-21 16:49:50.873  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-21 16:49:50.874  5740  5788 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-21 16:49:50.874  5740  5788 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-21 16:49:50.874  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 16:49:50.874  5740  5788 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-21 16:49:50.875  5740  5788 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 16:49:50.875  5740  5788 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-21 16:49:50.875  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-21 16:49:50.875  5740  5788 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-21 16:49:50.875  5740  5788 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-21 16:49:50.875  5740  5788 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-21 16:49:50.875  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-21 16:49:50.875  5740  5788 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-21 16:49:50.876  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-21 16:49:50.876  5740  5788 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-21 16:49:50.876  5740  5788 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-21 16:49:50.876  5740  5788 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-21 16:49:50.876  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-21 16:49:50.876  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.876  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.876  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.876  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:49:50.876  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-21 16:49:50.876  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:49:50.876  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:49:50.877  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:49:50.878  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:49:50.878  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:49:50.878  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:49:50.878  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:49:50.878  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 16:49:50.878  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:49:50.878  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:49:50.878  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:49:50.878  5740  5816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:49:50.880  5740  5816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:49:50.880  4921  4921 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32482]" dev="sockfs" ino=32482 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:50.880  4921  4921 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[32482]" dev="sockfs" ino=32482 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:50.885  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:49:50.885  5740  5788 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:49:50.885  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 16:49:50.889  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.890  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:49:50.890  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-21 16:49:50.890  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:49:50.890  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
11-21 16:49:50.890  5740  5816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-21 16:49:50.892  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.893  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.893  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:49:50.893  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:49:50.893  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:49:50.893  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-21 16:49:50.893  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:50.893  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:50.893  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.893  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:49:50.893  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:49:50.893  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.893  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.893  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.894  5740  5788 D BluetoothAdapter: STATE_ON
,11-21 16:49:50.897  4689  4706 D BtGatt.GattService: registerClient() - UUID=91408b79-6ae2-4f22-8948-17f13109142a
11-21 16:49:50.897  4689  4761 D BtGatt.GattService: onClientRegistered() - UUID=91408b79-6ae2-4f22-8948-17f13109142a, clientIf=5
,11-21 16:49:50.898  5740  5751 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-21 16:49:50.898  4689  4765 D BtGatt.AdvertiseManager: message : 0
,11-21 16:49:50.901  4689  4765 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:49:50.910  4689  4761 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:49:50.916  4689  4761 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:49:50.917  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.917  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.917  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:49:50.917  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.917  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.917  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.917  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:50.917  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.917  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-21 16:49:50.919  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:49:50.919  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.920  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.920  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.920  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:50.920  5740  5788 I io.jxcore.node.ConnectionHelper: start: OK
11-21 16:49:50.920  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:49:50.921  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.921  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-21 16:49:50.921  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:49:50.921  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.921  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.921  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:50.921  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.921  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:49:50.921  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:49:50.921  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.922  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-21 16:49:50.922  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-21 16:49:50.922  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:49:50.925  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-21 16:49:50.925  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:49:50.925  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.925  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.925  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:49:50.925  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:49:51.422  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 16:49:51.422  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-21 16:49:51.422  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:49:51.423  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-21 16:49:51.423  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-21 16:49:51.423  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-21 16:49:51.423  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:49:51.424  5740  5816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-21 16:49:51.424  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 16:49:51.424  5740  5816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:49:51.424  5740  5816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:49:51.424  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-21 16:49:51.424  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-21 16:49:51.424  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:49:51.425  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:49:51.426  5740  5740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 16:49:51.430  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4b9c42 removed from the list
11-21 16:49:51.430  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-21 16:49:51.430  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-21 16:49:51.430  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:49:51.430  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:49:51.431  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.431  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:51.431  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.431  5740  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 134
11-21 16:49:51.432  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.432  5740  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-21 16:49:51.432  5740  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 134)
11-21 16:49:51.433  5740  5815 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
,11-21 16:49:51.433  5740  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 134)
11-21 16:49:51.433  5740  5815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-21 16:49:51.433  4689  4907 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-21 16:49:51.433  5740  5815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 134)
11-21 16:49:51.433  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:49:51.434  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-21 16:49:51.435  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:49:51.436  5740  5788 D BluetoothLeScanner: could not find callback wrapper
11-21 16:49:51.436  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:49:51.436  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.437  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.437  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.437  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:49:51.437  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.439  4689  4765 D BtGatt.AdvertiseManager: message : 1
11-21 16:49:51.441  4689  4765 D BtGatt.AdvertiseManager: stop advertise for client 5
11-21 16:49:51.449  4689  4761 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-21 16:49:51.449  4689  4761 D BtGatt.GattService: Client app is not null!
,11-21 16:49:51.450  4689  4921 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:49:51.451  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-21 16:49:51.452  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.452  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:49:51.452  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:51.452  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.452  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.452  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:49:51.452  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-21 16:49:51.453  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:49:51.454  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:51.455  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.455  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:49:51.455  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.455  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:51.456  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:49:51.456  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d9d453 removed from the list
11-21 16:49:51.456  5740  5788 D io.jxcore.node.ConnectivityMonitor: stop
11-21 16:49:51.456  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:49:51.456  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 16:49:51.456  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:49:51.456  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 16:49:51.456  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:49:51.456  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-21 16:49:51.456  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:49:51.456  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:49:51.456  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:49:51.456  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:49:51.458  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:49:51.458  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:51.458  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:49:51.458  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:49:51.459  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:49:51.960  5740  5740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 16:49:56.001  4689  4892 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-21 16:49:56.001  4689  4892 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-21 16:49:56.460  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
11-21 16:49:56.464  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-21 16:49:56.464  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:49:56.465  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-21 16:49:56.472  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 16:49:56.473  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:49:56.473  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:49:56.473  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 16:49:56.473  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:49:56.474  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-21 16:49:56.474  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:49:56.474  5740  5818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:49:56.476  5740  5818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:49:56.478  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,11-21 16:49:56.480  5740  5788 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-21 16:49:56.480  5740  5788 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-21 16:49:56.480  4706  4706 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[33299]" dev="sockfs" ino=33299 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:49:56.480  4706  4706 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[33299]" dev="sockfs" ino=33299 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:49:56.481  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-21 16:49:56.481  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:49:56.481  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-21 16:49:56.482  5740  5818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:49:56.483  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-21 16:49:56.491  5740  5788 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-21 16:49:56.492  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 16:49:56.492  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:49:56.492  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:49:56.492  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-21 16:49:56.492  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 16:49:56.492  5740  5818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:49:56.493  5740  5818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:49:56.493  5740  5818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:49:56.493  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:49:56.494  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 16:49:56.494  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:49:56.494  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:49:56.494  5740  5788 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4b9c42 not in the list
11-21 16:49:56.494  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 16:49:56.494  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:49:56.494  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:49:56.495  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:49:56.495  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:49:56.495  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:49:56.496  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:56.497  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:49:56.497  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:56.497  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:49:56.497  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:49:56.497  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:49:56.497  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-21 16:49:56.497  5740  5788 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d9d453 not in the list
,11-21 16:49:56.498  5740  5788 D io.jxcore.node.ConnectivityMonitor: stop
11-21 16:49:56.499  5740  5788 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
11-21 16:49:56.499  5740  5788 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-21 16:49:56.499  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 16:49:56.500  5740  5788 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-21 16:49:56.500  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-21 16:49:56.500  5740  5788 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-21 16:49:56.500  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-21 16:49:56.500  5740  5788 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-21 16:49:56.501  5740  5788 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,11-21 16:49:56.503  5740  5788 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,11-21 16:49:56.503  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-21 16:49:56.503  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-21 16:49:56.503  5740  5788 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-21 16:49:56.504  5740  5788 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-21 16:49:56.504  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 16:49:56.504  5740  5788 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-21 16:49:56.504  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-21 16:49:56.504  5740  5788 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,11-21 16:49:56.504  5740  5788 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-21 16:49:56.505  5740  5788 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-21 16:49:56.505  5740  5788 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-21 16:49:56.505  5740  5788 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-21 16:49:56.505  5740  5788 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-21 16:49:56.505  5740  5788 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-21 16:49:56.505  5740  5788 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-21 16:49:56.505  5740  5788 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-21 16:49:56.506  5740  5788 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-21 16:49:56.506  5740  5788 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-21 16:49:56.506  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-21 16:49:56.506  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1bb7f9 added. We now have 3 listener(s)
11-21 16:49:56.508  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:49:56.508  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:49:56.508  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 16:49:56.508  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:49:56.508  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71633e added. We now have 3 listener(s)
11-21 16:49:56.508  5740  5788 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-21 16:49:56.509  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:49:56.512  5740  5788 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 16:49:56.512   934  3877 D WifiService: setWifiEnabled: true pid=5740, uid=10077
11-21 16:49:56.512   934  3877 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:49:56.514  5740  5788 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-21 16:49:56.518  5740  5788 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-21 16:49:56.519  5740  5788 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
11-21 16:49:56.519  5740  5788 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-21 16:49:56.525  4689  4757 D BluetoothAdapterState: Current state: ON, message: 23
11-21 16:49:56.525  4689  4757 D BluetoothAdapterProperties: Setting state to 13
11-21 16:49:56.525  4689  4757 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-21 16:49:56.526  4689  4757 D BluetoothAdapterProperties: onBluetoothDisable()
11-21 16:49:56.526  5740  5788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:49:56.526  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:49:56.526  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:49:56.526  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:49:56.526  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:49:56.526  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:49:56.526  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:49:56.526  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:49:56.526  5740  5788 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 16:49:56.527  4689  4757 I BluetoothAdapterState: Entering PendingCommandState
11-21 16:49:56.528  5740  5788 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-21 16:49:56.528  5740  5788 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:49:56.528  4689  4689 D BluetoothMapService: onReceive
,11-21 16:49:56.529  4689  4689 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 16:49:56.529  4689  4689 D BluetoothMapService: STATE_TURNING_OFF
11-21 16:49:56.530  4689  4689 D BluetoothMapService: MAP Service closeService in
11-21 16:49:56.530  4689  4689 D BluetoothMapMasInstance0: MAP Service shutdown
11-21 16:49:56.531  4689  4689 D ObexServerSockets0: shutdown(block = true)
11-21 16:49:56.531  4689  4922 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-21 16:49:56.531  4689  4689 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 16:49:56.532  4689  4689 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-21 16:49:56.532  4689  4923 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-21 16:49:56.532  4689  4907 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-21 16:49:56.534  4689  4689 I BtOppRfcommListener: stopping Accept Thread
11-21 16:49:56.534  4689  5351 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-21 16:49:56.534  4689  5351 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-21 16:49:56.542   934   947 I ActivityManager: Start proc 5821:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-21 16:49:56.549  4689  4761 D BluetoothAdapterProperties: Scan Mode:20
11-21 16:49:56.549  4689  4757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-21 16:49:56.551  4689  4689 D HeadsetService: Received stop request...Stopping profile...
11-21 16:49:56.555  3166  3178 D BluetoothHeadset: Proxy object disconnected
11-21 16:49:56.555   934   934 D BluetoothHeadset: Proxy object disconnected
,11-21 16:49:56.556  3832  3862 D BluetoothHeadset: Proxy object disconnected
11-21 16:49:56.556   934   934 D BluetoothHeadset: Proxy object disconnected
11-21 16:49:56.556   934   934 D BluetoothHeadset: Proxy object disconnected
,11-21 16:49:56.557  4689  4689 D A2dpService: Received stop request...Stopping profile...
11-21 16:49:56.557  4689  4912 D A2dpStateMachine: Exit Disconnected: -1
11-21 16:49:56.559  3166  3166 D HeadsetProfile: Bluetooth service disconnected
11-21 16:49:56.559   934   934 D BluetoothA2dp: Proxy object disconnected
11-21 16:49:56.559  3166  3166 D BluetoothA2dp: Proxy object disconnected
11-21 16:49:56.560  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-21 16:49:56.560  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-21 16:49:56.560  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:56.560  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:56.561  4689  4689 D HidService: Received stop request...Stopping profile...
11-21 16:49:56.561  4689  4689 D HidService: Stopping Bluetooth HidService
11-21 16:49:56.562  3166  3166 D BluetoothInputDevice: Proxy object disconnected
11-21 16:49:56.562  3166  3166 D HidProfile: Bluetooth service disconnected
,11-21 16:49:56.563  4689  4689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-21 16:49:56.563  4689  4689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-21 16:49:56.563  4689  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:49:56.563  4689  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 16:49:56.563  4689  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 16:49:56.564  4689  4689 D HealthService: Received stop request...Stopping profile...
11-21 16:49:56.564  4689  4761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-21 16:49:56.564  4689  4761 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-21 16:49:56.565  4689  4689 D PanService: Received stop request...Stopping profile...
,11-21 16:49:56.565  3166  3166 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-21 16:49:56.566  3166  3166 D PanProfile: Bluetooth service disconnected
11-21 16:49:56.566  4689  4689 D BluetoothMapService: Received stop request...Stopping profile...
11-21 16:49:56.566  4689  4689 D BluetoothMapService: stop()
11-21 16:49:56.567  4689  4689 D BluetoothMapAppObserver: deinitObservers()
,11-21 16:49:56.567  4689  4689 D BluetoothMapAppObserver: removeReceiver()
,11-21 16:49:56.569  3166  3166 D BluetoothMap: Proxy object disconnected
,11-21 16:49:56.569  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-21 16:49:56.569  3166  3166 D MapProfile: Bluetooth service disconnected
11-21 16:49:56.569  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-21 16:49:56.569  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:56.570  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 16:49:56.571  4689  4761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-21 16:49:56.571  4689  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:49:56.571  4689  4689 D SapService: Received stop request...Stopping profile...
11-21 16:49:56.571  4689  4689 V SapService: stop()
11-21 16:49:56.571  4689  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-21 16:49:56.571  4689  4892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-21 16:49:56.572  4689  4892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-21 16:49:56.572  4689  4892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-21 16:49:56.572  4689  4892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-21 16:49:56.575  4689  4689 V BluetoothAdapterState: isTurningOff()=true
,11-21 16:49:56.575  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-21 16:49:56.575  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:56.575  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:56.575  4689  4689 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-21 16:49:56.575  4689  4761 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-21 16:49:56.576  4689  4689 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-21 16:49:56.576  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-21 16:49:56.576  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-21 16:49:56.576  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:56.576  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:56.576  4689  4689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-21 16:49:56.577  4689  4761 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-21 16:49:56.577  4689  4689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-21 16:49:56.577  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-21 16:49:56.577  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-21 16:49:56.577  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:56.578  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:56.578  4689  4689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-21 16:49:56.578  4689  4689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-21 16:49:56.579  4689  4689 D BluetoothMapService: MAP Service closeService in
11-21 16:49:56.579  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-21 16:49:56.579  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-21 16:49:56.579  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:56.580  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:56.580  4689  4689 D BluetoothMapService: cleanup()
11-21 16:49:56.580  4689  4689 D BluetoothMapService: MAP Service closeService in
11-21 16:49:56.580  4689  4689 V BluetoothAdapterState: isTurningOff()=true
,11-21 16:49:56.580  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-21 16:49:56.580  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:56.580  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:56.581  4689  4757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-21 16:49:56.581  4689  4757 D BluetoothAdapterProperties: Setting state to 15
11-21 16:49:56.581  4689  4757 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-21 16:49:56.581  4689  4757 I BluetoothAdapterState: Entering BleOnState
11-21 16:49:56.583  3166  3983 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-21 16:49:56.584  3166  3187 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-21 16:49:56.585  3166  3178 D BluetoothMap: onBluetoothStateChange: up=false
11-21 16:49:56.585   934   951 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:49:56.586  3166  3983 D BluetoothPbap: onBluetoothStateChange: up=false
11-21 16:49:56.587  3832  3858 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:49:56.587   934   951 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:49:56.588  3166  3187 D BluetoothPan: onBluetoothStateChange on: false
,11-21 16:49:56.588  3166  3178 D BluetoothHeadset: onBluetoothStateChange: up=false
11-21 16:49:56.588   934   951 D BluetoothA2dp: onBluetoothStateChange: up=false
11-21 16:49:56.589   934   951 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-21 16:49:56.589  4689  4757 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-21 16:49:56.589  4689  4757 D BluetoothAdapterProperties: Setting state to 16
11-21 16:49:56.589  4689  4757 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-21 16:49:56.590  4689  4757 D BluetoothAdapterProperties: onBleDisable
11-21 16:49:56.590  4689  4757 I BluetoothAdapterState: Entering PendingCommandState
11-21 16:49:56.590  4689  4758 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-21 16:49:56.591  4689  4761 D BluetoothAdapterProperties: Scan Mode:20
11-21 16:49:56.591  4689  4892 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-21 16:49:56.592  4689  4892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-21 16:49:56.600  5821  5821 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-21 16:49:56.615  5821  5821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 16:49:56.621   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b757659:true
,11-21 16:49:56.622  3626  3626 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-21 16:49:56.635   934  3467 I ActivityManager: Start proc 5833:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-21 16:49:56.646  5821  5821 D LocalBluetoothProfileManager: Adding local MAP profile
,11-21 16:49:56.649  5821  5821 D BluetoothMap: Create BluetoothMap proxy object
,11-21 16:49:56.659  5821  5821 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-21 16:49:56.671  5833  5833 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-21 16:49:56.675  5821  5821 D DockEventReceiver: finishStartingService: stopping service
,11-21 16:49:56.683   934   944 I ActivityManager: Killing 5450:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-21 16:49:56.796  4689  4761 I bt_hci  : shut_down
,11-21 16:49:56.800  4689  4767 D bt_hwcfg: hw_epilog_process
,11-21 16:49:56.801  4689  4767 I bt_vendor: low_power_mode_cb
,11-21 16:49:56.803  4689  4767 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-21 16:49:56.803  4689  4767 I bt_vendor: epilog_cb
11-21 16:49:56.803  4689  4767 I bt_hci  : epilog_finished_callback
11-21 16:49:56.805  4689  4761 I bt_hci_h4: hal_close
11-21 16:49:56.806  4689  4761 I bt_userial_vendor: device fd = 54 close
,11-21 16:49:56.904  5833  5833 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-21 16:49:56.904  5833  5833 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:49:56.904  5833  5833 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:49:56.904  5833  5833 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.e.b(PG:170)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:49:56.904  5833  5833 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.k.d(PG:583)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.e.b(PG:170)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:49:56.904  5833  5833 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:49:56.904  5833  5833 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.io.File.exists(File.java:361)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:49:56.904  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:49:56.905  5833  5833 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-21 16:49:56.905  5833  5833 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-21 16:49:56.905  5833  5833 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-21 16:49:56.909  5821  5821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-21 16:49:56.912  4689  4758 D bt_stack_manager: event_shut_down_stack finished.
11-21 16:49:56.913  4689  4757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-21 16:49:56.915  3626  3626 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 16:49:56.915  4689  4757 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-21 16:49:56.916  4689  4689 D BtGatt.DebugUtils: handleDebugAction() action=null
11-21 16:49:56.917  4689  4689 D BtGatt.GattService: Received stop request...Stopping profile...
11-21 16:49:56.917  4689  4689 D BtGatt.GattService: stop()
11-21 16:49:56.917  4689  4689 D BtGatt.AdvertiseManager: advertise clients cleared
11-21 16:49:56.917  5821  5821 D DockEventReceiver: finishStartingService: stopping service
11-21 16:49:56.919  4689  4689 V BluetoothAdapterState: isTurningOff()=false
11-21 16:49:56.919  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-21 16:49:56.919  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:56.919  4689  4689 V BluetoothAdapterState: isBleTurningOff()=true
11-21 16:49:56.919   934  3859 I ActivityManager: Killing 5462:com.android.chrome/u0a39 (adj 15): empty #17
11-21 16:49:56.919  4689  4757 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-21 16:49:56.919  4689  4757 D BluetoothAdapterProperties: Setting state to 10
11-21 16:49:56.919  4689  4757 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-21 16:49:56.920  4689  4757 I BluetoothAdapterState: Entering OffState
11-21 16:49:56.921   934   951 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-21 16:49:56.956  4689  4689 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-21 16:49:56.956  4689  4689 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-21 16:49:56.956  4689  4689 I BluetoothServiceJni: cleanupNative: return from cleanup
11-21 16:49:56.956  4689  4758 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-21 16:49:56.958  4689  4689 I art     : System.exit called, status: 0
11-21 16:49:56.958  4689  4689 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-21 16:49:56.987   934   944 I ActivityManager: Process com.android.bluetooth (pid 4689) has died
,11-21 16:49:56.999  5740  5740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 16:49:57.027  5740  5819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-21 16:49:57.027  5740  5819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:49:57.027  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:49:57.027  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:49:57.027  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:49:57.027  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-21 16:49:57.027  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:49:57.027  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:49:57.027  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:49:57.027  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-21 16:49:57.027  5740  5819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-21 16:49:57.027  5740  5819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:49:57.030  5740  5788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:49:57.040   934   951 I ActivityManager: Start proc 5865:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-21 16:49:57.071  5833  5853 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-21 16:49:57.081   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ab8f9a6:true
,11-21 16:49:57.096  5865  5865 D AdapterServiceConfig: Adding HeadsetService
,11-21 16:49:57.097  5865  5865 D AdapterServiceConfig: Adding A2dpService
11-21 16:49:57.097  5865  5865 D AdapterServiceConfig: Adding HidService
11-21 16:49:57.097  5865  5865 D AdapterServiceConfig: Adding HealthService
11-21 16:49:57.097  5865  5865 D AdapterServiceConfig: Adding PanService
11-21 16:49:57.097  5865  5865 D AdapterServiceConfig: Adding GattService
11-21 16:49:57.097  5865  5865 D AdapterServiceConfig: Adding BluetoothMapService
,11-21 16:49:57.098  5865  5865 D AdapterServiceConfig: Adding SapService
,11-21 16:49:57.105   934   951 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@77c14df:true
,11-21 16:49:57.105  5865  5865 D BluetoothAdapterState: make() - Creating AdapterState
,11-21 16:49:57.106  5865  5865 I bt_bluedroid: init
,11-21 16:49:57.107  5865  5879 I BluetoothAdapterState: Entering OffState
,11-21 16:49:57.108  5865  5880 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-21 16:49:57.108  5865  5880 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-21 16:49:57.108  5865  5880 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-21 16:49:57.109  5865  5880 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-21 16:49:57.109  5865  5865 I bt_bluedroid: get_profile_interface socket
,11-21 16:49:57.110  5865  5865 I bt_bluedroid: get_profile_interface sdp
,11-21 16:49:57.111  5865  5883 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-21 16:49:57.112  5865  5883 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-21 16:49:57.113  5865  5876 I bt_bluedroid: config_hci_snoop_log
,11-21 16:49:57.114   934   951 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-21 16:49:57.118  5865  5879 D BluetoothAdapterState: Current state: OFF, message: 0
,11-21 16:49:57.118  5865  5879 D BluetoothAdapterProperties: Setting state to 14
11-21 16:49:57.118  5865  5879 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-21 16:49:57.119  5865  5879 D BluetoothBondStateMachine: make
11-21 16:49:57.120  5865  5884 I BluetoothBondStateMachine: StableState(): Entering Off State
11-21 16:49:57.122  5865  5879 I BluetoothAdapterState: Entering PendingCommandState
,11-21 16:49:57.123  5865  5865 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-21 16:49:57.124  5865  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
,11-21 16:49:57.124  5865  5865 D BtGatt.DebugUtils: handleDebugAction() action=null
11-21 16:49:57.125  5865  5865 D BtGatt.GattService: Received start request. Starting profile...
11-21 16:49:57.125  5865  5865 D BtGatt.GattService: start()
11-21 16:49:57.125  5865  5865 I bt_bluedroid: get_profile_interface gatt
,11-21 16:49:57.125  5865  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
11-21 16:49:57.126  5865  5865 D BtGatt.AdvertiseManager: advertise manager created
,11-21 16:49:57.129  5865  5865 V BluetoothAdapterState: isTurningOff()=false
,11-21 16:49:57.129  5865  5865 V BluetoothAdapterState: isTurningOn()=false
11-21 16:49:57.129  5865  5865 V BluetoothAdapterState: isBleTurningOn()=true
11-21 16:49:57.129  5865  5865 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 16:49:57.129  5865  5879 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-21 16:49:57.130  5865  5879 I bt_bluedroid: bt_bluedroid
11-21 16:49:57.130  5865  5880 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-21 16:49:57.131  5865  5880 I bt_hci  : start_up
,11-21 16:49:57.135  5865  5880 I bt_vendor: alloc value 0xf420b871
,11-21 16:49:57.135  5865  5880 I bt_vendor: init
11-21 16:49:57.135  5865  5880 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-21 16:49:57.135  5865  5880 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-21 16:49:57.246  5865  5880 D bt_hci  : start_up starting async portion
,11-21 16:49:57.246  5865  5887 I bt_hci  : event_finish_startup
,11-21 16:49:57.246  5865  5887 I bt_hci_h4: hal_open
,11-21 16:49:57.246  5865  5887 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-21 16:49:57.248  5865  5887 I bt_userial_vendor: device fd = 54 open
11-21 16:49:57.244  5888  5888 W irq/448-msm_hs_: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:49:57.260  5865  5887 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-21 16:49:57.262  5865  5887 D bt_hwcfg: Chipset BCM4358A3
,11-21 16:49:57.262  5865  5887 D bt_hwcfg: Target name = [BCM4358A3]
11-21 16:49:57.263  5865  5887 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-21 16:49:57.536  5865  5879 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-21 16:49:57.647  5865  5887 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-21 16:49:57.648  5865  5887 D bt_hwcfg: Settlement delay -- 100 ms
11-21 16:49:57.648  5865  5887 I bt_hwcfg: Setting fw settlement delay to 100 
,11-21 16:49:57.771  5865  5887 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-21 16:49:57.771  5865  5887 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-21 16:49:57.773  5865  5887 I bt_hwcfg: vendor lib fwcfg completed
11-21 16:49:57.773  5865  5887 I bt_vendor: firmware callback
11-21 16:49:57.773  5865  5887 I bt_hci  : firmware_config_callback
,11-21 16:49:57.781  5865  5890 I bt_btu  : btu_task pending for preload complete event
,11-21 16:49:57.782  5865  5890 I bt_btu_task: Bluetooth chip preload is complete
11-21 16:49:57.782  5865  5890 I bt_btu  : btu_task received preload complete event
,11-21 16:49:57.789  5865  5890 I         : BTE_InitTraceLevels -- TRC_HCI
,11-21 16:49:57.789  5865  5890 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-21 16:49:57.789  5865  5890 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-21 16:49:57.789  5865  5890 I         : BTE_InitTraceLevels -- TRC_AVDT
11-21 16:49:57.789  5865  5890 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-21 16:49:57.789  5865  5890 I         : BTE_InitTraceLevels -- TRC_A2D
11-21 16:49:57.789  5865  5890 I         : BTE_InitTraceLevels -- TRC_BNEP
11-21 16:49:57.789  5865  5890 I         : BTE_InitTraceLevels -- TRC_BTM
11-21 16:49:57.790  5865  5890 I         : BTE_InitTraceLevels -- TRC_GAP
,11-21 16:49:57.790  5865  5890 I         : BTE_InitTraceLevels -- TRC_PAN
11-21 16:49:57.790  5865  5890 I         : BTE_InitTraceLevels -- TRC_SDP
11-21 16:49:57.790  5865  5890 I         : BTE_InitTraceLevels -- TRC_GATT
11-21 16:49:57.790  5865  5890 I         : BTE_InitTraceLevels -- TRC_SMP
11-21 16:49:57.790  5865  5890 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-21 16:49:57.790  5865  5890 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-21 16:49:57.877  5865  5890 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4189549
,11-21 16:49:57.877  5865  5890 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4189549 
,11-21 16:49:57.897  5865  5883 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-21 16:49:57.899  5865  5883 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-21 16:49:57.899  5865  5883 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-21 16:49:57.902  5865  5883 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-21 16:49:57.905  5865  5883 D BluetoothAdapterProperties: Scan Mode:20
,11-21 16:49:57.905  5865  5883 D BluetoothAdapterProperties: Discoverable Timeout:120
11-21 16:49:57.905  5865  5883 D bt_hci  : do_postload posting postload work item
,11-21 16:49:57.905  5865  5887 I bt_hci  : event_postload
,11-21 16:49:57.905  5865  5887 I bt_vendor: sco_config_cb
11-21 16:49:57.905  5865  5887 I bt_hci  : sco_config_callback postload finished.
11-21 16:49:57.908  5865  5883 D bt_bte_conf: Device ID record 1 : primary
11-21 16:49:57.908  5865  5883 D bt_bte_conf:   vendorId            = 000f
11-21 16:49:57.909  5865  5883 D bt_bte_conf:   vendorIdSource      = 0001
11-21 16:49:57.909  5865  5883 D bt_bte_conf:   product             = 1200
,11-21 16:49:57.909  5865  5883 D bt_bte_conf:   version             = 1436
11-21 16:49:57.909  5865  5883 D bt_bte_conf:   clientExecutableURL = 
,11-21 16:49:57.909  5865  5883 D bt_bte_conf:   serviceDescription  = 
11-21 16:49:57.909  5865  5883 D bt_bte_conf:   documentationURL    = 
11-21 16:49:57.909  5865  5883 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-21 16:49:57.909  5865  5880 D bt_stack_manager: event_start_up_stack finished
11-21 16:49:57.910  5865  5879 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-21 16:49:57.910  5865  5879 D BluetoothAdapterProperties: Setting state to 15
11-21 16:49:57.910  5865  5879 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-21 16:49:57.912  5865  5879 I BluetoothAdapterState: Entering BleOnState
,11-21 16:49:57.915  5865  5887 I bt_vendor: low_power_mode_cb
,11-21 16:49:57.918  5865  5879 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-21 16:49:57.918  5865  5879 D BluetoothAdapterProperties: Setting state to 11
11-21 16:49:57.918  5865  5879 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-21 16:49:57.924  5865  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
,11-21 16:49:57.925  5865  5865 D HeadsetService: Received start request. Starting profile...
11-21 16:49:57.928  5865  5865 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-21 16:49:57.929  5865  5865 D HeadsetStateMachine: make
,11-21 16:49:57.934  5865  5879 I BluetoothAdapterState: Entering PendingCommandState
,11-21 16:49:57.937  5865  5865 D HeadsetStateMachine: max_hf_connections = 1
11-21 16:49:57.938  5865  5865 I bt_bluedroid: get_profile_interface handsfree
11-21 16:49:57.938  5865  5883 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-21 16:49:57.938  5865  5883 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-21 16:49:57.941  5865  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
11-21 16:49:57.942  5865  5865 D A2dpService: Received start request. Starting profile...
11-21 16:49:57.943  5865  5865 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-21 16:49:57.943  5865  5865 I bt_bluedroid: get_profile_interface avrcp
11-21 16:49:57.949  5865  5865 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-21 16:49:57.949  5865  5865 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-21 16:49:57.949  5865  5865 D A2dpStateMachine: make
11-21 16:49:57.950  5865  5865 I bt_bluedroid: get_profile_interface a2dp
11-21 16:49:57.951  5865  5883 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-21 16:49:57.953  5865  5898 D A2dpStateMachine: Enter Disconnected: -2
11-21 16:49:57.954  5865  5865 I BluetoothHidServiceJni: classInitNative: succeeds
11-21 16:49:57.955  5865  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
11-21 16:49:57.955  3626  3626 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 16:49:57.957  5821  5821 D BluetoothInputDevice: Proxy object connected
11-21 16:49:57.957  5865  5865 D HidService: Received start request. Starting profile...
11-21 16:49:57.957  5865  5865 I bt_bluedroid: get_profile_interface hidhost
11-21 16:49:57.958  5865  5865 D HidService: setHidService(): set to: null
11-21 16:49:57.958  5865  5883 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf416a56d
11-21 16:49:57.958  5821  5821 D HidProfile: Bluetooth service connected
11-21 16:49:57.958  5865  5883 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-21 16:49:57.958  5865  5865 I BluetoothHealthServiceJni: classInitNative: succeeds
11-21 16:49:57.959  5865  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
11-21 16:49:57.959  5865  5865 D HealthService: Received start request. Starting profile...
11-21 16:49:57.961  5865  5865 I bt_bluedroid: get_profile_interface health
11-21 16:49:57.962  5865  5865 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-21 16:49:57.962  5865  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
11-21 16:49:57.963  5821  5821 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 16:49:57.964  5821  5821 D PanProfile: Bluetooth service connected
11-21 16:49:57.964  5865  5865 D PanService: Received start request. Starting profile...
11-21 16:49:57.964  5865  5865 D BluetoothPanServiceJni: initializeNative(L110): pan
11-21 16:49:57.965  5865  5865 I bt_bluedroid: get_profile_interface pan
11-21 16:49:57.965  5865  5883 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-21 16:49:57.967  5865  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
11-21 16:49:57.968  5865  5865 D BluetoothMapService: Received start request. Starting profile...
11-21 16:49:57.968  5865  5865 D BluetoothMapService: start()
,11-21 16:49:57.970  5865  5865 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-21 16:49:57.971  5865  5865 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-21 16:49:57.971  5865  5865 D BluetoothMapAppObserver: createReceiver()
11-21 16:49:57.972  5865  5865 D BluetoothMapAppObserver: initObservers()
11-21 16:49:57.972  5865  5865 D BluetoothMapAppObserver: getEnabledAccountItems()
11-21 16:49:57.977  5821  5821 D BluetoothMap: Proxy object connected
11-21 16:49:57.978  5821  5821 D MapProfile: Bluetooth service connected
,11-21 16:49:57.978  5821  5821 D BluetoothMap: getConnectedDevices()
11-21 16:49:57.978  5865  5865 V SapService: SapBinder()
,11-21 16:49:57.978  5865  5865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
11-21 16:49:57.979  5821  5821 D BluetoothMap: Bluetooth is Not enabled
11-21 16:49:57.979  5865  5865 D SapService: Received start request. Starting profile...
11-21 16:49:57.979  5865  5865 V SapService: start()
,11-21 16:49:57.982  5865  5865 V BluetoothAdapterState: isTurningOff()=false
,11-21 16:49:57.982  5865  5865 V BluetoothAdapterState: isTurningOn()=true
11-21 16:49:57.982  5865  5896 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-21 16:49:57.982  5865  5865 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:57.982  5865  5865 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:57.983  5865  5865 V BluetoothAdapterState: isTurningOff()=false
11-21 16:49:57.983  5865  5865 V BluetoothAdapterState: isTurningOn()=true
11-21 16:49:57.983  5865  5865 V BluetoothAdapterState: isBleTurningOn()=false
,11-21 16:49:57.983  5865  5865 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:57.984  5865  5865 V BluetoothAdapterState: isTurningOff()=false
11-21 16:49:57.984  5865  5865 V BluetoothAdapterState: isTurningOn()=true
11-21 16:49:57.984  5865  5865 V BluetoothAdapterState: isBleTurningOn()=false
,11-21 16:49:57.984  5865  5865 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:57.984  5865  5865 V BluetoothAdapterState: isTurningOff()=false
11-21 16:49:57.984  5865  5865 V BluetoothAdapterState: isTurningOn()=true
11-21 16:49:57.984  5865  5865 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:57.984  5865  5865 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:57.984  5865  5865 V BluetoothAdapterState: isTurningOff()=false
11-21 16:49:57.985  5865  5865 V BluetoothAdapterState: isTurningOn()=true
11-21 16:49:57.985  5865  5865 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:57.985  5865  5865 V BluetoothAdapterState: isBleTurningOff()=false
11-21 16:49:57.985  5865  5865 V BluetoothAdapterState: isTurningOff()=false
11-21 16:49:57.985  5865  5865 V BluetoothAdapterState: isTurningOn()=true
11-21 16:49:57.985  5865  5865 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:57.985  5865  5865 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 16:49:57.986  5865  5865 V BluetoothAdapterState: isTurningOff()=false
11-21 16:49:57.986  5865  5865 V BluetoothAdapterState: isTurningOn()=true
11-21 16:49:57.986  5865  5865 V BluetoothAdapterState: isBleTurningOn()=false
11-21 16:49:57.986  5865  5865 V BluetoothAdapterState: isBleTurningOff()=false
,11-21 16:49:57.986  5865  5879 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-21 16:49:57.986  5865  5879 D BluetoothAdapterProperties: ScanMode =  20
11-21 16:49:57.986  5865  5879 D BluetoothAdapterProperties: State =  11
11-21 16:49:57.987  5865  5879 D BluetoothAdapterProperties: Setting state to 12
11-21 16:49:57.987  5865  5879 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-21 16:49:57.987  5865  5879 I BluetoothAdapterState: Entering OnState
11-21 16:49:57.987  3166  3178 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-21 16:49:57.989  3166  3983 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 16:49:57.989  3166  3166 D BluetoothInputDevice: Proxy object connected
11-21 16:49:57.989  3166  3166 D HidProfile: Bluetooth service connected
11-21 16:49:57.990  5865  5883 D BluetoothAdapterProperties: Scan Mode:21
11-21 16:49:57.991  5865  5883 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-21 16:49:57.992  3166  3178 D BluetoothMap: onBluetoothStateChange: up=true
11-21 16:49:57.993  3166  3166 D BluetoothA2dp: Proxy object connected
11-21 16:49:57.993   934   951 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-21 16:49:57.993  5821  5832 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-21 16:49:57.994  3166  3187 D BluetoothPbap: onBluetoothStateChange: up=true
11-21 16:49:57.995  5821  5831 D BluetoothMap: onBluetoothStateChange: up=true
11-21 16:49:57.996  3832  3862 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:49:57.996   934   951 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:49:57.996  5821  5832 D BluetoothPan: onBluetoothStateChange on: true
11-21 16:49:57.996  5821  5831 D BluetoothPbap: onBluetoothStateChange: up=true
,11-21 16:49:57.997  5865  5865 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-21 16:49:57.998  3166  3178 D BluetoothPan: onBluetoothStateChange on: true
11-21 16:49:57.998  5865  5865 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-21 16:49:57.998  3166  3166 D BluetoothMap: Proxy object connected
11-21 16:49:57.998  3166  3166 D MapProfile: Bluetooth service connected
11-21 16:49:57.998  3166  3166 D BluetoothMap: getConnectedDevices()
11-21 16:49:57.999  3166  3187 D BluetoothHeadset: onBluetoothStateChange: up=true
11-21 16:49:58.000  5865  5865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:49:58.000   934   951 D BluetoothA2dp: onBluetoothStateChange: up=true
11-21 16:49:58.000   934   934 D BluetoothA2dp: Proxy object connected
,11-21 16:49:58.000   934   951 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-21 16:49:58.001  3166  3166 D BluetoothPan: BluetoothPAN Proxy object connected
11-21 16:49:58.001  3166  3166 D PanProfile: Bluetooth service connected
11-21 16:49:58.004  5865  5865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:49:58.004   934   934 I Telecom : BluetoothPhoneService: queryPhoneState
11-21 16:49:58.005  5821  5821 D LocalBluetoothProfileManager: Adding local A2DP profile
11-21 16:49:58.007  5865  5865 D ObexServerSockets: Succeed to create listening sockets 
11-21 16:49:58.007  5865  5865 D ObexServerSockets0: startAccept()
11-21 16:49:58.007  5865  5865 D ObexServerSockets0: prepareForNewConnect()
11-21 16:49:58.008  5821  5821 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-21 16:49:58.009  5865  5865 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-21 16:49:58.009  5865  5865 D BluetoothSdpJni: SDP Create record success - handle: 0
11-21 16:49:58.009  5865  5865 D BluetoothMapService: onReceive
,11-21 16:49:58.009  5865  5904 D ObexServerSockets0: Accepting socket connection...
11-21 16:49:58.010  5865  5865 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-21 16:49:58.010  5865  5905 D ObexServerSockets0: Accepting socket connection...
11-21 16:49:58.010  5865  5865 D BluetoothMapService: STATE_ON
11-21 16:49:58.011  5865  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:49:58.013  5865  5906 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-21 16:49:58.013  5865  5906 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-21 16:49:58.015  5821  5821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-21 16:49:58.016  5821  5821 D BluetoothA2dp: Proxy object connected
,11-21 16:49:58.020  3626  3626 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-21 16:49:58.021  5821  5821 D DockEventReceiver: finishStartingService: stopping service
,11-21 16:49:58.027  5821  5821 D BluetoothPbap: Proxy object connected
,11-21 16:49:58.027  5821  5821 D PbapServerProfile: Bluetooth service connected
,11-21 16:49:58.031  3166  3166 D BluetoothPbap: Proxy object connected
11-21 16:49:58.032  3166  3166 D PbapServerProfile: Bluetooth service connected
,11-21 16:49:58.035  5865  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:49:58.041  5740  5819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:49:58.041  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:49:58.041  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:49:58.041  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:49:58.041  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:49:58.041  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-21 16:49:58.041  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-21 16:49:58.041  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-21 16:49:58.041  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-21 16:49:58.044  5740  5819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-21 16:49:58.045  5740  5788 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-21 16:49:58.045  5865  5865 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-21 16:49:58.045  5865  5865 D ObexServerSockets0: prepareForNewConnect()
11-21 16:49:58.046   934  3877 D WifiService: setWifiEnabled: false pid=5740, uid=10077
,11-21 16:49:58.046   934  3877 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 16:49:58.047   934  3022 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-21 16:49:58.047   934  3022 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-21 16:49:58.047  5740  5788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-21 16:49:58.047   934  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 16:49:58.047   934  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 16:49:58.052  5865  5915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:49:58.055  5865  5915 I BtOppRfcommListener: Accept thread started.
,11-21 16:49:58.058   934  5422 D DhcpClient: Clearing IP address
,11-21 16:49:58.058   511   926 D CommandListener: Clearing all IP addresses on wlan0
,11-21 16:49:58.066   511   926 D CommandListener: Setting iface cfg
,11-21 16:49:58.069  3626  5475 V NativeCrypto: Read error: ssl=0x7f97bc5700: I/O error during system call, Connection timed out
,11-21 16:49:58.070  3626  5475 V NativeCrypto: SSL shutdown failed: ssl=0x7f97bc5700: I/O error during system call, Broken pipe
,11-21 16:49:58.072   934  3203 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-21 16:49:58.072   934  5420 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-21 16:49:58.074   934  5420 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-21 16:49:58.074   934  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-21 16:49:58.074   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-21 16:49:58.075   934  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-21 16:49:58.080   934  5423 D DhcpClient: Receive thread stopped
11-21 16:49:58.082   934  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-21 16:49:58.082   934  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-21 16:49:58.086   934   934 D RttService: SCAN_AVAILABLE : 1
11-21 16:49:58.087   537   537 E Parcel  : Reading a NULL string not supported here.
11-21 16:49:58.087   934  3132 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-21 16:49:58.087   934  3024 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-21 16:49:58.088  3794  3935 W QCNEJ   : |CORE| network lost: 100
11-21 16:49:58.089  3794  3935 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-21 16:49:58.096  3166  3983 D BluetoothHeadset: Proxy object connected
11-21 16:49:58.096   934   934 D BluetoothHeadset: Proxy object connected
11-21 16:49:58.096  3832  3858 D BluetoothHeadset: Proxy object connected
11-21 16:49:58.096   934   934 D BluetoothHeadset: Proxy object connected
11-21 16:49:58.096   934   934 D BluetoothHeadset: Proxy object connected
11-21 16:49:58.097  3832  3862 D BluetoothHeadset: Proxy object connected
11-21 16:49:58.097   934  3022 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-21 16:49:58.098   934   951 D BluetoothHeadset: Proxy object connected
11-21 16:49:58.100  3166  3178 D BluetoothHeadset: Proxy object connected
11-21 16:49:58.100   934   951 D BluetoothHeadset: Proxy object connected
,11-21 16:49:58.105   934  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-21 16:49:58.108   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:49:58.111  5821  5831 D BluetoothHeadset: Proxy object connected
,11-21 16:49:58.117  5821  5821 D HeadsetProfile: Bluetooth service connected
11-21 16:49:58.117  3166  3166 D HeadsetProfile: Bluetooth service connected
,11-21 16:49:58.120  3166  3166 D HeadsetProfile: Bluetooth service connected
,11-21 16:49:58.129   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:49:58.129   511   926 D CommandListener: Clearing all IP addresses on wlan0
11-21 16:49:58.130   511   926 D TetherController: Setting IP forward enable = 0
11-21 16:49:58.130   934  3024 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-21 16:49:58.131   934  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-21 16:49:58.132   934   951 D Tethering: MasterInitialState.processMessage what=3
,11-21 16:49:58.135  5307  5307 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b4036fb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-21 16:49:58.139  4023  4023 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-21 16:49:58.141  5094  5117 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 16:49:58.141  5094  5117 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 16:49:58.141  5094  5117 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-21 16:49:58.142  5094  5117 E SarControlService: no key has been found,reset the power
11-21 16:49:58.142  5094  5131 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 16:49:58.142  5094  5131 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 16:49:58.142  5094  5131 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 16:49:58.143  5119  5119 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:49:58.143  5119  5119 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-21 16:49:58.146  3902  3902 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-21 16:49:58.149  5094  5131 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-21 16:49:58.149  5094  5131 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 16:49:58.149  5094  5131 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 16:49:58.150  5119  5133 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@395679 HexData = [00000000ea03000000000000ffffffff]
11-21 16:49:58.150  5119  5133 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 16:49:58.150  5119  5133 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-21 16:49:58.151  5119  5119 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-21 16:49:58.151  5119  5119 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-21 16:49:58.155  5119  5119 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:49:58.155  5094  5104 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 16:49:58.156  3902  3902 D SystemUpdateService: onCreate
11-21 16:49:58.160  3902  3902 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-21 16:49:58.162  5119  5133 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@395679 HexData = [00000000eb03000000000000ffffffff]
,11-21 16:49:58.163  5119  5133 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 16:49:58.163  5119  5133 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-21 16:49:58.163  5119  5119 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:49:58.164  5094  5105 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 16:49:58.169  3902  3902 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-21 16:49:58.172  3902  5934 I SystemUpdateService: active receiver: enabled
,11-21 16:49:58.174  3902  5446 I iu.UploadsManager: num queued entries: 0
,11-21 16:49:58.174  3902  5446 I iu.UploadsManager: num updated entries: 0
,11-21 16:49:58.175  3902  5446 I iu.SyncManager: NEXT; no task
,11-21 16:49:58.177  3902  3902 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-21 16:49:58.178   511   926 E Netd    : netlink response contains error (No such file or directory)
11-21 16:49:58.178  3902  3902 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-21 16:49:58.178   511   926 D TetherController: Setting IP forward enable = 0
11-21 16:49:58.179   934  3024 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-21 16:49:58.180  3902  5934 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 16:49:58.182  3902  5934 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-21 16:49:58.182  3902  5934 I SystemUpdateService: now status is 0 (complete)
11-21 16:49:58.182  3902  5934 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 16:49:58.182  3902  5934 I SystemUpdateService: file has been verified
11-21 16:49:58.182  3902  5934 I SystemUpdateService: OTA package size = 21989297
,11-21 16:49:58.188  3902  5934 I SystemUpdateService: showing system update notification
,11-21 16:49:58.191   934  3468 I ActivityManager: Start proc 5938:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-21 16:49:58.192   934  3022 D DhcpClient: doQuit
11-21 16:49:58.193   934  3022 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-21 16:49:58.193   934  5422 D DhcpClient: onQuitting
11-21 16:49:58.194  3497  3497 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-21 16:49:58.203   934   934 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 16:49:58.206  3902  3902 D SystemUpdateService: onDestroy
,11-21 16:49:58.219  3497  3497 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-21 16:49:58.223  3497  3497 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-21 16:49:58.239  5938  5938 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-21 16:49:58.242  5938  5938 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 16:49:58.246  3497  3497 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-21 16:49:58.248  5938  5938 D SprintDMHelper: simOperator: 
,11-21 16:49:58.249  5938  5938 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 16:49:58.251  3497  3497 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-21 16:49:58.261   934  3209 I ActivityManager: Start proc 5951:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-21 16:49:58.262   934  3209 I ActivityManager: Killing 5479:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-21 16:49:58.342  5056  5965 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-21 16:49:58.351   934  3912 I ActivityManager: Start proc 5966:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-21 16:49:58.353   934  3022 D wifi    : In wifi stop Hal
,11-21 16:49:58.353   934  3022 D wifi    : halHandle = 0x7f81627900, mVM = 0x7f9dc4d140, mCls = 0x100a02
11-21 16:49:58.354   934  3496 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-21 16:49:58.354   934  3496 D WifiHAL : Got a signal to exit!!!
11-21 16:49:58.354   934  3496 I WifiHAL : Exit wifi_event_loop
11-21 16:49:58.355   934  3022 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-21 16:49:58.355   934  3022 E WifiHAL : Event processing terminated
11-21 16:49:58.355   934  3022 D wifi    : In wifi cleaned up handler
11-21 16:49:58.355   934  3022 I WifiHAL : Internal cleanup completed
11-21 16:49:58.356   934  3203 I ActivityManager: Killing 5307:com.google.android.music:main/u0a59 (adj 15): empty #17
11-21 16:49:58.358  4091  4265 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-21 16:49:58.361  5056  5056 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 16:49:58.375   934  3496 D wifi    : set interface wlan0 flags (DOWN)
11-21 16:49:58.375   934  3022 D WifiNative-HAL: HAL event thread stopped successfully
,11-21 16:49:58.402  5966  5966 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-21 16:49:58.550   934  3468 I ActivityManager: Killing 3947:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-21 16:49:58.551  5740  5819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:49:58.551  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:49:58.551  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:49:58.551  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-21 16:49:58.551  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:49:58.551  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 16:49:58.551  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 16:49:58.551  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 16:49:58.551  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 16:49:58.553  5740  5819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 16:49:58.554   934  3203 D WifiService: setWifiEnabled: true pid=5740, uid=10077
,11-21 16:49:58.554   934  3203 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 16:49:58.555  5740  5788 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-21 16:49:58.577   934   951 D Tethering: InitialState.processMessage what=4
,11-21 16:49:58.579   511   926 D SoftapController: Softap fwReload - Ok
,11-21 16:49:58.581   934  3859 I ActivityManager: Start proc 5979:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
11-21 16:49:58.582   934   951 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-21 16:49:58.582   511   926 D CommandListener: Setting iface cfg
,11-21 16:49:58.583   511   926 D CommandListener: Trying to bring down wlan0
11-21 16:49:58.584   511   926 D CommandListener: Clearing all IP addresses on wlan0
,11-21 16:49:58.586   934  3022 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-21 16:49:58.613  5979  5979 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-21 16:49:58.620   934  3468 I ActivityManager: Killing 5524:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-21 16:49:59.057   934  3912 D WifiService: setWifiEnabled: true pid=5740, uid=10077
11-21 16:49:59.064   934  3912 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:49:59.174   934  3022 D wifi    : set interface wlan0 flags (UP)
,11-21 16:49:59.174   934  3022 I WifiHAL : Initializing wifi
,11-21 16:49:59.174   934  3022 I WifiHAL : Creating socket
,11-21 16:49:59.181   934   951 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-21 16:49:59.181   934  3022 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-21 16:49:59.182   934  3022 D wifi    : Did set static halHandle = 0x7f81627900
,11-21 16:49:59.182   934  3022 D wifi    : halHandle = 0x7f81627900, mVM = 0x7f9dc4d140, mCls = 0x101816
,11-21 16:49:59.183   934  3022 D wifi    : array field set
,11-21 16:49:59.184   934  3022 I WifiNative-HAL: interface[0] = wlan0
,11-21 16:49:59.189   934  5997 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547631560960
11-21 16:49:59.189   934  5997 D wifi    : waitForHalEvents called, vm = 0x7f9dc4d140, obj = 0x101816, env = 0x7f833d4740
,11-21 16:49:59.192   934  3022 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-21 16:49:59.193   934  3022 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-21 16:49:59.255  5998  5998 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-21 16:49:59.312  5998  5998 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 16:49:59.382  5998  5998 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-21 16:49:59.382  5998  5998 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-21 16:49:59.568   934  3927 D WifiService: setWifiEnabled: true pid=5740, uid=10077
,11-21 16:49:59.568   934  3927 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:50:00.071   934  3468 D WifiService: setWifiEnabled: true pid=5740, uid=10077
,11-21 16:50:00.071   934  3468 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-21 16:50:00.210   934  3022 D WifiConfigStore: Loading config and enabling all networks 
,11-21 16:50:00.257   934  3022 D WifiConfigStore: loaded 0 passpoint configs
,11-21 16:50:00.258   934  3022 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-21 16:50:00.259   934  3022 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-21 16:50:00.260   934  3022 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-21 16:50:00.261   934  3022 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-21 16:50:00.262   934  3022 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-21 16:50:00.263   934  3022 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-21 16:50:00.263   934  3022 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-21 16:50:00.264   934  3022 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-21 16:50:00.264   934  3022 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-21 16:50:00.264   934  3022 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-21 16:50:00.264   934  3022 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-21 16:50:00.264   934  3022 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-21 16:50:00.268   934  3022 D WifiNative-HAL: Setting external_sim to 1
,11-21 16:50:00.268  5056  5056 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-21 16:50:00.269   934  3022 D wifi    : setting dfs flag to true, 0x7f853dfa60
11-21 16:50:00.270   934  3022 D WifiStateMachine: Setting OUI to DA-A1-19
11-21 16:50:00.270   934  3022 D wifi    : setting scan oui 0x7f853dfa60
,11-21 16:50:00.271   934  3022 D WifiHAL : Sending mac address OUI
,11-21 16:50:00.275   934  3022 E native  : do suspend false
,11-21 16:50:00.285   934  3022 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-21 16:50:00.285   511   926 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-21 16:50:00.285   934   934 D RttService: SCAN_AVAILABLE : 3
11-21 16:50:00.286   934  3132 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-21 16:50:00.287   511   926 D CommandListener: Setting iface cfg
,11-21 16:50:00.292   934  3020 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,11-21 16:50:00.292   934  3020 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-21 16:50:00.302   934  3020 D WifiNative-HAL: p2pGetDeviceAddress
,11-21 16:50:00.307   934   949 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=178669 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
11-21 16:50:00.307   934  3020 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-21 16:50:00.582  5740  5819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-21 16:50:00.582  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-21 16:50:00.582  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-21 16:50:00.582  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-21 16:50:00.582  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-21 16:50:00.582  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-21 16:50:00.582  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-21 16:50:00.582  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-21 16:50:00.582  5740  5819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-21 16:50:00.587  5740  5819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-21 16:50:00.591  5740  5788 D BluetoothAdapter: enable(): BT is already enabled..!
,11-21 16:50:00.592   934  3856 D WifiService: setWifiEnabled: true pid=5740, uid=10077
11-21 16:50:00.592   934  3856 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-21 16:50:00.593  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-21 16:50:00.593  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-21 16:50:00.593  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-21 16:50:00.594  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1bb7f9 removed from the list
11-21 16:50:00.594  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 16:50:00.594  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@71633e removed from the list
,11-21 16:50:00.594  5740  5788 D io.jxcore.node.ConnectivityMonitor: stop
11-21 16:50:00.597  5740  5788 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-21 16:50:00.599  5740  5788 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-21 16:50:00.601  5740  5788 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-21 16:50:00.603  5740  5788 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-21 16:50:00.606  5740  5788 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-21 16:50:00.608  5740  5788 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-21 16:50:00.609  5740  5788 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-21 16:50:00.609  5740  5788 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-21 16:50:00.610  5740  5788 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-21 16:50:00.613  5740  5788 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-21 16:50:00.613  5740  5788 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6f801ed Bundle[{}]
,11-21 16:50:00.615  5740  5788 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-21 16:50:00.615  5740  5788 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-21 16:50:00.615  5740  5788 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-21 16:50:00.617  5740  5788 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,11-21 16:50:00.617  5740  5788 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-21 16:50:00.618  5740  5788 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,11-21 16:50:00.618  5740  5788 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-21 16:50:00.619  5740  5788 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-21 16:50:00.620  5740  5788 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-21 16:50:00.621  5740  5788 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-21 16:50:00.622  5740  5788 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-21 16:50:00.624  5740  5788 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-21 16:50:00.627  5740  5788 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-21 16:50:00.629  5740  5788 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-21 16:50:00.630  5740  5788 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-21 16:50:00.632  5740  5788 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-21 16:50:00.633  5740  5788 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-21 16:50:00.635  5740  5788 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-21 16:50:00.637  5740  5788 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-21 16:50:01.640  5740  5788 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-21 16:50:01.641  5740  5788 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-21 16:50:01.644  5740  5788 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-21 16:50:01.645  5740  5788 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-21 16:50:01.645  5740  5788 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-21 16:50:01.645  5740  5788 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
11-21 16:50:01.646  5740  5788 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-21 16:50:01.646  5740  5788 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-21 16:50:01.646  5740  5788 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
11-21 16:50:01.647  5740  5788 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
11-21 16:50:01.647  5740  5788 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
11-21 16:50:01.648  5740  5788 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
11-21 16:50:01.649  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-21 16:50:01.649  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14d16ec added. We now have 3 listener(s)
,11-21 16:50:01.651  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 16:50:01.651  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-21 16:50:01.651  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-21 16:50:01.652  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-21 16:50:01.652  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@156dab5 added. We now have 3 listener(s)
11-21 16:50:01.652  5740  5788 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-21 16:50:01.653  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-21 16:50:01.658  5740  5788 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-21 16:50:01.659  5740  5788 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
,11-21 16:50:01.659  5740  5788 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-21 16:50:01.659  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-21 16:50:01.660  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.660  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.660  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.660  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:50:01.660  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-21 16:50:01.660  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:50:01.660  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:50:01.660  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-21 16:50:01.663  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-21 16:50:01.664  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:50:01.664  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-21 16:50:01.664  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-21 16:50:01.664  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-21 16:50:01.664  5740  6002 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:50:01.664  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-21 16:50:01.664  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:50:01.664  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-21 16:50:01.664  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:50:01.665  5740  6002 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-21 16:50:01.668  5740  6002 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:50:01.667  5876  5876 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34027]" dev="sockfs" ino=34027 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:50:01.667  5876  5876 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34027]" dev="sockfs" ino=34027 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:50:01.670  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-21 16:50:01.670  5740  5788 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:50:01.670  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 16:50:01.677  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:01.677  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:50:01.678  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:50:01.678  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:50:01.678  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-21 16:50:01.679  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.679  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.680  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:50:01.680  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:50:01.680  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-21 16:50:01.680  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
11-21 16:50:01.680  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:50:01.680  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:50:01.680  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.680  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
,11-21 16:50:01.680  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:50:01.680  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.680  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.680  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.681  5740  5788 D BluetoothAdapter: STATE_ON
,11-21 16:50:01.685  5865  5876 D BtGatt.GattService: registerClient() - UUID=156e9693-5351-4c12-a0ae-1a8b52cf0e36
11-21 16:50:01.685  5865  5883 D BtGatt.GattService: onClientRegistered() - UUID=156e9693-5351-4c12-a0ae-1a8b52cf0e36, clientIf=5
,11-21 16:50:01.686  5740  5750 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-21 16:50:01.688  5865  5885 D BtGatt.AdvertiseManager: message : 0
,11-21 16:50:01.690  5865  5885 D BtGatt.AdvertiseManager: starting multi advertising
,11-21 16:50:01.701  5865  5883 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-21 16:50:01.706  5865  5883 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-21 16:50:01.707  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:01.707  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.707  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:50:01.707  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:01.707  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.707  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:01.707  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.708  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.708  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:50:01.709  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:50:01.709  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:01.710  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.710  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.710  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:01.710  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.711  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.711  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-21 16:50:01.711  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.714  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.714  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-21 16:50:01.714  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.714  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.714  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:50:01.714  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-21 16:50:02.214  5740  5740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-21 16:50:02.214  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-21 16:50:02.214  5740  5740 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:50:02.751   934  3022 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-21 16:50:03.348  5998  5998 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-21 16:50:03.349  5998  5998 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 16:50:03.350  5998  5998 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-21 16:50:03.376   934  3022 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-21 16:50:03.378   934  3022 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-21 16:50:03.378   934  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 16:50:03.390   934  3022 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-21 16:50:03.424   934  3022 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-21 16:50:03.429  5998  5998 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-21 16:50:03.851  5998  5998 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-21 16:50:03.885  5998  5998 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-21 16:50:03.885  5998  5998 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
11-21 16:50:03.897   934  3022 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-21 16:50:03.897   934  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-21 16:50:03.897   934  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-21 16:50:03.917   934  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-21 16:50:03.930   511   926 D CommandListener: Setting iface cfg
,11-21 16:50:03.935   934  3022 D WifiStateMachine: Start Dhcp Watchdog 2
,11-21 16:50:03.940   934  6007 D DhcpClient: Receive thread started
,11-21 16:50:03.944   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:50:03.945   934  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-21 16:50:03.945   934  3024 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-21 16:50:04.024   934  3022 E native  : do suspend false
,11-21 16:50:04.034   934  6006 D DhcpClient: Broadcasting DHCPDISCOVER
,11-21 16:50:04.047   934  6007 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172659, domain null
,11-21 16:50:04.048   934  6006 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172659 seconds
11-21 16:50:04.050   934  6006 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-21 16:50:04.065   934  6007 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-21 16:50:04.066   934  6006 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-21 16:50:04.069   511   926 D CommandListener: Setting iface cfg
,11-21 16:50:04.073   934  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-21 16:50:04.078   934  6006 D DhcpClient: Scheduling renewal in 86399s
,11-21 16:50:04.090   934  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-21 16:50:04.091   934  3022 D WifiConfigStore: No blacklist allowed without epno enabled
,11-21 16:50:04.093   934  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-21 16:50:04.098   934  3024 D ConnectivityService: Adding iface wlan0 to network 101
11-21 16:50:04.101   934  3022 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-21 16:50:04.145   934  3024 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-21 16:50:04.145   934  3024 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-21 16:50:04.146   934  3024 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-21 16:50:04.148   934  3024 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-21 16:50:04.149   934  3024 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-21 16:50:04.157   934  3024 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:50:04.161   934  3024 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-21 16:50:04.161   934  3024 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-21 16:50:04.161   934  3024 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-21 16:50:04.161   934  3022 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-21 16:50:04.161   934  3024 D ConnectivityService:    accepting network in place of null
11-21 16:50:04.162   934  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-21 16:50:04.162   934  3024 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -57]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-21 16:50:04.174   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=182536, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:50:04.184   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:50:04.204   511   926 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-21 16:50:04.207   934  3024 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-21 16:50:04.207   934  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-21 16:50:04.207  3794  3935 W QCNEJ   : |CORE| network available: 101
11-21 16:50:04.208   934  3024 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-21 16:50:04.209   934   951 D Tethering: MasterInitialState.processMessage what=3
11-21 16:50:04.212  3794  3935 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-21 16:50:04.213  3794  3935 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-21 16:50:04.214  3794  3935 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-21 16:50:04.228  5094  5117 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-21 16:50:04.228  5094  5117 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-21 16:50:04.228  5094  5117 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-21 16:50:04.228  5094  5117 E SarControlService: no key has been found,reset the power
11-21 16:50:04.228  5094  5131 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-21 16:50:04.228  5094  5131 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-21 16:50:04.228  5094  5131 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-21 16:50:04.229  5119  5119 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:50:04.229  5119  5119 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-21 16:50:04.231  5094  5131 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-21 16:50:04.231  5094  5131 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-21 16:50:04.231  5094  5131 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-21 16:50:04.231  5119  5119 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-21 16:50:04.232  5119  5119 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-21 16:50:04.236  3902  3902 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-21 16:50:04.237  5119  5133 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@395679 HexData = [00000000ec03000000000000ffffffff]
11-21 16:50:04.237  5119  5133 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-21 16:50:04.237  5119  5133 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-21 16:50:04.237  5119  5133 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@395679 HexData = [00000000ed03000000000000ffffffff]
11-21 16:50:04.237  5119  5133 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-21 16:50:04.237  5119  5133 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-21 16:50:04.238  5119  5119 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:50:04.238  5094  5104 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-21 16:50:04.238  5119  5119 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-21 16:50:04.238  5094  5105 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-21 16:50:04.241  4023  4023 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-21 16:50:04.242  3902  3902 D SystemUpdateService: onCreate
11-21 16:50:04.246  3902  3902 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-21 16:50:04.259   934  6004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-21 16:50:04.262  3902  3902 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-21 16:50:04.268  3902  5446 I iu.UploadsManager: num queued entries: 0
,11-21 16:50:04.269  3902  5446 I iu.UploadsManager: num updated entries: 0
11-21 16:50:04.269  3902  5446 I iu.SyncManager: NEXT; no task
,11-21 16:50:04.271  3902  3902 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-21 16:50:04.273  3902  3902 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-21 16:50:04.275  5938  5938 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-21 16:50:04.278  5938  5938 D SprintDMHelper: simOperator: 
11-21 16:50:04.278  5938  5938 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-21 16:50:04.279  3902  6018 I SystemUpdateService: active receiver: enabled
,11-21 16:50:04.312   934  6004 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 21 Nov 2016 15:50:04 GMT], X-Android-Received-Millis=[1479743404312], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479743404287]}
,11-21 16:50:04.313   934  3024 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-21 16:50:04.313   934  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-21 16:50:04.313   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-21 16:50:04.314   934  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-21 16:50:04.315  3902  6018 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-21 16:50:04.324  3902  6018 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-21 16:50:04.325  3902  6018 I SystemUpdateService: now status is 0 (complete)
11-21 16:50:04.325  3902  6018 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-21 16:50:04.325  3902  6018 I SystemUpdateService: file has been verified
11-21 16:50:04.325  3902  6018 I SystemUpdateService: OTA package size = 21989297
,11-21 16:50:04.332  3902  6018 I SystemUpdateService: showing system update notification
,11-21 16:50:04.343   934   934 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-21 16:50:04.345  3902  3902 D SystemUpdateService: onDestroy
,11-21 16:50:04.447  5056  6022 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-21 16:50:05.209   934  3024 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-21 16:50:05.213  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-21 16:50:05.213  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-21 16:50:05.213  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-21 16:50:05.213  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:50:05.213  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-21 16:50:05.214  5740  6002 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:50:05.214  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:50:05.214  5740  6002 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:50:05.215  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-21 16:50:05.215  5740  6002 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:50:05.215  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:50:05.215  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:50:05.216  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-21 16:50:05.216  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-21 16:50:05.216  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:50:05.216  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:50:05.216  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:50:05.217  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:50:05.217  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:05.217  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.217  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.217  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.220  5740  5788 D BluetoothAdapter: STATE_ON
,11-21 16:50:05.221  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:50:05.224  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:50:05.225  5740  5788 D BluetoothLeScanner: could not find callback wrapper
,11-21 16:50:05.225  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:50:05.225  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:05.226  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.226  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.226  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-21 16:50:05.227  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:05.229  5865  5885 D BtGatt.AdvertiseManager: message : 1
,11-21 16:50:05.231  5865  5885 D BtGatt.AdvertiseManager: stop advertise for client 5
11-21 16:50:05.241  5865  5883 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-21 16:50:05.241  5865  5883 D BtGatt.GattService: Client app is not null!
,11-21 16:50:05.242  5865  5903 D BtGatt.GattService: unregisterClient() - clientIf=5
11-21 16:50:05.244  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 16:50:05.244  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.244  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-21 16:50:05.245  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.245  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.245  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.245  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:50:05.245  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-21 16:50:05.247  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-21 16:50:05.249  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.251  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.251  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:50:05.251  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.251  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.252  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-21 16:50:05.252  5740  5740 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-21 16:50:05.252  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:50:05.252  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:50:05.253  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:50:05.253  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.254  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:50:05.254  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-21 16:50:05.254  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.254  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.254  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-21 16:50:05.254  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:50:05.256  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.257  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.257  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.257  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 16:50:05.257  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:50:05.260  5740  5788 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-21 16:50:05.260  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-21 16:50:05.261  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-21 16:50:05.262  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-21 16:50:05.262  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-21 16:50:05.262  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-21 16:50:05.262  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-21 16:50:05.264  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-21 16:50:05.269  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 16:50:05.269  5740  5788 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-21 16:50:05.269  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-21 16:50:05.275  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:05.275  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-21 16:50:05.276  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:50:05.276  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:50:05.276  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-21 16:50:05.280  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-21 16:50:05.284  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-21 16:50:05.284  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:05.284  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 16:50:05.284  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-21 16:50:05.285  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 16:50:05.285  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 16:50:05.286  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.287  5740  5788 D BluetoothAdapter: STATE_ON
,11-21 16:50:05.291  5865  5875 D BtGatt.GattService: registerClient() - UUID=103ccd22-495f-46c6-bd23-44ca894fb09a
,11-21 16:50:05.292  5865  5883 D BtGatt.GattService: onClientRegistered() - UUID=103ccd22-495f-46c6-bd23-44ca894fb09a, clientIf=5
,11-21 16:50:05.293  5740  5784 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-21 16:50:05.294  5865  5895 D BtGatt.GattService: start scan with filters
,11-21 16:50:05.299  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-21 16:50:05.299  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.299  5865  5886 D BtGatt.ScanManager: handling starting scan
11-21 16:50:05.299  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 16:50:05.300  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.300  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:50:05.300  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:50:05.300  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.301  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 16:50:05.301  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:50:05.301  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.301  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.301  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-21 16:50:05.302  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:50:05.302  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:05.302  5865  5886 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77f2896
11-21 16:50:05.305  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.305  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 16:50:05.305  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:05.305  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:05.306  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:50:05.311  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.311  5865  5883 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-21 16:50:05.311  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.311  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:05.311  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:05.311  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-21 16:50:05.311  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-21 16:50:05.312  5865  5886 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-21 16:50:05.317  5865  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-21 16:50:05.318  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:05.318  5865  5886 D BtGatt.ScanManager: Starting BLE batch scan
11-21 16:50:05.318  5865  5886 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 16:50:05.328  5865  5883 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-21 16:50:05.328  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:50:05.334  5865  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-21 16:50:05.335  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:50:05.813  5740  5740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-21 16:50:05.813  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-21 16:50:05.813  5740  5740 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:50:06.955   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:50:06.963   934  3024 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 59
,11-21 16:50:08.308  5740  5788 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
11-21 16:50:08.309  5740  5788 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-21 16:50:08.309  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-21 16:50:08.310  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:08.310  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.310  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-21 16:50:08.310  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.311  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-21 16:50:08.311  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:08.311  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:08.311  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-21 16:50:08.311  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-21 16:50:08.312  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.312  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:08.312  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:08.315  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:50:08.316  5865  5895 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 16:50:08.316  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:50:08.318  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:50:08.319  5865  5886 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 16:50:08.320  5865  5903 D BtGatt.GattService: stopScan() - queue size =1
,11-21 16:50:08.322  5865  5895 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:50:08.323  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-21 16:50:08.324  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.324  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 16:50:08.324  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.324  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-21 16:50:08.325  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:08.325  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.325  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-21 16:50:08.325  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-21 16:50:08.325  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-21 16:50:08.325  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-21 16:50:08.325  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.327  5740  5788 D BluetoothAdapter: STATE_ON
,11-21 16:50:08.328  5865  5865 D BtGatt.ScanManager: awakened up at time 186691
11-21 16:50:08.332  5865  5876 D BtGatt.GattService: registerClient() - UUID=8b51fbf6-e2a4-498f-bc75-3ccf74c17d02
11-21 16:50:08.334  5865  5883 D BtGatt.GattService: onClientRegistered() - UUID=8b51fbf6-e2a4-498f-bc75-3ccf74c17d02, clientIf=5
11-21 16:50:08.336  5740  5784 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-21 16:50:08.336  5865  5903 D BtGatt.GattService: start scan with filters
,11-21 16:50:08.340  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-21 16:50:08.340  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.340  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-21 16:50:08.340  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.341  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.341  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:50:08.341  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-21 16:50:08.341  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 16:50:08.341  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-21 16:50:08.341  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 16:50:08.341  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:50:08.341  5740  5788 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-21 16:50:08.341  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:50:08.341  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-21 16:50:08.341  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-21 16:50:08.342  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-21 16:50:08.343  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-21 16:50:08.343  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-21 16:50:08.344  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-21 16:50:08.344  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-21 16:50:08.344  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-21 16:50:08.344  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-21 16:50:08.344  5740  6031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-21 16:50:08.345  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-21 16:50:08.345  5740  5788 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-21 16:50:08.347  5740  6031 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-21 16:50:08.348  5865  5883 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-21 16:50:08.348  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:08.348  5865  5883 D BtGatt.GattService: current time is 186711223747
11-21 16:50:08.349  5865  5883 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -92, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -90, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -79, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 16:50:08.349  5740  6031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-21 16:50:08.347  5895  5895 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34062]" dev="sockfs" ino=34062 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-21 16:50:08.347  5895  5895 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[34062]" dev="sockfs" ino=34062 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-21 16:50:08.350  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-21 16:50:08.351  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-21 16:50:08.351  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-21 16:50:08.352  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-21 16:50:08.352  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 16:50:08.352  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-21 16:50:08.355  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:08.355  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.355  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.355  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-21 16:50:08.355  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-21 16:50:08.355  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-21 16:50:08.355  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-21 16:50:08.356  5740  5788 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:50:08.356  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:50:08.356  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.356  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-21 16:50:08.356  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-21 16:50:08.356  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.356  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.356  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.357  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:50:08.358  5865  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-21 16:50:08.358  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:08.358  5865  5886 D BtGatt.ScanManager: stopping BLe Batch
11-21 16:50:08.359  5865  5876 D BtGatt.GattService: registerClient() - UUID=12b3d484-b443-4dc5-a936-e637158fbf70
11-21 16:50:08.360  5865  5883 D BtGatt.GattService: onClientRegistered() - UUID=12b3d484-b443-4dc5-a936-e637158fbf70, clientIf=6
11-21 16:50:08.360  5740  5751 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-21 16:50:08.361  5865  5885 D BtGatt.AdvertiseManager: message : 0
,11-21 16:50:08.363  5865  5885 D BtGatt.AdvertiseManager: starting multi advertising
11-21 16:50:08.363  5865  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-21 16:50:08.363  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:08.364  5865  5886 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:50:08.369  5865  5883 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 16:50:08.369  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:50:08.372  5865  5886 D BtGatt.ScanManager: handling starting scan
,11-21 16:50:08.378  5865  5883 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-21 16:50:08.382  5865  5883 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-21 16:50:08.382  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:08.382  5865  5886 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-21 16:50:08.386  5865  5883 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-21 16:50:08.387  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.387  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-21 16:50:08.387  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-21 16:50:08.387  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-21 16:50:08.389  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-21 16:50:08.389  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:08.390  5865  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-21 16:50:08.391  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:08.391  5865  5886 D BtGatt.ScanManager: Starting BLE batch scan
11-21 16:50:08.391  5865  5886 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-21 16:50:08.391  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.391  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.392  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:08.392  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 16:50:08.392  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-21 16:50:08.392  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-21 16:50:08.392  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-21 16:50:08.392  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-21 16:50:08.392  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-21 16:50:08.392  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-21 16:50:08.392  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:50:08.393  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-21 16:50:08.393  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-21 16:50:08.393  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:50:08.393  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-21 16:50:08.393  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-21 16:50:08.393  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-21 16:50:08.396  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-21 16:50:08.396  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-21 16:50:08.396  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:08.396  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:08.396  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:50:08.396  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-21 16:50:08.400  5865  5883 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-21 16:50:08.400  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:50:08.404  5865  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-21 16:50:08.404  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:50:08.897  5740  5740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
11-21 16:50:08.898  5740  5740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 16:50:08.898  5740  5740 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-21 16:50:09.886   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:09.987   934  3024 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-21 16:50:10.887   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:11.395  5740  5788 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-21 16:50:11.396  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-21 16:50:11.396  5740  5788 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-21 16:50:11.396  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-21 16:50:11.396  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-21 16:50:11.397  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-21 16:50:11.397  5740  6031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-21 16:50:11.397  5740  6031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-21 16:50:11.397  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-21 16:50:11.397  5740  6031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-21 16:50:11.397  5740  5788 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-21 16:50:11.398  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-21 16:50:11.398  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-21 16:50:11.398  5740  5788 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14d16ec removed from the list
11-21 16:50:11.398  5740  5740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-21 16:50:11.398  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-21 16:50:11.398  5740  5788 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-21 16:50:11.398  5740  5740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-21 16:50:11.398  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-21 16:50:11.398  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-21 16:50:11.399  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.399  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.399  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:11.399  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-21 16:50:11.400  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.402  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:50:11.402  5865  5895 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-21 16:50:11.403  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-21 16:50:11.404  5865  5886 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-21 16:50:11.404  5740  5788 D BluetoothAdapter: STATE_ON
11-21 16:50:11.406  5865  5875 D BtGatt.GattService: stopScan() - queue size =1
11-21 16:50:11.408  5865  5876 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-21 16:50:11.408  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-21 16:50:11.409  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.409  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-21 16:50:11.409  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.409  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.410  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.410  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-21 16:50:11.410  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.412  5865  5885 D BtGatt.AdvertiseManager: message : 1
11-21 16:50:11.413  5865  5865 D BtGatt.ScanManager: awakened up at time 189775
11-21 16:50:11.414  5865  5885 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-21 16:50:11.423  5865  5883 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-21 16:50:11.424  5865  5883 D BtGatt.GattService: Client app is not null!
,11-21 16:50:11.425  5865  5875 D BtGatt.GattService: unregisterClient() - clientIf=6
11-21 16:50:11.425  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-21 16:50:11.425  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:11.425  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-21 16:50:11.425  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.426  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.426  5740  5788 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.426  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-21 16:50:11.426  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-21 16:50:11.426  5740  5788 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-21 16:50:11.427  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.428  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-21 16:50:11.428  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:50:11.428  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.428  5740  5788 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-21 16:50:11.429  5740  5788 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@156dab5 removed from the list
11-21 16:50:11.429  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:50:11.429  5740  5788 D io.jxcore.node.ConnectivityMonitor: stop
11-21 16:50:11.429  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-21 16:50:11.429  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:50:11.429  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.429  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-21 16:50:11.429  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-21 16:50:11.429  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.429  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.429  5740  5740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED]
11-21 16:50:11.430  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.430  5740  5788 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-21 16:50:11.430  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-21 16:50:11.430  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-21 16:50:11.430  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-21 16:50:11.430  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-21 16:50:11.431  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-21 16:50:11.431  5740  5788 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-21 16:50:11.431  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.431  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.431  5740  5740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.431  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.431  5740  5788 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,11-21 16:50:11.432  5740  5740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-21 16:50:11.432  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.432  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-21 16:50:11.432  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-21 16:50:11.432  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.432  5740  5740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-21 16:50:11.432  5740  5740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-21 16:50:11.433  5740  5788 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-21 16:50:11.433  5740  5788 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
,11-21 16:50:11.434  5740  5788 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-21 16:50:11.435  5740  5788 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-21 16:50:11.436  5740  5788 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-21 16:50:11.437  5740  5788 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-21 16:50:11.439  5740  5788 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,11-21 16:50:11.445  5865  5883 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-21 16:50:11.446  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:11.446  5865  5883 D BtGatt.GattService: current time is 189808695716
11-21 16:50:11.446  5865  5883 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -95, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -79, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -79, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -89, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-21 16:50:11.446  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-21 16:50:11.447  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-21 16:50:11.447  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-21 16:50:11.447  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-21 16:50:11.448  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-21 16:50:11.448  5865  5883 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-21 16:50:11.453  5865  5883 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-21 16:50:11.453  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:11.454  5865  5886 D BtGatt.ScanManager: stopping BLe Batch
,11-21 16:50:11.458  5865  5883 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-21 16:50:11.458  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-21 16:50:11.459  5865  5886 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-21 16:50:11.463  5865  5883 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-21 16:50:11.464  5865  5883 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-21 16:50:11.888   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:11.933  5740  5740 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-21 16:50:12.163   934  3024 D ConnectivityService: handlePromptUnvalidated 101
,11-21 16:50:12.889   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:13.001   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:50:13.444  5740  5788 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-21 16:50:13.604  5740  6033 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 16:50:13.604  5740  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:50:13.890   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:13.990  5740  5749 I art     : Background sticky concurrent mark sweep GC freed 45(44KB) AllocSpace objects, 8(4MB) LOS objects, 5% free, 52MB/55MB, paused 6.173ms total 43.918ms
,11-21 16:50:14.422  5740  6033 W !!      : call onHalfStreamCopied
,11-21 16:50:14.423  5740  6033 I testCopyDataAndClose: closing input stream
,11-21 16:50:14.891   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-21 16:50:15.204  5740  6033 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 16:50:15.310   934  3022 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-21 16:50:19.644  5740  5788 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-21 16:50:19.739  5740  6034 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 16:50:19.739  5740  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 194, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 194, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-21 16:50:21.427  5740  6034 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-21 16:50:22.348   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=200710, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:50:25.682  5740  5788 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-21 16:50:25.685  5740  6035 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:50:25.685  5740  6035 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:50:25.685  5740  6035 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 196, thread name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:50:25.685  5740  6035 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:50:25.686  5740  6035 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-21 16:50:25.686  5740  6035 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-21 16:50:25.686  5740  6035 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-21 16:50:25.686  5740  6035 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-21 16:50:25.686  5740  6035 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-21 16:50:25.686  5740  6035 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-21 16:50:25.686  5740  6035 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-21 16:50:25.686  5740  6035 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 196, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:50:25.686  5740  6035 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-21 16:50:25.688  5740  5788 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-21 16:50:25.689  5740  5788 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-21 16:50:25.689  5740  5788 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-21 16:50:25.692  5740  6036 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:50:25.692  5740  6036 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-21 16:50:25.692  5740  6036 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 200, thread name: My test thread name): Test exception.
11-21 16:50:25.692  5740  6036 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:50:25.692  5740  6036 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-21 16:50:25.693  5740  6036 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-21 16:50:25.693  5740  6036 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name). Connection data: Peer properties: [null null].
11-21 16:50:25.693  5740  6036 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-21 16:50:25.697  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG UnitTest_app: 'Running unit tests'
11-21 16:50:25.697  5740  5788 I jxcore-log: 
11-21 16:50:25.698  5740  5788 I jxcore-log: *Native tests were executed*
11-21 16:50:25.698  5740  5788 I jxcore-log: 
11-21 16:50:25.698  5740  5788 I jxcore-log: Total number of executed tests:  81
11-21 16:50:25.698  5740  5788 I jxcore-log: 
11-21 16:50:25.698  5740  5788 I jxcore-log: Number of passed tests:  79
11-21 16:50:25.698  5740  5788 I jxcore-log: 
11-21 16:50:25.698  5740  5788 I jxcore-log: Number of failed tests:  0
11-21 16:50:25.698  5740  5788 I jxcore-log: 
,11-21 16:50:25.698  5740  5788 I jxcore-log: Number of ignored tests:  2
11-21 16:50:25.698  5740  5788 I jxcore-log: 
11-21 16:50:25.698  5740  5788 I jxcore-log: Total duration:  36114
11-21 16:50:25.698  5740  5788 I jxcore-log: 
,11-21 16:50:25.701  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-21 16:50:25.701  5740  5788 I jxcore-log: 
,11-21 16:50:25.705  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:50:25.705  5740  5788 I jxcore-log: 
,11-21 16:50:25.706  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:50:25.706  5740  5788 I jxcore-log: 
,11-21 16:50:25.708  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:50:25.708  5740  5788 I jxcore-log: 
,11-21 16:50:25.708  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:50:25.708  5740  5788 I jxcore-log: 
11-21 16:50:25.709  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:50:25.709  5740  5788 I jxcore-log: 
11-21 16:50:25.710  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:50:25.710  5740  5788 I jxcore-log: 
,11-21 16:50:25.710  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:50:25.710  5740  5788 I jxcore-log: 
11-21 16:50:25.710  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:50:25.710  5740  5788 I jxcore-log: 
11-21 16:50:25.711  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:50:25.711  5740  5788 I jxcore-log: 
11-21 16:50:25.711  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:50:25.711  5740  5788 I jxcore-log: 
11-21 16:50:25.711  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:50:25.711  5740  5788 I jxcore-log: 
11-21 16:50:25.711  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:50:25.711  5740  5788 I jxcore-log: 
11-21 16:50:25.711  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:50:25.711  5740  5788 I jxcore-log: 
11-21 16:50:25.712  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 16:50:25.712  5740  5788 I jxcore-log: 
11-21 16:50:25.712  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:50:25.712  5740  5788 I jxcore-log: 
11-21 16:50:25.712  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:50:25.712  5740  5788 I jxcore-log: 
11-21 16:50:25.712  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:50:25.712  5740  5788 I jxcore-log: 
11-21 16:50:25.713  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 16:50:25.713  5740  5788 I jxcore-log: 
11-21 16:50:25.713  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:50:25.713  5740  5788 I jxcore-log: 
11-21 16:50:25.713  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:50:25.713  5740  5788 I jxcore-log: 
,11-21 16:50:25.713  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:50:25.713  5740  5788 I jxcore-log: 
11-21 16:50:25.713  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-21 16:50:25.713  5740  5788 I jxcore-log: 
11-21 16:50:25.713  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:50:25.713  5740  5788 I jxcore-log: 
11-21 16:50:25.714  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-21 16:50:25.714  5740  5788 I jxcore-log: 
11-21 16:50:25.714  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:50:25.714  5740  5788 I jxcore-log: 
11-21 16:50:25.714  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-21 16:50:25.714  5740  5788 I jxcore-log: 
,11-21 16:50:25.715  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-21 16:50:25.715  5740  5788 I jxcore-log: 
11-21 16:50:25.715  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-21 16:50:25.715  5740  5788 I jxcore-log: 
11-21 16:50:25.715  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:50:25.715  5740  5788 I jxcore-log: 
11-21 16:50:25.716  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:50:25.716  5740  5788 I jxcore-log: 
11-21 16:50:25.717  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-21 16:50:25.717  5740  5788 I jxcore-log: 
11-21 16:50:25.717  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:50:25.717  5740  5788 I jxcore-log: 
,11-21 16:50:25.717  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:50:25.717  5740  5788 I jxcore-log: 
11-21 16:50:25.717  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-21 16:50:25.717  5740  5788 I jxcore-log: 
11-21 16:50:25.718  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-21 16:50:25.718  5740  5788 I jxcore-log: 
11-21 16:50:25.718  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:50:25.718  5740  5788 I jxcore-log: 
11-21 16:50:25.718  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-21 16:50:25.718  5740  5788 I jxcore-log: 
11-21 16:50:25.718  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-21 16:50:25.718  5740  5788 I jxcore-log: 
,11-21 16:50:25.723  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-21 16:50:25.723  5740  5788 I jxcore-log: 
,11-21 16:50:25.723  5740  5788 I jxcore-log: 2016-11-21 15:50:25 - WARN testUtils: 'myNameCallback not set!'
11-21 16:50:25.723  5740  5788 I jxcore-log: 
,11-21 16:50:25.725  5740  5740 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-21 16:50:27.764  5740  5788 I jxcore-log: 2016-11-21 15:50:27 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-21 16:50:27.764  5740  5788 I jxcore-log: 
,11-21 16:50:27.767  5740  5788 I jxcore-log: 2016-11-21 15:50:27 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-21 16:50:27.767  5740  5788 I jxcore-log: 
,11-21 16:50:28.049  3711  3917 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-21 16:50:28.049  3711  3917 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-21 16:50:28.078  3626  3626 I ConfigService: onCreate
,11-21 16:50:28.093  5740  5788 I jxcore-log: 2016-11-21 15:50:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-21 16:50:28.093  5740  5788 I jxcore-log: 
,11-21 16:50:28.103  5740  5788 I jxcore-log: 2016-11-21 15:50:28 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-21 16:50:28.103  5740  5788 I jxcore-log: 
,11-21 16:50:29.188  5740  5788 I jxcore-log: 2016-11-21 15:50:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-21 16:50:29.188  5740  5788 I jxcore-log: 
,11-21 16:50:29.353  5740  5788 I jxcore-log: 2016-11-21 15:50:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-21 16:50:29.353  5740  5788 I jxcore-log: 
,11-21 16:50:29.358  5740  5788 I jxcore-log: 2016-11-21 15:50:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-21 16:50:29.358  5740  5788 I jxcore-log: 
,11-21 16:50:29.370  5740  5788 I jxcore-log: 2016-11-21 15:50:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-21 16:50:29.370  5740  5788 I jxcore-log: 
,11-21 16:50:29.858  5740  5788 I jxcore-log: 2016-11-21 15:50:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-21 16:50:29.858  5740  5788 I jxcore-log: 
,11-21 16:50:29.902  5740  5788 I jxcore-log: 2016-11-21 15:50:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-21 16:50:29.902  5740  5788 I jxcore-log: 
,11-21 16:50:29.915  5740  5788 I jxcore-log: 2016-11-21 15:50:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-21 16:50:29.915  5740  5788 I jxcore-log: 
,11-21 16:50:29.919  5740  5788 I jxcore-log: 2016-11-21 15:50:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-21 16:50:29.919  5740  5788 I jxcore-log: 
,11-21 16:50:30.190  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-21 16:50:30.190  5740  5788 I jxcore-log: 
,11-21 16:50:30.317  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-21 16:50:30.317  5740  5788 I jxcore-log: 
,11-21 16:50:30.686  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-21 16:50:30.686  5740  5788 I jxcore-log: 
,11-21 16:50:30.692  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-21 16:50:30.692  5740  5788 I jxcore-log: 
,11-21 16:50:30.697  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-21 16:50:30.697  5740  5788 I jxcore-log: 
,11-21 16:50:30.700  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-21 16:50:30.700  5740  5788 I jxcore-log: 
,11-21 16:50:30.705  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-21 16:50:30.705  5740  5788 I jxcore-log: 
,11-21 16:50:30.743  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-21 16:50:30.743  5740  5788 I jxcore-log: 
,11-21 16:50:30.749  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-21 16:50:30.749  5740  5788 I jxcore-log: 
,11-21 16:50:30.777  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-21 16:50:30.777  5740  5788 I jxcore-log: 
,11-21 16:50:30.815  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-21 16:50:30.815  5740  5788 I jxcore-log: 
,11-21 16:50:30.822  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-21 16:50:30.822  5740  5788 I jxcore-log: 
,11-21 16:50:30.829  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-21 16:50:30.829  5740  5788 I jxcore-log: 
,11-21 16:50:30.844  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-21 16:50:30.844  5740  5788 I jxcore-log: 
,11-21 16:50:30.858  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-21 16:50:30.858  5740  5788 I jxcore-log: 
,11-21 16:50:30.864  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-21 16:50:30.864  5740  5788 I jxcore-log: 
,11-21 16:50:30.870  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-21 16:50:30.870  5740  5788 I jxcore-log: 
,11-21 16:50:30.883  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-21 16:50:30.883  5740  5788 I jxcore-log: 
,11-21 16:50:30.900  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-21 16:50:30.900  5740  5788 I jxcore-log: 
,11-21 16:50:30.914  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-21 16:50:30.914  5740  5788 I jxcore-log: 
,11-21 16:50:30.925  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-21 16:50:30.925  5740  5788 I jxcore-log: 
,11-21 16:50:30.938  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-21 16:50:30.938  5740  5788 I jxcore-log: 
,11-21 16:50:30.948  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-21 16:50:30.948  5740  5788 I jxcore-log: 
,11-21 16:50:30.961  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-21 16:50:30.961  5740  5788 I jxcore-log: 
,11-21 16:50:30.971  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-21 16:50:30.971  5740  5788 I jxcore-log: 
,11-21 16:50:30.978  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-21 16:50:30.978  5740  5788 I jxcore-log: 
,11-21 16:50:30.998  5740  5788 I jxcore-log: 2016-11-21 15:50:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-21 16:50:30.998  5740  5788 I jxcore-log: 
,11-21 16:50:31.005  5740  5788 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-21 16:50:31.006  5740  5788 I jxcore-log: 2016-11-21 15:50:31 - INFO testUtils: 'BLE multiple advertisement supported'
11-21 16:50:31.006  5740  5788 I jxcore-log: 
,11-21 16:50:31.129   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:50:31.290  5740  5788 I jxcore-log: 2016-11-21 15:50:31 - DEBUG CoordinatedClient: 'connected to the test server'
11-21 16:50:31.290  5740  5788 I jxcore-log: 
,11-21 16:50:33.109  3626  3626 I ConfigService: onDestroy
,11-21 16:50:34.157   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:50:36.074   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=214437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:50:39.892   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 16:50:39.892   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 16:50:44.148   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:50:48.835   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=227197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:50:49.894   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:50.895   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:51.896   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:52.897   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:53.898   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:50:54.899   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-21 16:50:59.900   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:00.901   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:01.275   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=239637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:51:01.902   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:02.903   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:03.905   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:04.906   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-21 16:51:13.955   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=252317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:51:14.907   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:15.908   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:16.909   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:17.910   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:18.912   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:19.913   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-21 16:51:24.153   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:51:26.301   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=264664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:51:34.913   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:35.915   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:36.916   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:37.918   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:38.919   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:51:39.919   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 16:51:44.153   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:51:59.921   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:00.922   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:01.924   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:02.925   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:03.926   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:03.981   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=302343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:52:04.927   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 16:52:16.355   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=314717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:52:24.158   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:52:28.995   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=327357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:52:29.928   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 16:52:29.928   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 16:52:41.381   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=339743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:52:44.161   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:52:44.929   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:45.931   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:46.932   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:47.933   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:48.934   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:49.935   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-21 16:52:54.062   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=352424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:52:54.937   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:55.938   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:56.939   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:57.940   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:58.942   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:52:59.942   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-21 16:53:04.164   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:53:06.408   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=364770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:53:09.944   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:10.945   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:11.947   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:12.948   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:13.950   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:14.951   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-21 16:53:19.075   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=377437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:53:29.952   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:30.953   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:31.450   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=389811, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:53:31.955   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:32.956   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:33.957   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:34.958   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-21 16:53:41.830   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:53:44.142   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=402504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:53:44.169   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:53:44.874   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:53:49.555   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=407917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-21 16:53:54.959   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:55.961   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:56.962   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:57.964   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:58.965   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:53:59.966   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-21 16:54:04.170   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:54:09.135   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=427497, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:54:21.528   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=439890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-21 16:54:24.173   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:54:24.966   539   539 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-21 16:54:24.967   539   539 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-21 16:54:31.836  5740  5788 I jxcore-log: 2016-11-21 15:54:31 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-21 16:54:31.836  5740  5788 I jxcore-log: 
,11-21 16:54:32.021  5740  5788 I jxcore-log: 2016-11-21 15:54:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:32.021  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:32.021  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:32.021  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:32.021  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:32.021  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:32.021  5740  5788 I jxcore-log: 
,11-21 16:54:32.026  5740  5788 I jxcore-log: 2016-11-21 15:54:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:32.026  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:32.026  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:32.026  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:32.026  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:32.026  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:32.026  5740  5788 I jxcore-log: 
,11-21 16:54:32.577  5740  5788 I jxcore-log: 2016-11-21 15:54:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:32.577  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:32.577  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:32.577  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:32.577  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:32.577  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:32.577  5740  5788 I jxcore-log: 
,11-21 16:54:32.582  5740  5788 I jxcore-log: 2016-11-21 15:54:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:32.582  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:32.582  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:32.582  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:32.582  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:32.582  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:32.582  5740  5788 I jxcore-log: 
,11-21 16:54:33.137  5740  5788 I jxcore-log: 2016-11-21 15:54:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:33.137  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:33.137  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:33.137  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:33.137  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:33.137  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:33.137  5740  5788 I jxcore-log: 
,11-21 16:54:33.141  5740  5788 I jxcore-log: 2016-11-21 15:54:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:33.141  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:33.141  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:33.141  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:33.141  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:33.141  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:33.141  5740  5788 I jxcore-log: 
,11-21 16:54:34.178  5740  5788 I jxcore-log: 2016-11-21 15:54:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:34.178  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:34.178  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:34.178  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:34.178  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:34.178  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:34.178  5740  5788 I jxcore-log: 
,11-21 16:54:34.182  5740  5788 I jxcore-log: 2016-11-21 15:54:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:34.182  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:34.182  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:34.182  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:34.182  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:34.182  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:34.182  5740  5788 I jxcore-log: 
,11-21 16:54:34.195   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=452557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-21 16:54:35.226  5740  5788 I jxcore-log: 2016-11-21 15:54:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:35.226  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:35.226  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:35.226  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:35.226  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:35.226  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:35.226  5740  5788 I jxcore-log: 
,11-21 16:54:35.230  5740  5788 I jxcore-log: 2016-11-21 15:54:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:35.230  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:35.230  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:35.230  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:35.230  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:35.230  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:35.230  5740  5788 I jxcore-log: 
,11-21 16:54:36.267  5740  5788 I jxcore-log: 2016-11-21 15:54:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:36.267  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:36.267  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:36.267  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:36.267  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:36.267  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:36.267  5740  5788 I jxcore-log: 
,11-21 16:54:36.272  5740  5788 I jxcore-log: 2016-11-21 15:54:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:36.272  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:36.272  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:36.272  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:36.272  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:36.272  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:36.272  5740  5788 I jxcore-log: 
,11-21 16:54:36.316   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:54:37.302  5740  5788 I jxcore-log: 2016-11-21 15:54:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:37.302  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:37.302  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:37.302  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:37.302  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:37.302  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:37.302  5740  5788 I jxcore-log: 
,11-21 16:54:37.307  5740  5788 I jxcore-log: 2016-11-21 15:54:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:37.307  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:37.307  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:37.307  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:37.307  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:37.307  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:37.307  5740  5788 I jxcore-log: 
,11-21 16:54:38.340  5740  5788 I jxcore-log: 2016-11-21 15:54:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:38.340  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:38.340  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:38.340  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:38.340  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:38.340  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:38.340  5740  5788 I jxcore-log: 
,11-21 16:54:38.347  5740  5788 I jxcore-log: 2016-11-21 15:54:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:38.347  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:38.347  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:38.347  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:38.347  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:38.347  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:38.347  5740  5788 I jxcore-log: 
,11-21 16:54:39.349   934  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-21 16:54:39.383  5740  5788 I jxcore-log: 2016-11-21 15:54:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:39.383  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:39.383  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:39.383  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:39.383  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:39.383  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:39.383  5740  5788 I jxcore-log: 
,11-21 16:54:39.386  5740  5788 I jxcore-log: 2016-11-21 15:54:39 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:39.386  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:39.386  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:39.386  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:39.386  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:39.386  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:39.386  5740  5788 I jxcore-log: 
,11-21 16:54:40.221   934  6005 D NetlinkSocketObserver: NeighborEvent{elapsedMs=458583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-21 16:54:40.455  5740  5788 I jxcore-log: 2016-11-21 15:54:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:40.455  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:40.455  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:40.455  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:40.455  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:40.455  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:40.455  5740  5788 I jxcore-log: 
,11-21 16:54:40.460  5740  5788 I jxcore-log: 2016-11-21 15:54:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:40.460  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:40.460  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:40.460  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:40.460  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:40.460  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:40.460  5740  5788 I jxcore-log: 
,11-21 16:54:41.502  5740  5788 I jxcore-log: 2016-11-21 15:54:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:41.502  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:41.502  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:41.502  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:41.502  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:41.502  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:41.502  5740  5788 I jxcore-log: 
,11-21 16:54:41.509  5740  5788 I jxcore-log: 2016-11-21 15:54:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:41.509  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:41.509  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:41.509  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:41.509  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:41.509  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:41.509  5740  5788 I jxcore-log: 
,11-21 16:54:42.649  5740  5788 I jxcore-log: 2016-11-21 15:54:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:42.649  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:42.649  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:42.649  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:42.649  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:42.649  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:42.649  5740  5788 I jxcore-log: 
,11-21 16:54:42.656  5740  5788 I jxcore-log: 2016-11-21 15:54:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:42.656  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:42.656  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:42.656  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:42.656  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:42.656  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:42.656  5740  5788 I jxcore-log: 
,11-21 16:54:43.684  5740  5788 I jxcore-log: 2016-11-21 15:54:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:43.684  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:43.684  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:43.684  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:43.684  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:43.684  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:43.684  5740  5788 I jxcore-log: 
,11-21 16:54:43.689  5740  5788 I jxcore-log: 2016-11-21 15:54:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:43.689  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:43.689  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:43.689  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:43.689  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:43.689  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:43.689  5740  5788 I jxcore-log: 
,11-21 16:54:44.176   934  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-21 16:54:44.722  5740  5788 I jxcore-log: 2016-11-21 15:54:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:44.722  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:44.722  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:44.722  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:44.722  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:44.722  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:44.722  5740  5788 I jxcore-log: 
,11-21 16:54:44.727  5740  5788 I jxcore-log: 2016-11-21 15:54:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:44.727  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:44.727  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:44.727  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:44.727  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:44.727  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:44.727  5740  5788 I jxcore-log: 
,11-21 16:54:44.968   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:54:45.760  5740  5788 I jxcore-log: 2016-11-21 15:54:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-21 16:54:45.760  5740  5788 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-21 16:54:45.760  5740  5788 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-21 16:54:45.760  5740  5788 I jxcore-log: emit@events.js:82:1
11-21 16:54:45.760  5740  5788 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-21 16:54:45.760  5740  5788 I jxcore-log: emit@events.js:82:1'
11-21 16:54:45.760  5740  5788 I jxcore-log: 
,11-21 16:54:45.773  5740  5788 E jxcore  : Error!: error is undefined
11-21 16:54:45.773  5740  5788 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"223","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-21 16:54:45.778  5740  5788 I jxcore-log: 2016-11-21 15:54:45 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-21 16:54:45.778  5740  5788 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:223:1
11-21 16:54:45.778  5740  5788 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-21 16:54:45.778  5740  5788 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-21 16:54:45.778  5740  5788 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-21 16:54:45.778  5740  5788 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-21 16:54:45.778  5740  5788 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-21 16:54:45.778  5740  5788 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-21 16:54:45.780  5740  5788 I jxcore-log: 2016-11-21 15:54:45 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-21 16:54:45.780  5740  5788 I jxcore-log: 
,11-21 16:54:45.784  5740  5788 E jxcore-log: TypeError: 
11-21 16:54:45.784  5740  5788 E jxcore-log: error is undefined
11-21 16:54:45.784  5740  5788 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 223:0)
11-21 16:54:45.784  5740  5788 E jxcore-log: 
,11-21 16:54:45.879   934  3927 I WindowState: WIN DEATH: Window{d64740e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-21 16:54:45.879   934  3203 D GraphicsStats: Buffer count: 2
11-21 16:54:45.879   934  3023 D WifiService: Client connection lost with reason: 4
,11-21 16:54:45.891   531   531 I Zygote  : Process 5740 exited cleanly (139)
11-21 16:54:45.895   934   945 I ActivityManager: Process com.test.thalitest (pid 5740) has died
,11-21 16:54:45.899   934   945 W ActivityManager: Force removing ActivityRecord{f974957 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-21 16:54:45.942   934  3912 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5740 uid 10077
,11-21 16:54:45.940  3912  3912 W Binder_B: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[27341]" dev="sockfs" ino=27341 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-21 16:54:45.940  3912  3912 W Binder_B: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[27341]" dev="sockfs" ino=27341 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-21 16:54:45.946  3711  3711 I Keyboard.Facilitator: onFinishInput()
,11-21 16:54:45.968   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:54:45.998  4023  6059 I MicroRecognitionRnrImpl: Starting detection.
,11-21 16:54:45.999  4023  6060 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@81dbd3c
,11-21 16:54:46.003   516  6062 I AudioFlinger: AudioFlinger's thread 0xf1f00000 ready to run
,11-21 16:54:46.006   516  3044 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-21 16:54:46.007  4023  6060 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@81dbd3c
,11-21 16:54:46.017   516  6062 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,11-21 16:54:46.017   516  6062 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-21 16:54:46.017   516  6062 I ACDB-LOADER: ACDB AFE returned = -19
,11-21 16:54:46.017   516  6062 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-21 16:54:46.017   516  6062 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-21 16:54:46.018   516  6062 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-21 16:54:46.026   516  6062 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-21 16:54:46.104  4023  4023 I HotwordWorkerImpl: onReady
,11-21 16:54:46.258  6053  6053 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-21 16:54:46.261  6053  6053 D AndroidRuntime: CheckJNI is OFF
,11-21 16:54:46.285  6053  6053 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-21 16:54:46.314  6053  6053 I Radio-JNI: register_android_hardware_Radio DONE
,11-21 16:54:46.329  6053  6053 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-21 16:54:46.339   934   947 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-21 16:54:46.481  3876  4073 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,11-21 16:54:46.494   934   957 I art     : Starting a blocking GC Explicit
,11-21 16:54:46.592   934   957 I art     : Explicit concurrent mark sweep GC freed 90812(6MB) AllocSpace objects, 68(1848KB) LOS objects, 33% free, 29MB/43MB, paused 1.645ms total 97.797ms
,11-21 16:54:46.615   934   957 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-21 16:54:46.618  6053  6053 I art     : System.exit called, status: 0
,11-21 16:54:46.619  6053  6053 I AndroidRuntime: VM exiting with result code 0.
,11-21 16:54:46.633   934   957 I ActivityManager: Start proc 6076:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-21 16:54:46.634   934   957 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-21 16:54:46.642  3711  3711 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-21 16:54:46.645  5865  5865 D BluetoothMapAppObserver: onReceive
11-21 16:54:46.645  5865  5865 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-21 16:54:46.652   934  2988 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-21 16:54:46.654  4091  4231 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-21 16:54:46.667  3711  6087 I Keyboard.Facilitator.DecoderInitializer: run()
,11-21 16:54:46.681  3832  3832 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-21 16:54:46.686  3452  6090 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-21 16:54:46.690  3711  6087 I Decoder : createOrResetDecoder
,11-21 16:54:46.735  3626  3626 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-21 16:54:46.736  3626  3626 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
11-21 16:54:46.736   934   934 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-21 16:54:46.737  5540  5540 W kworker/1:3: type=1400 audit(0.0:130): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:54:46.740  5540  5540 W kworker/1:3: type=1400 audit(0.0:131): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:54:46.756  3626  3626 I ConfigService: onCreate
,11-21 16:54:46.757  3876  3999 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-21 16:54:46.757  3902  6095 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-21 16:54:46.757  3902  6095 D AccountUtils: Clearing selected account for com.test.thalitest
11-21 16:54:46.754  5540  5540 W kworker/1:3: type=1400 audit(0.0:132): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-21 16:54:46.761   934   946 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-21 16:54:46.761  3626  6096 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
11-21 16:54:46.761   934   946 E PackageManager: Failed to write settings, restoring backup
11-21 16:54:46.761   934   946 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-21 16:54:46.761   934   946 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-21 16:54:46.761   934   946 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-21 16:54:46.761   934   946 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-21 16:54:46.761   934   946 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-21 16:54:46.761   934   946 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:54:46.761   934   946 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:54:46.761   934   946 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:54:46.763  3452  6090 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-21 16:54:46.765   934   947 E DropBoxManagerService: Can't write: system_server_wtf
11-21 16:54:46.765   934   947 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-21 16:54:46.765   934   947 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:54:46.765   934   947 E DropBoxManagerService: 	... 13 more
,11-21 16:54:46.774   934  3856 I ActivityManager: Start proc 6098:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-21 16:54:46.774  3452  6090 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-21 16:54:46.774  3452  6090 E AndroidRuntime: Process: android.process.acore, PID: 3452
11-21 16:54:46.774  3452  6090 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:54:46.774  3452  6090 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-21 16:54:46.775  3876  3999 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3876
11-21 16:54:46.775  3876  3999 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:54:46.775  3876  3999 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:54:46.779  3902  6095 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
11-21 16:54:46.789   934  3877 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-21 16:54:46.792  3711  6087 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-21 16:54:46.792  4023  5636 W SearchService: Abort, client detached.
,11-21 16:54:46.800  4023  4023 I HotwordDetector: Closing mic
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:54:46.800  3902  6108 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:54:46.800  4023  4250 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@81dbd3c
11-21 16:54:46.800  4023  6060 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:54:46.800  3902  6108 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: Can't write: system_app_crash
11-21 16:54:46.801   934  6110 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:54:46.801   934  6110 E DropBoxManagerService: 	... 5 more
11-21 16:54:46.801   934  6109 E DropBoxManagerService: Can't write: system_app_crash
11-21 16:54:46.801   934  6109 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:54:46.801   934  6109 E DropBoxManagerService: 	... 5 more
11-21 16:54:46.803  3902  6108 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-21 16:54:46.803  3902  6108 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
11-21 16:54:46.803  3902  6108 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-21 16:54:46.804  3902  6108 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-21 16:54:46.805  3902  6108 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-21 16:54:46.805  3902  6108 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-21 16:54:46.805  3902  6108 E AndroidRuntime: Process: com.google.android.gms, PID: 3902
11-21 16:54:46.805  3902  6108 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:54:46.805  3902  6108 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:54:46.810   771   771 W Binder_3: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[26519]" dev="sockfs" ino=26519 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 16:54:46.810   771   771 W Binder_3: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[26519]" dev="sockfs" ino=26519 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 16:54:46.815   934  6116 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-21 16:54:46.814   412   412 W Binder_1: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[31739]" dev="sockfs" ino=31739 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 16:54:46.814   412   412 W Binder_1: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[31739]" dev="sockfs" ino=31739 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:54:46.827  3902  6095 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-21 16:54:46.828  3902  6095 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-21 16:54:46.829  3902  6095 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-21 16:54:46.833   934  6118 E DropBoxManagerService: Can't write: system_app_crash
11-21 16:54:46.833   934  6118 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-21 16:54:46.833   934  6118 E DropBoxManagerService: 	... 5 more
,11-21 16:54:46.842  3902  3902 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-21 16:54:46.842  3902  3902 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-21 16:54:46.861   516  6062 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-21 16:54:46.863   516  6062 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-21 16:54:46.868   516  6062 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-21 16:54:46.868   516  6062 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-21 16:54:46.869   516  3044 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-21 16:54:46.871  4023  6059 I MicroRecognitionRnrImpl: Detection finished
,11-21 16:54:46.872  4023  4253 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-21 16:54:46.877  3902  3902 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-21 16:54:46.877  3902  3902 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-21 16:54:46.888  3902  6119 W BaseAppContext: Using Auth Proxy for data requests.
,11-21 16:54:46.896   934   945 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-21 16:54:46.903  3711  6087 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-21 16:54:46.913  3711  6087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-21 16:54:46.913  3711  6087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-21 16:54:46.915  3902  6119 W BaseAppContext: Using Auth Proxy for data requests.
,11-21 16:54:46.922  3711  6087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-21 16:54:46.922  3711  6087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-21 16:54:46.922  3711  6087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,11-21 16:54:46.922  3711  6087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-21 16:54:46.923  3711  6087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
11-21 16:54:46.923  3711  6087 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-21 16:54:46.923  3711  6087 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-21 16:54:46.923  3711  6087 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-21 16:54:46.923  3711  6087 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-21 16:54:46.923  3711  6087 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-21 16:54:46.948  4023  6120 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-21 16:54:46.969   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,11-21 16:54:47.018  3902  6095 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,11-21 16:54:47.049  3902  3902 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-21 16:54:47.076  3902  6130 I GMPM-SVC: App measurement is starting up
,11-21 16:54:47.079  3902  6130 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-21 16:54:47.080  3902  6130 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-21 16:54:47.082  3902  6130 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,11-21 16:54:47.083  3902  6130 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1022)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 16:54:47.083  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-21 16:54:47.083  3902  6130 E GMPM-SVC: Opening the database failed, dropping and recreating it
,11-21 16:54:47.091  3902  6130 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
,11-21 16:54:47.091  3902  6130 E SQLiteLog: (14) os_unix.c:31278: (2) open(/data/user/0/com.google.android.gms/databases/google_app_measurement2.db) - 
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/google_app_measurement2.db'.
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.j(SourceFile:271)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.d.d(SourceFile:877)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ao.run(SourceFile:397)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
11-21 16:54:47.093  3902  6130 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.al.run(SourceFile:257)
11-21 16:54:47.093  3902  6130 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-21 16:54:47.093  3902  6130 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
11-21 16:54:47.095  3902  6130 E GMPM-SVC: Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database: com.google.android.gms.measurement.internal.e.getWritableDatabase(SourceFile:1036)
,11-21 16:54:47.110   934   947 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{196b2f4 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{a074e06 3902 com.google.android.gms/10012/u0 remote:c4ef0e1}: process crashing
,11-21 16:54:47.117   934  3209 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3902 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-21 16:54:47.174  3902  6105 W DriveInitializer: Awaiting to be initialized
,11-21 16:54:47.175  3902  6135 W DriveInitializer: Background init thread started
11-21 16:54:47.176   384   484 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
