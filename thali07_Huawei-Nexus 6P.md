#### Test 8962479671c5ab8_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-04 14:14:29.932  3954  4139 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
11-04 14:14:30.003  3954  4139 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
,11-04 14:14:30.514  5527  5527 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-04 14:14:30.519  5527  5527 D AndroidRuntime: CheckJNI is OFF
11-04 14:14:30.547  5527  5527 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-04 14:14:30.590  5527  5527 I Radio-JNI: register_android_hardware_Radio DONE
11-04 14:14:30.604  5527  5527 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-04 14:14:30.615   928  3722 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-04 14:14:30.648  5527  5527 D AndroidRuntime: Shutting down VM
11-04 14:14:30.650  3878  3890 W SearchService: Abort, client detached.
11-04 14:14:30.661  3878  3878 I HotwordDetector: Closing mic
11-04 14:14:30.662  3878  4128 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@17822ed
11-04 14:14:30.663  3878  4134 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-04 14:14:30.675   928  3085 I ActivityManager: Start proc 5536:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-04 14:14:30.737   511  4137 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-04 14:14:30.739   511  4137 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-04 14:14:30.743   511  4137 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-04 14:14:30.743   511  4137 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-04 14:14:30.743   511  2924 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-04 14:14:30.746  3878  4133 I MicroRecognitionRnrImpl: Detection finished
11-04 14:14:30.746  3878  4131 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-04 14:14:30.768  5536  5536 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-04 14:14:30.787  5536  5536 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-04 14:14:30.845  5536  5536 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 5919-5974)
11-04 14:14:30.845  5536  5536 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 14:14:30.874  5536  5536 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7233d4}
,11-04 14:14:30.875  5536  5536 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 14:14:30.876  5536  5536 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 14:14:30.885  5536  5536 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 14:14:30.886  5536  5536 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 14:14:30.934  5536  5536 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 14:14:30.947  5536  5536 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 14:14:30.948  5536  5536 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 14:14:30.948  5536  5536 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 14:14:30.948  5536  5536 I Adreno  : Build Date                       : 12/06/15
11-04 14:14:30.948  5536  5536 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 14:14:30.948  5536  5536 I Adreno  : Local Branch                     : mybranch17112971
11-04 14:14:30.948  5536  5536 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 14:14:30.948  5536  5536 I Adreno  : Remote Branch                    : NONE
11-04 14:14:30.948  5536  5536 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 14:14:30.995   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44688b:true
,11-04 14:14:31.022   406   406 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[15953]" dev="sockfs" ino=15953 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:14:31.026   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[15953]" dev="sockfs" ino=15953 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:14:31.036  5536  5536 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 14:14:31.044  5536  5536 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 14:14:31.086   724   724 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32192]" dev="sockfs" ino=32192 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:14:31.086   724   724 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32192]" dev="sockfs" ino=32192 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:31.089  5536  5573 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-04 14:14:31.089  3526  3526 W Binder_6: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[23251]" dev="sockfs" ino=23251 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:14:31.089  3526  3526 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[23251]" dev="sockfs" ino=23251 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:31.094  5536  5560 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 14:14:31.120  5536  5573 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 14:14:31.210   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +557ms
,11-04 14:14:31.212  3577  3577 I Keyboard.Facilitator: onFinishInput()
,11-04 14:14:31.206  3124  3124 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32928]" dev="sockfs" ino=32928 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:14:31.206  3124  3124 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[32928]" dev="sockfs" ino=32928 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:31.209  3738  3738 W Binder_9: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[32927]" dev="sockfs" ino=32927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:31.209  3738  3738 W Binder_9: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32927]" dev="sockfs" ino=32927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:14:31.256  5536  5536 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5536
,11-04 14:14:31.372  5536  5536 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 14:14:31.612  5536  5575 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -583272144
,11-04 14:14:31.627  5536  5575 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-04 14:14:31.627  5536  5575 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-04 14:14:31.627  5536  5575 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-04 14:14:31.627  5536  5575 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-04 14:14:31.627  5536  5575 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-04 14:14:31.627  5536  5575 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3b928a added. We now have 1 listener(s)
,11-04 14:14:31.633  5536  5575 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-04 14:14:31.636  5536  5575 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-04 14:14:31.637  5536  5575 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 14:14:31.637  5536  5575 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-04 14:14:31.642  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-04 14:14:31.643  5536  5575 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4221b71 added. We now have 1 listener(s)
11-04 14:14:31.643  5536  5575 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 14:14:31.650   928  2903 D WifiService: New client listening to asynchronous messages
,11-04 14:14:31.650  5536  5575 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 14:14:31.651  5536  5575 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-04 14:14:31.651  5536  5575 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-04 14:14:31.651  5536  5575 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-04 14:14:31.651  5536  5575 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-04 14:14:31.653  5536  5575 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:14:31.653  5536  5575 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 14:14:31.658  5536  5575 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-04 14:14:31.659  5536  5575 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:14:31.659  5536  5575 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:14:31.659  5536  5575 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:14:31.659  5536  5575 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:14:31.659  5536  5575 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:14:31.659  5536  5575 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:14:31.659  5536  5575 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:14:31.659  5536  5575 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:14:31.659  5536  5575 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
11-04 14:14:31.659  5536  5575 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 14:14:31.659  5536  5575 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-04 14:14:31.664  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:14:31.668  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:14:31.917  5536  5536 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-04 14:14:32.186  5536  5584 W jxcore-log: Initializing JXcore engine
,11-04 14:14:32.186  5536  5584 W jxcore-log: JXcore engine is ready
,11-04 14:14:32.209  5584  5584 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11672 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-04 14:14:32.209  5584  5584 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15476]" dev="sockfs" ino=15476 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-04 14:14:32.209  5584  5584 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-04 14:14:32.209  5584  5584 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30325]" dev="sockfs" ino=30325 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-04 14:14:32.221  5536  5584 W jxcore-log: Starting JXcore engine
,11-04 14:14:32.282  5536  5584 W jxcore-log: Platform android
11-04 14:14:32.282  5536  5584 W jxcore-log: 
,11-04 14:14:32.282  5536  5584 W jxcore-log: Process ARCH arm
11-04 14:14:32.282  5536  5584 W jxcore-log: 
,11-04 14:14:32.434  5536  5584 I jxcore-log: JXcore Cordova bridge is ready!
11-04 14:14:32.434  5536  5584 I jxcore-log: 
,11-04 14:14:32.435  5536  5584 W jxcore-log: JXcore engine is started
,11-04 14:14:32.442  5536  5575 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-04 14:14:32.448  5536  5536 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-04 14:14:32.805   928  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-04 14:14:34.097  3510  3510 I ConfigService: onDestroy
,11-04 14:14:35.667   928  3085 I ActivityManager: Killing 4976:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-04 14:14:36.858   928  2897 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-04 14:14:38.865   928  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-04 14:14:39.773   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:14:40.774   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:14:41.775   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:14:42.039  5536  5584 I jxcore-log: 2016-11-04 13:14:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-04 14:14:42.039  5536  5584 I jxcore-log: 
,11-04 14:14:42.041  5536  5584 I jxcore-log: 2016-11-04 13:14:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-04 14:14:42.041  5536  5584 I jxcore-log: 
,11-04 14:14:42.046  5536  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:14:42.046  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:14:42.046  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:14:42.046  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:14:42.046  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:14:42.046  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:14:42.046  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:14:42.046  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:14:42.047  5536  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:14:42.049  5536  5584 I jxcore-log: 2016-11-04 13:14:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-04 14:14:42.049  5536  5584 I jxcore-log: 
11-04 14:14:42.050  5536  5584 I jxcore-log: 2016-11-04 13:14:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-04 14:14:42.050  5536  5584 I jxcore-log: 
,11-04 14:14:42.302  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 14:14:42.302  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8467497 added. We now have 2 listener(s)
11-04 14:14:42.303  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:14:42.303  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 14:14:42.303  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 14:14:42.303  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-04 14:14:42.303  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14fd684 added. We now have 2 listener(s)
,11-04 14:14:42.303  5536  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-04 14:14:42.304  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-04 14:14:42.306  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:14:42.310  5536  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:14:42.310  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:14:42.310  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:14:42.310  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:14:42.310  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:14:42.310  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:14:42.310  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:14:42.310  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:14:42.312  5536  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:14:42.312  5536  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
11-04 14:14:42.313  5536  5584 D ExecuteNativeTests: Running unit tests
11-04 14:14:42.313  5536  5584 D BluetoothAdapter: enable(): BT is already enabled..!
11-04 14:14:42.314   928  4762 D WifiService: setWifiEnabled: true pid=5536, uid=10077
,11-04 14:14:42.314   928  4762 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-04 14:14:42.319  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:14:42.324  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:14:42.777   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:14:43.664  3878  5586 W CronetSyncConnectionRcs: Upload content type not set.
,11-04 14:14:43.733  4798  4843 D Finsky  : [192] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-04 14:14:43.735  4798  4798 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-04 14:14:43.738   928  3526 I ActivityManager: Killing 5320:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-04 14:14:43.777   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:14:44.778   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-04 14:14:52.319  5536  5584 I com.test.thalitest.ThaliTestRunner: Running UT
,11-04 14:14:52.385  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-04 14:14:52.386  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2680476 added. We now have 3 listener(s)
11-04 14:14:52.387  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:14:52.387  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 14:14:52.387  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 14:14:52.387  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 14:14:52.387  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea0a77 added. We now have 3 listener(s)
11-04 14:14:52.387  5536  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 14:14:52.388  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 14:14:52.391  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:14:52.395  5536  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:14:52.395  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:14:52.395  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:14:52.395  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:14:52.395  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:14:52.395  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:14:52.395  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:14:52.395  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:14:52.396  5536  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:14:52.397  5536  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 14:14:52.402  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:14:52.403  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:14:52.405  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-04 14:14:52.405  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 14:14:52.405  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:14:52.405  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:14:52.405  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:14:52.406  5536  5584 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-04 14:14:52.406  5536  5584 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 14:14:52.406  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 14:14:52.406  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:14:52.406  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:14:52.406  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:14:52.406  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,11-04 14:14:52.407  5536  5584 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-04 14:14:52.408  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
11-04 14:14:52.410  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-04 14:14:52.410  5536  5584 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 14:14:52.410  5536  5584 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 14:14:52.410  5536  5584 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-04 14:14:52.410  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-04 14:14:52.410  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:14:52.410  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:14:52.411  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 14:14:52.411  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:14:52.411  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 14:14:52.412  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:14:52.412  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:14:52.412  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-04 14:14:52.412  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:14:52.412  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,11-04 14:14:52.412  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:14:52.412  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 14:14:52.412  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:14:52.413  5536  5590 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:14:52.414  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:14:52.415  5536  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-04 14:14:52.415  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 14:14:52.417  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:14:52.417  5536  5590 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:14:52.419  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:14:52.420  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:14:52.421  5536  5590 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 14:14:52.416  4820  4820 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33823]" dev="sockfs" ino=33823 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:52.416  4820  4820 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33823]" dev="sockfs" ino=33823 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 14:14:52.426  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.426  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,11-04 14:14:52.426  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:14:52.427  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 D4
11-04 14:14:52.428  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:14:52.428  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.428  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.428  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.428  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:52.429  5536  5584 D BluetoothAdapter: STATE_ON
,11-04 14:14:52.431  4573  4585 D BtGatt.GattService: registerClient() - UUID=9a209adf-1e92-4a55-bdb5-5b43bb2f2810
,11-04 14:14:52.432  4573  4646 D BtGatt.GattService: onClientRegistered() - UUID=9a209adf-1e92-4a55-bdb5-5b43bb2f2810, clientIf=5
,11-04 14:14:52.435  5536  5576 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-04 14:14:52.437  4573  4648 D BtGatt.AdvertiseManager: message : 0
,11-04 14:14:52.441  4573  4648 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:14:52.456  4573  4646 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 14:14:52.465  4573  4646 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 14:14:52.466  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:52.467  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:52.467  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:14:52.467  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.467  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.467  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.467  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:52.467  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.467  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 14:14:52.468  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 14:14:52.468  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.468  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:52.468  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.468  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.469  5536  5584 I io.jxcore.node.ConnectionHelper: start: OK
11-04 14:14:52.469  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:14:52.469  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:14:52.469  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 14:14:52.470  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-04 14:14:52.470  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,11-04 14:14:52.470  5536  5536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-04 14:14:52.470  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-04 14:14:52.470  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:14:52.470  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-04 14:14:52.470  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:14:52.470  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 14:14:52.471  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-04 14:14:52.471  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 14:14:52.475  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 14:14:52.475  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:14:52.476  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-04 14:14:52.476  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 14:14:52.476  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:14:52.476  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-04 14:14:52.476  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 14:14:52.972  5536  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-04 14:14:52.973  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-04 14:14:52.973  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-04 14:14:52.973  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-04 14:14:52.973  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-04 14:14:52.973  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-04 14:14:52.973  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-04 14:14:52.974  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-04 14:14:52.974  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-04 14:14:52.974  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-04 14:14:52.974  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-04 14:14:52.974  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-04 14:14:52.975  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-04 14:14:52.975  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-04 14:14:52.975  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-04 14:14:52.975  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-04 14:14:52.975  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-04 14:14:52.975  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-04 14:14:52.976  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-04 14:14:52.976  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-04 14:14:52.976  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-04 14:14:52.976  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-04 14:14:52.976  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-04 14:14:52.976  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-04 14:14:52.976  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-04 14:14:52.977  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-04 14:14:52.977  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-04 14:14:52.977  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-04 14:14:52.977  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-04 14:14:52.977  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-04 14:14:52.977  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-04 14:14:52.978  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-04 14:14:52.978  5536  5536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-04 14:14:52.978  5536  5584 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 14:14:52.978  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-04 14:14:52.978  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 14:14:52.979  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:14:52.979  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:14:52.979  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 14:14:52.980  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:14:52.980  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 14:14:52.980  5536  5590 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 14:14:52.980  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:14:52.980  5536  5590 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 14:14:52.980  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 14:14:52.980  5536  5590 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:14:52.984  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 14:14:52.985  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 14:14:52.985  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 14:14:52.986  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.986  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.988  5536  5584 D BluetoothAdapter: STATE_ON
11-04 14:14:52.989  5536  5584 D BluetoothLeScanner: could not find callback wrapper
11-04 14:14:52.989  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 14:14:52.990  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.990  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:52.990  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 14:14:52.991  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:52.993  4573  4648 D BtGatt.AdvertiseManager: message : 1
11-04 14:14:52.995  4573  4648 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 14:14:53.007  4573  4646 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-04 14:14:53.007  4573  4646 D BtGatt.GattService: Client app is not null!
11-04 14:14:53.008  4573  4586 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 14:14:53.009  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 14:14:53.009  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.009  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 14:14:53.010  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.010  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.010  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.010  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 14:14:53.010  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:14:53.010  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.010  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.010  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 14:14:53.011  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.012  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:53.013  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:14:53.013  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.013  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.013  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:53.013  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.013  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.013  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:14:53.014  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 14:14:53.015  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:14:53.015  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.017  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.018  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.019  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.019  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 14:14:53.019  5536  5536 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 14:14:53.020  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-04 14:14:53.020  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 14:14:53.020  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:14:53.020  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:14:53.020  5536  5584 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 14:14:53.021  5536  5584 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 14:14:53.021  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 14:14:53.021  5536  5584 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-04 14:14:53.021  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:14:53.021  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-04 14:14:53.021  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:14:53.021  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:14:53.021  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 14:14:53.021  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:14:53.022  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 14:14:53.023  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:14:53.023  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:14:53.023  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:14:53.023  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:14:53.023  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:14:53.023  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 14:14:53.023  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:14:53.023  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 14:14:53.024  5536  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:14:53.027  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:14:53.028  5536  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:14:53.028  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 14:14:53.028  5536  5593 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 14:14:53.033  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 14:14:53.029  4586  4586 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32966]" dev="sockfs" ino=32966 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:53.034  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:14:53.034  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:14:53.035  5536  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 14:14:53.032  4586  4586 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32966]" dev="sockfs" ino=32966 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 14:14:53.036  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:53.036  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 14:14:53.036  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:14:53.036  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 D4
11-04 14:14:53.037  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:14:53.037  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.037  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.037  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.037  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:53.038  5536  5584 D BluetoothAdapter: STATE_ON
,11-04 14:14:53.040  4573  4820 D BtGatt.GattService: registerClient() - UUID=229776ad-4a27-43a4-bafe-afcb73cd2f6d
11-04 14:14:53.041  4573  4646 D BtGatt.GattService: onClientRegistered() - UUID=229776ad-4a27-43a4-bafe-afcb73cd2f6d, clientIf=5
,11-04 14:14:53.041  5536  5546 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-04 14:14:53.042  4573  4648 D BtGatt.AdvertiseManager: message : 0
11-04 14:14:53.045  4573  4648 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:14:53.056  4573  4646 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 14:14:53.062  4573  4646 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 14:14:53.063  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.063  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:53.063  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:14:53.063  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.063  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.063  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.063  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.064  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.064  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-04 14:14:53.065  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 14:14:53.065  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.066  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.066  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.066  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.066  5536  5584 I io.jxcore.node.ConnectionHelper: start: OK
11-04 14:14:53.067  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:14:53.067  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-04 14:14:53.067  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,11-04 14:14:53.067  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-04 14:14:53.067  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.067  5536  5536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:14:53.067  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.067  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:14:53.067  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 14:14:53.068  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.068  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.068  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,11-04 14:14:53.068  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.070  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.070  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:14:53.070  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.070  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.070  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.071  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-04 14:14:53.071  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 14:14:53.571  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-04 14:14:53.571  5536  5584 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 14:14:53.572  5536  5584 V io.jxcore.node.ConnectivityMonitor: start: Already started
,11-04 14:14:53.572  5536  5584 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-04 14:14:53.572  5536  5536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-04 14:14:53.572  5536  5584 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-04 14:14:53.572  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-04 14:14:53.573  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-04 14:14:53.573  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-04 14:14:53.573  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-04 14:14:53.573  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-04 14:14:53.573  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-04 14:14:53.573  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-04 14:14:53.573  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-04 14:14:53.573  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-04 14:14:53.573  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,11-04 14:14:53.573  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.576  4573  4648 D BtGatt.AdvertiseManager: message : 1
11-04 14:14:53.578  4573  4648 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 14:14:53.591  4573  4646 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-04 14:14:53.591  4573  4646 D BtGatt.GattService: Client app is not null!
,11-04 14:14:53.592  4573  4820 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 14:14:53.593  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 14:14:53.593  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.593  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 14:14:53.593  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.593  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.594  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:14:53.594  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.594  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 14:14:53.594  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:14:53.594  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 D4
11-04 14:14:53.594  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:14:53.595  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.595  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:53.595  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.595  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.596  5536  5584 D BluetoothAdapter: STATE_ON
,11-04 14:14:53.601  4573  4812 D BtGatt.GattService: registerClient() - UUID=0d902f11-c14b-4e06-b266-103b805b62d3
11-04 14:14:53.601  4573  4646 D BtGatt.GattService: onClientRegistered() - UUID=0d902f11-c14b-4e06-b266-103b805b62d3, clientIf=5
,11-04 14:14:53.602  5536  5546 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-04 14:14:53.608  4573  4648 D BtGatt.AdvertiseManager: message : 0
,11-04 14:14:53.612  4573  4648 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:14:53.628  4573  4646 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 14:14:53.637  4573  4646 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 14:14:53.638  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.638  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.638  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:14:53.638  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:53.638  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.638  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.638  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.638  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.638  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:14:53.638  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:14:53.639  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 14:14:53.639  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-04 14:14:53.639  5536  5584 I io.jxcore.node.ConnectionHelper: start: OK
11-04 14:14:53.639  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.639  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 14:14:53.639  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 14:14:53.639  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.639  5536  5536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:14:53.640  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.640  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,11-04 14:14:53.640  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:14:53.640  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.640  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.640  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 14:14:53.640  5536  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-04 14:14:53.640  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-04 14:14:53.640  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 14:14:53.640  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:14:53.640  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:14:53.640  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 14:14:53.641  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:14:53.641  5536  5593 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 14:14:53.641  5536  5593 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 14:14:53.641  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 14:14:53.641  5536  5593 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:14:53.641  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:14:53.641  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 14:14:53.641  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 14:14:53.641  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 14:14:53.641  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 14:14:53.641  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:14:53.641  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 14:14:53.641  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:14:53.641  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.641  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.642  5536  5584 D BluetoothAdapter: STATE_ON
11-04 14:14:53.642  5536  5584 D BluetoothLeScanner: could not find callback wrapper
11-04 14:14:53.642  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 14:14:53.643  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.643  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.643  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 14:14:53.643  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.644  4573  4648 D BtGatt.AdvertiseManager: message : 1
11-04 14:14:53.644  4573  4648 D BtGatt.AdvertiseManager: stop advertise for client 5
11-04 14:14:53.652  4573  4646 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-04 14:14:53.652  4573  4646 D BtGatt.GattService: Client app is not null!
11-04 14:14:53.653  4573  4586 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 14:14:53.653  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 14:14:53.653  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.653  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 14:14:53.653  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.653  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.654  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.654  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 14:14:53.654  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:14:53.654  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.654  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.654  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 14:14:53.654  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.655  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.655  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:14:53.655  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.655  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.655  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.655  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.655  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.656  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:14:53.656  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 14:14:53.657  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:14:53.657  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.658  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.658  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.658  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.659  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 14:14:53.659  5536  5536 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-04 14:14:53.659  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:14:53.659  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:14:53.659  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:14:53.661  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-04 14:14:53.661  5536  5584 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-04 14:14:53.663  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
11-04 14:14:53.663  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-04 14:14:53.664  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-04 14:14:53.664  5536  5584 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-04 14:14:53.665  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-04 14:14:53.665  5536  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-04 14:14:53.666  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-04 14:14:53.666  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 14:14:53.667  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:14:53.667  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:14:53.667  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:14:53.667  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-04 14:14:53.667  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:14:53.667  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:14:53.667  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:14:53.667  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-04 14:14:53.667  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:14:53.667  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:14:53.667  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-04 14:14:53.668  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-04 14:14:53.670  5536  5584 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-04 14:14:53.671  5536  5584 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 14:14:53.675  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-04 14:14:53.675  5536  5584 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-04 14:14:53.677  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-04 14:14:53.677  5536  5584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-04 14:14:53.677  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-04 14:14:53.678  5536  5584 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
11-04 14:14:53.678  5536  5584 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-04 14:14:53.678  5536  5584 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-04 14:14:53.678  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 14:14:53.678  5536  5584 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-04 14:14:53.678  5536  5584 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 14:14:53.678  5536  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-04 14:14:53.678  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 14:14:53.678  5536  5584 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-04 14:14:53.678  5536  5584 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-04 14:14:53.678  5536  5584 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-04 14:14:53.678  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-04 14:14:53.678  5536  5584 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-04 14:14:53.679  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-04 14:14:53.679  5536  5584 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-04 14:14:53.679  5536  5584 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-04 14:14:53.679  5536  5584 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-04 14:14:53.679  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-04 14:14:53.680  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:14:53.680  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:14:53.680  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 14:14:53.680  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:14:53.681  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 14:14:53.682  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:14:53.682  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:14:53.682  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:14:53.682  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:14:53.682  5536  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:14:53.682  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 14:14:53.682  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:14:53.682  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 14:14:53.683  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:14:53.683  5536  5597 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:14:53.682  4585  4585 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[30363]" dev="sockfs" ino=30363 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:53.682  4585  4585 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[30363]" dev="sockfs" ino=30363 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:53.686  5536  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 14:14:53.687  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:14:53.687  5536  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:14:53.687  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 14:14:53.691  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:14:53.692  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:14:53.692  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:14:53.693  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.694  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 14:14:53.694  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:14:53.694  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 D4
11-04 14:14:53.694  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:14:53.694  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.694  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.694  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.694  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.695  5536  5584 D BluetoothAdapter: STATE_ON
11-04 14:14:53.697  4573  4812 D BtGatt.GattService: registerClient() - UUID=8320053d-6ebe-4e30-9667-86b0e9ef8300
11-04 14:14:53.698  4573  4646 D BtGatt.GattService: onClientRegistered() - UUID=8320053d-6ebe-4e30-9667-86b0e9ef8300, clientIf=5
11-04 14:14:53.698  5536  5547 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-04 14:14:53.699  4573  4648 D BtGatt.AdvertiseManager: message : 0
11-04 14:14:53.701  4573  4648 D BtGatt.AdvertiseManager: starting multi advertising
11-04 14:14:53.711  4573  4646 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 14:14:53.716  4573  4646 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 14:14:53.717  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.717  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.717  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:14:53.717  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.717  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:53.717  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:53.717  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.717  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.717  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 14:14:53.719  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 14:14:53.719  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.720  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.720  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.720  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:53.720  5536  5584 I io.jxcore.node.ConnectionHelper: start: OK
11-04 14:14:53.720  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:14:53.720  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.721  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 14:14:53.721  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,11-04 14:14:53.721  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.721  5536  5536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:14:53.721  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.721  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:14:53.721  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 14:14:53.721  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.721  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.721  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-04 14:14:53.721  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 14:14:53.723  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.723  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:14:53.723  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.724  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.724  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:14:53.724  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 14:14:53.724  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 14:14:54.222  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 14:14:54.222  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-04 14:14:54.222  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:14:54.222  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 14:14:54.223  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:14:54.223  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-04 14:14:54.223  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:14:54.223  5536  5597 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 14:14:54.223  5536  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-04 14:14:54.224  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 14:14:54.224  5536  5597 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:14:54.224  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:14:54.224  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2680476 removed from the list
11-04 14:14:54.224  5536  5536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-04 14:14:54.224  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 14:14:54.224  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 14:14:54.225  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 14:14:54.225  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 14:14:54.225  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 14:14:54.225  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:14:54.225  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:54.225  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.227  5536  5584 D BluetoothAdapter: STATE_ON
11-04 14:14:54.228  5536  5584 D BluetoothLeScanner: could not find callback wrapper
11-04 14:14:54.228  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 14:14:54.228  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:54.228  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.228  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 14:14:54.228  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:54.230  4573  4648 D BtGatt.AdvertiseManager: message : 1
11-04 14:14:54.233  4573  4648 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 14:14:54.246  4573  4646 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-04 14:14:54.247  4573  4646 D BtGatt.GattService: Client app is not null!
11-04 14:14:54.248  4573  4820 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 14:14:54.249  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 14:14:54.249  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.249  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 14:14:54.249  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.249  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:54.250  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.250  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 14:14:54.250  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-04 14:14:54.250  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.250  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.250  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 14:14:54.250  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:54.252  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:54.253  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:14:54.253  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.253  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.253  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.253  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.253  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:54.253  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:14:54.253  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 14:14:54.255  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:14:54.255  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.256  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:54.257  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.257  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:54.257  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea0a77 removed from the list
11-04 14:14:54.257  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:14:54.257  5536  5584 D io.jxcore.node.ConnectivityMonitor: stop
11-04 14:14:54.257  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 14:14:54.257  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:14:54.257  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 14:14:54.759  5536  5536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 14:14:59.262  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-04 14:14:59.264  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-04 14:14:59.264  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:14:59.266  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 14:14:59.268  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-04 14:14:59.268  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-04 14:14:59.268  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-04 14:14:59.268  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-04 14:14:59.269  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 14:14:59.269  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:14:59.269  5536  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-04 14:14:59.270  5536  5598 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:14:59.272  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-04 14:14:59.273  5536  5584 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-04 14:14:59.274  5536  5584 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-04 14:14:59.275  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-04 14:14:59.272  4812  4812 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30374]" dev="sockfs" ino=30374 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:59.276  4812  4812 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[30374]" dev="sockfs" ino=30374 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:14:59.275  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-04 14:14:59.276  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-04 14:14:59.277  5536  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-04 14:14:59.278  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-04 14:14:59.286  5536  5584 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-04 14:14:59.286  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 14:14:59.287  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:14:59.287  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-04 14:14:59.287  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 14:14:59.287  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-04 14:14:59.287  5536  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 14:14:59.287  5536  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 14:14:59.287  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-04 14:14:59.287  5536  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:14:59.287  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:14:59.287  5536  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2680476 not in the list
,11-04 14:14:59.288  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 14:14:59.288  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-04 14:14:59.288  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:14:59.288  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-04 14:14:59.288  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:14:59.288  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 14:14:59.288  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-04 14:14:59.288  5536  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-04 14:14:59.288  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:14:59.288  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:59.290  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:14:59.290  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:14:59.291  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:59.291  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:14:59.291  5536  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea0a77 not in the list
11-04 14:14:59.291  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-04 14:14:59.291  5536  5584 D io.jxcore.node.ConnectivityMonitor: stop
11-04 14:14:59.291  5536  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 14:14:59.291  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:14:59.291  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:14:59.291  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:14:59.293  5536  5584 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-04 14:14:59.294  5536  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-04 14:14:59.294  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 14:14:59.294  5536  5584 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-04 14:14:59.294  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-04 14:14:59.294  5536  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-04 14:14:59.294  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-04 14:14:59.295  5536  5584 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-04 14:14:59.296  5536  5584 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-04 14:14:59.298  5536  5584 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-04 14:14:59.299  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-04 14:14:59.299  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-04 14:14:59.300  5536  5584 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
,11-04 14:14:59.300  5536  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-04 14:14:59.300  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-04 14:14:59.302  5536  5584 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-04 14:14:59.302  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-04 14:14:59.302  5536  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-04 14:14:59.302  5536  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-04 14:14:59.303  5536  5584 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-04 14:14:59.303  5536  5584 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-04 14:14:59.303  5536  5584 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-04 14:14:59.304  5536  5584 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
,11-04 14:14:59.304  5536  5584 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-04 14:14:59.305  5536  5584 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-04 14:14:59.305  5536  5584 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-04 14:14:59.305  5536  5584 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-04 14:14:59.306  5536  5584 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,11-04 14:14:59.306  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 14:14:59.306  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc7f67 added. We now have 3 listener(s)
11-04 14:14:59.308  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:14:59.308  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 14:14:59.308  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 14:14:59.308  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 14:14:59.309  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbdd114 added. We now have 3 listener(s)
11-04 14:14:59.309  5536  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 14:14:59.310  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 14:14:59.314  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:14:59.319  5536  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:14:59.319  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:14:59.319  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:14:59.319  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:14:59.319  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:14:59.319  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:14:59.319  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:14:59.319  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:14:59.320  5536  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:14:59.321  5536  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 14:14:59.323  5536  5584 D BluetoothAdapter: enable(): BT is already enabled..!
11-04 14:14:59.323   928  3124 D WifiService: setWifiEnabled: true pid=5536, uid=10077
11-04 14:14:59.323   928  3124 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-04 14:14:59.325  5536  5584 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
11-04 14:14:59.325  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:14:59.328  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:14:59.329  5536  5584 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,11-04 14:14:59.330  5536  5584 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,11-04 14:14:59.333   928  4763 D WifiService: setWifiEnabled: false pid=5536, uid=10077
,11-04 14:14:59.333   928  4763 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:14:59.338   928  2897 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-04 14:14:59.338   928  2897 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-04 14:14:59.338   928  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 14:14:59.338   928  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:14:59.347   928  5296 D DhcpClient: Clearing IP address
,11-04 14:14:59.347   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-04 14:14:59.351   506   921 D CommandListener: Setting iface cfg
11-04 14:14:59.352   928  5297 D DhcpClient: Receive thread stopped
11-04 14:14:59.359  3510  5347 V NativeCrypto: Read error: ssl=0x7f638df280: I/O error during system call, Connection timed out
,11-04 14:14:59.362  3510  5347 V NativeCrypto: SSL shutdown failed: ssl=0x7f638df280: I/O error during system call, Broken pipe
,11-04 14:14:59.364   928   939 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-04 14:14:59.365   928  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-04 14:14:59.365   928  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-04 14:14:59.366   928  5294 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-04 14:14:59.371   532   532 E Parcel  : Reading a NULL string not supported here.
11-04 14:14:59.372   928  5294 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-04 14:14:59.377   928   928 D RttService: SCAN_AVAILABLE : 1
11-04 14:14:59.377   928  2998 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 14:14:59.379   928  2904 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-04 14:14:59.380   928   939 I ActivityManager: Killing 5333:com.android.chrome/u0a39 (adj 15): empty #17
,11-04 14:14:59.386  3642  3784 W QCNEJ   : |CORE| network lost: 100
11-04 14:14:59.386  3642  3784 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-04 14:14:59.397   928  2897 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-04 14:14:59.420   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:14:59.423   928  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 14:14:59.437   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:14:59.437   506   921 D CommandListener: Clearing all IP addresses on wlan0
11-04 14:14:59.438   506   921 D TetherController: Setting IP forward enable = 0
,11-04 14:14:59.438   928  2904 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-04 14:14:59.439   928  2904 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:14:59.443   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-04 14:14:59.444  5182  5182 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@1d9a600 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-04 14:14:59.448  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:14:59.448  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:14:59.448  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:14:59.448  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:14:59.448  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:14:59.448  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:14:59.448  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:14:59.448  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:14:59.451  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:14:59.455  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:14:59.455  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:14:59.455  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:14:59.455  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:14:59.455  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:14:59.455  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:14:59.455  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:14:59.455  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:14:59.457  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:14:59.461  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:14:59.461  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:14:59.461  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:14:59.461  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:14:59.461  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:14:59.461  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:14:59.461  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:14:59.461  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:14:59.461  3878  3878 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-04 14:14:59.463  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:14:59.465  3954  3954 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-04 14:14:59.469  3954  3954 D SystemUpdateService: onCreate
11-04 14:14:59.472  3954  3954 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 14:14:59.475  3954  5617 I SystemUpdateService: active receiver: enabled
,11-04 14:14:59.479  3954  3954 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-04 14:14:59.484  3954  4166 I iu.UploadsManager: num queued entries: 0
,11-04 14:14:59.484  3954  4166 I iu.UploadsManager: num updated entries: 0
11-04 14:14:59.485  3954  4166 I iu.SyncManager: NEXT; no task
,11-04 14:14:59.487  3954  3954 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-04 14:14:59.488  3954  3954 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-04 14:14:59.490  3954  5617 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 14:14:59.492  3954  5617 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-04 14:14:59.492  3954  5617 I SystemUpdateService: now status is 0 (complete)
11-04 14:14:59.492  3954  5617 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 14:14:59.492  3954  5617 I SystemUpdateService: file has been verified
11-04 14:14:59.492  3954  5617 I SystemUpdateService: OTA package size = 21989297
,11-04 14:14:59.497  3954  5617 I SystemUpdateService: showing system update notification
,11-04 14:14:59.500   928   939 I ActivityManager: Start proc 5619:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-04 14:14:59.511   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 14:14:59.513  3954  3954 D SystemUpdateService: onDestroy
,11-04 14:14:59.531  5619  5619 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-04 14:14:59.534  5619  5619 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-04 14:14:59.541  5619  5619 D SprintDMHelper: simOperator: 
,11-04 14:14:59.542  5619  5619 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 14:14:59.553   928  3527 I ActivityManager: Start proc 5631:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-04 14:14:59.554   928  3527 I ActivityManager: Killing 4391:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-04 14:14:59.650   928  4762 I ActivityManager: Killing 5044:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-04 14:14:59.793  5536  5536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 14:14:59.839   928   939 D WifiService: setWifiEnabled: false pid=5536, uid=10077
11-04 14:14:59.839   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:15:00.342   928  3526 D WifiService: setWifiEnabled: false pid=5536, uid=10077
,11-04 14:15:00.342   928  3526 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:15:00.525   506   921 E Netd    : netlink response contains error (No such file or directory)
11-04 14:15:00.527   928  2904 E NetdConnector: NDC Command {107 network destroy 100} took too long (1087ms)
,11-04 14:15:00.527   928  2904 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-04 14:15:00.527   928  2904 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-04 14:15:00.528   928  2897 E NetdConnector: NDC Command {108 interface ipv6 wlan0 disable} took too long (1088ms)
,11-04 14:15:00.529   928  2897 D DhcpClient: doQuit
11-04 14:15:00.529   928  2897 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 14:15:00.530   928  5296 D DhcpClient: onQuitting
11-04 14:15:00.532   506   921 D TetherController: Setting IP forward enable = 0
11-04 14:15:00.532  3366  3366 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-04 14:15:00.533   928  2877 E NetdConnector: NDC Command {109 bandwidth setglobalalert 2097152} took too long (1085ms)
,11-04 14:15:00.542  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:00.542  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:00.542  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:00.542  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:15:00.542  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:00.542  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:00.542  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:00.542  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:00.545  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:00.549  3366  3366 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-04 14:15:00.550  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:00.550  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:00.550  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:00.550  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:15:00.550  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:00.550  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:00.550  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:00.550  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:00.553  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:00.554  3366  3366 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-04 14:15:00.560  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:00.560  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:00.560  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:00.560  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:15:00.560  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:00.560  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:00.560  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:00.560  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:00.560   928   941 I ActivityManager: Start proc 5651:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-04 14:15:00.563  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:00.572  3366  3366 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 14:15:00.581  3366  3366 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 14:15:00.590  5651  5651 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-04 14:15:00.596   928  3526 I ActivityManager: Killing 5364:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-04 14:15:00.684   928  2897 D wifi    : In wifi stop Hal
,11-04 14:15:00.684   928  2897 D wifi    : halHandle = 0x7f61a66680, mVM = 0x7f7e0cd140, mCls = 0x100a02
,11-04 14:15:00.684   928  3365 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 14:15:00.685   928  3365 D WifiHAL : Got a signal to exit!!!
11-04 14:15:00.685   928  3365 I WifiHAL : Exit wifi_event_loop
11-04 14:15:00.687   928  2897 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-04 14:15:00.687   928  2897 E WifiHAL : Event processing terminated
11-04 14:15:00.687   928  2897 D wifi    : In wifi cleaned up handler
11-04 14:15:00.687   928  2897 I WifiHAL : Internal cleanup completed
11-04 14:15:00.691  3864  4123 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 14:15:00.693  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:00.695  4433  4433 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 14:15:00.696  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:00.697  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:00.717   928  3365 D wifi    : set interface wlan0 flags (DOWN)
,11-04 14:15:00.718   928  2897 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 14:15:00.846  5536  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:00.848   928  3738 D WifiService: setWifiEnabled: true pid=5536, uid=10077
11-04 14:15:00.848   928  3738 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:15:00.921   928   945 D Tethering: InitialState.processMessage what=4
,11-04 14:15:00.925   506   921 D SoftapController: Softap fwReload - Ok
,11-04 14:15:00.931   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 14:15:00.931   506   921 D CommandListener: Setting iface cfg
11-04 14:15:00.931   506   921 D CommandListener: Trying to bring down wlan0
,11-04 14:15:00.933   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-04 14:15:00.939   928  2897 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 14:15:01.029   928   941 I ActivityManager: Start proc 5665:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,11-04 14:15:01.079  5665  5665 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,11-04 14:15:01.105  5665  5665 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
11-04 14:15:01.105  5665  5665 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-04 14:15:01.105  5665  5665 I GAv4    :   adb logcat -s GAv4
,11-04 14:15:01.119  5665  5665 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,11-04 14:15:01.125  5665  5665 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-04 14:15:01.137  5665  5680 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,11-04 14:15:01.146   928  3085 I ActivityManager: Killing 5182:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-04 14:15:01.353   928  3527 D WifiService: setWifiEnabled: true pid=5536, uid=10077
11-04 14:15:01.356   928  3527 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:15:01.528   928  2897 D wifi    : set interface wlan0 flags (UP)
,11-04 14:15:01.528   928  2897 I WifiHAL : Initializing wifi
11-04 14:15:01.528   928  2897 I WifiHAL : Creating socket
,11-04 14:15:01.535   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 14:15:01.536   928  2897 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-04 14:15:01.536   928  2897 D wifi    : Did set static halHandle = 0x7f61a66680
,11-04 14:15:01.536   928  2897 D wifi    : halHandle = 0x7f61a66680, mVM = 0x7f7e0cd140, mCls = 0x198a
,11-04 14:15:01.536   928  2897 D wifi    : array field set
11-04 14:15:01.537   928  2897 I WifiNative-HAL: interface[0] = wlan0
11-04 14:15:01.541   928  5681 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547099141760
,11-04 14:15:01.541   928  5681 D wifi    : waitForHalEvents called, vm = 0x7f7e0cd140, obj = 0x198a, env = 0x7f65422900
,11-04 14:15:01.614  5682  5682 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 14:15:01.642   928  2897 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 14:15:01.651  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:01.653  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:01.656  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:01.683  5682  5682 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 14:15:01.690  5682  5682 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 14:15:01.690  5682  5682 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 14:15:01.701   928  2897 D WifiConfigStore: Loading config and enabling all networks 
,11-04 14:15:01.705  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:01.705  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:01.705  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:01.705  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:01.705  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:01.705  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:01.705  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:01.705  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:01.708  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:01.710  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:01.710  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:01.710  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:01.710  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:01.710  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:01.710  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:01.710  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:01.710  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:01.712  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:01.714  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:01.714  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:01.714  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:01.714  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:01.714  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:01.714  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:01.714  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:01.714  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:01.715   928  2897 D WifiConfigStore: loaded 0 passpoint configs
11-04 14:15:01.716   928  2897 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-04 14:15:01.716   928  2897 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-04 14:15:01.716   928  2897 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-04 14:15:01.716  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:01.717   928  2897 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-04 14:15:01.717   928  2897 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-04 14:15:01.718   928  2897 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 14:15:01.718   928  2897 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 14:15:01.718   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 14:15:01.718   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 14:15:01.718   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-04 14:15:01.718   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 14:15:01.718   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 14:15:01.720   928  2897 D WifiNative-HAL: Setting external_sim to 1
,11-04 14:15:01.721   928  2897 D wifi    : setting dfs flag to true, 0x7f65361b80
11-04 14:15:01.721   928  2897 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 14:15:01.721   928  2897 D wifi    : setting scan oui 0x7f65361b80
11-04 14:15:01.721   928  2897 D WifiHAL : Sending mac address OUI
,11-04 14:15:01.721  4433  4433 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 14:15:01.724   928  2897 E native  : do suspend false
,11-04 14:15:01.730   928  2897 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-04 14:15:01.730   928   928 D RttService: SCAN_AVAILABLE : 3
,11-04 14:15:01.731   928  2998 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 14:15:01.734   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-04 14:15:01.735   506   921 D CommandListener: Setting iface cfg
,11-04 14:15:01.738   928  2882 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '119 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 119 Failed to set address (No such device)'
,11-04 14:15:01.738   928  2882 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 14:15:01.743   928  2882 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 14:15:01.744   928  2882 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 14:15:01.760   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=106889 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=25 mControllerEnergyUsed=95 }
,11-04 14:15:01.861  5536  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:01.868  4573  4642 D BluetoothAdapterState: Current state: ON, message: 23
,11-04 14:15:01.868  4573  4642 D BluetoothAdapterProperties: Setting state to 13
11-04 14:15:01.868  4573  4642 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 14:15:01.869  4573  4642 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 14:15:01.871  4573  4642 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:15:01.872  4573  4573 D BluetoothMapService: onReceive
,11-04 14:15:01.872  4573  4573 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-04 14:15:01.873  4573  4573 D BluetoothMapService: STATE_TURNING_OFF
11-04 14:15:01.873  4573  4573 D BluetoothMapService: MAP Service closeService in
11-04 14:15:01.873  4573  4573 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 14:15:01.873  4573  4573 D ObexServerSockets0: shutdown(block = true)
11-04 14:15:01.876  4573  4573 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 14:15:01.877  4573  4823 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-04 14:15:01.877  4573  4573 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 14:15:01.877  4573  4824 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 14:15:01.877  4573  4804 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 14:15:01.879  4573  4573 I BtOppRfcommListener: stopping Accept Thread
11-04 14:15:01.880  4573  5226 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-04 14:15:01.882  4573  5226 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-04 14:15:01.883  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:15:01.883  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:01.883  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:01.883  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:01.883  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:01.883  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:15:01.883  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:01.883  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:01.883  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:01.885  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:15:01.886  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:01.890  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:15:01.890  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:01.890  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:01.890  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:01.890  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:01.890  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:15:01.890  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:01.890  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:01.890  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:01.892  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:15:01.892  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:01.895  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:15:01.895  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:01.895  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:01.895  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:01.895  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:01.895  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:15:01.895  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:01.895  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:01.895  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:01.896  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:15:01.896  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:01.900   928   941 I ActivityManager: Start proc 5686:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-04 14:15:01.901  4573  4646 D BluetoothAdapterProperties: Scan Mode:20
11-04 14:15:01.901  4573  4642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 14:15:01.906  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:01.906  4573  4573 D HeadsetService: Received stop request...Stopping profile...
11-04 14:15:01.907   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 14:15:01.908  3068  3082 D BluetoothHeadset: Proxy object disconnected
11-04 14:15:01.908  3068  3068 D HeadsetProfile: Bluetooth service disconnected
11-04 14:15:01.908   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 14:15:01.908  3679  3701 D BluetoothHeadset: Proxy object disconnected
11-04 14:15:01.908   928   928 D BluetoothHeadset: Proxy object disconnected
11-04 14:15:01.909  4573  4573 D A2dpService: Received stop request...Stopping profile...
11-04 14:15:01.909  4573  4815 D A2dpStateMachine: Exit Disconnected: -1
11-04 14:15:01.910  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:01.910   928   928 D BluetoothA2dp: Proxy object disconnected
11-04 14:15:01.911  3068  3068 D BluetoothA2dp: Proxy object disconnected
11-04 14:15:01.912  4573  4573 D HidService: Received stop request...Stopping profile...
11-04 14:15:01.912  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:01.912  4573  4573 D HidService: Stopping Bluetooth HidService
11-04 14:15:01.913  3068  3068 D BluetoothInputDevice: Proxy object disconnected
11-04 14:15:01.913  3068  3068 D HidProfile: Bluetooth service disconnected
11-04 14:15:01.913  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:01.913  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:01.913  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:01.913  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:01.913  4573  4573 D HealthService: Received stop request...Stopping profile...
11-04 14:15:01.916  4573  4573 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 14:15:01.918  4573  4573 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 14:15:01.918  4573  4776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:01.919  4573  4776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:01.919  4573  4776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:01.919  4573  4646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-04 14:15:01.919  4573  4646 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-04 14:15:01.919  4573  4573 D PanService: Received stop request...Stopping profile...
11-04 14:15:01.920  3068  3068 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 14:15:01.920  3068  3068 D PanProfile: Bluetooth service disconnected
11-04 14:15:01.921  4573  4573 D BluetoothMapService: Received stop request...Stopping profile...
11-04 14:15:01.921  4573  4573 D BluetoothMapService: stop()
11-04 14:15:01.922  4573  4573 D BluetoothMapAppObserver: deinitObservers()
11-04 14:15:01.923  4573  4573 D BluetoothMapAppObserver: removeReceiver()
11-04 14:15:01.924  3068  3068 D BluetoothMap: Proxy object disconnected
11-04 14:15:01.924  3068  3068 D MapProfile: Bluetooth service disconnected
11-04 14:15:01.925  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:01.925  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:01.925  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:01.925  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:01.926  4573  4646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-04 14:15:01.926  4573  4776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:01.926  4573  4776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:01.926  4573  4776 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 14:15:01.926  4573  4776 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 14:15:01.926  4573  4776 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 14:15:01.926  4573  4776 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 14:15:01.927  4573  4573 D SapService: Received stop request...Stopping profile...
11-04 14:15:01.927  4573  4573 V SapService: stop()
11-04 14:15:01.929  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:01.929  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:01.929  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:01.929  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:01.929  4573  4573 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 14:15:01.929  4573  4573 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 14:15:01.930  4573  4646 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 14:15:01.930  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:01.930  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:01.930  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:01.930  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:01.930  4573  4573 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 14:15:01.930  4573  4646 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 14:15:01.931  4573  4573 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 14:15:01.931  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:01.931  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:01.931  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:01.931  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:01.931  4573  4573 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 14:15:01.932  4573  4573 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-04 14:15:01.936  4573  4573 D BluetoothMapService: MAP Service closeService in
11-04 14:15:01.936  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:01.936  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:01.936  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:01.936  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:01.936  4573  4573 D BluetoothMapService: cleanup()
11-04 14:15:01.936  4573  4573 D BluetoothMapService: MAP Service closeService in
11-04 14:15:01.937  4573  4573 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:01.937  4573  4573 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:01.937  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:01.937  4573  4573 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:01.937  4573  4642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 14:15:01.937  4573  4642 D BluetoothAdapterProperties: Setting state to 15
11-04 14:15:01.937  4573  4642 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 14:15:01.938  4573  4642 I BluetoothAdapterState: Entering BleOnState
11-04 14:15:01.938   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:01.938  3068  3081 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:01.938   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:01.939   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 14:15:01.939  3068  3901 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 14:15:01.940  3068  3082 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 14:15:01.941  3068  3081 D BluetoothPan: onBluetoothStateChange on: false
11-04 14:15:01.942  3679  3908 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:01.943   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:01.943  3068  3901 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 14:15:01.943  3068  3082 D BluetoothMap: onBluetoothStateChange: up=false
11-04 14:15:01.944  4573  4642 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-04 14:15:01.944  4573  4642 D BluetoothAdapterProperties: Setting state to 16
11-04 14:15:01.944  4573  4642 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 14:15:01.944  4573  4642 D BluetoothAdapterProperties: onBleDisable
11-04 14:15:01.945  4573  4642 I BluetoothAdapterState: Entering PendingCommandState
11-04 14:15:01.945  4573  4643 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 14:15:01.946  4573  4646 D BluetoothAdapterProperties: Scan Mode:20
11-04 14:15:01.946  4573  4776 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 14:15:01.947  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:01.947  4573  4776 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:01.948  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:01.950  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:01.952  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:01.953  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:01.954  5686  5686 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-04 14:15:01.955  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:01.970  5686  5686 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 14:15:01.974   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b10e6c:true
,11-04 14:15:01.975  3510  3510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:15:01.987   928  3527 I ActivityManager: Start proc 5698:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-04 14:15:02.001  5686  5686 D LocalBluetoothProfileManager: Adding local MAP profile
,11-04 14:15:02.003  5686  5686 D BluetoothMap: Create BluetoothMap proxy object
,11-04 14:15:02.023  5698  5698 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-04 14:15:02.024  5686  5686 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-04 14:15:02.035  5686  5686 D DockEventReceiver: finishStartingService: stopping service
,11-04 14:15:02.041   928  3124 I ActivityManager: Killing 3790:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-04 14:15:02.154  4573  4646 I bt_hci  : shut_down
,11-04 14:15:02.158  4573  4650 D bt_hwcfg: hw_epilog_process
,11-04 14:15:02.158  4573  4650 I bt_vendor: low_power_mode_cb
,11-04 14:15:02.161  4573  4650 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-04 14:15:02.161  4573  4650 I bt_vendor: epilog_cb
11-04 14:15:02.161  4573  4650 I bt_hci  : epilog_finished_callback
,11-04 14:15:02.163  4573  4646 I bt_hci_h4: hal_close
,11-04 14:15:02.163  4573  4646 I bt_userial_vendor: device fd = 54 close
,11-04 14:15:02.196  5698  5698 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:15:02.196  5698  5698 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:15:02.196  5698  5698 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:15:02.196  5698  5698 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:15:02.196  5698  5698 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.k.d(PG:583)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.e.b(PG:170)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:02.196  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:15:02.197  5698  5698 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:15:02.197  5698  5698 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at java.io.File.exists(File.java:361)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:15:02.197  5698  5698 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:02.197  5698  5698 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:15:02.201  5686  5686 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 14:15:02.206  3510  3510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-04 14:15:02.215  5686  5686 D DockEventReceiver: finishStartingService: stopping service
11-04 14:15:02.216   928  4763 I ActivityManager: Killing 5413:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-04 14:15:02.272  4573  4643 D bt_stack_manager: event_shut_down_stack finished.
11-04 14:15:02.272  4573  4642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-04 14:15:02.274  4573  4642 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-04 14:15:02.274  4573  4573 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 14:15:02.275  4573  4573 D BtGatt.GattService: Received stop request...Stopping profile...
11-04 14:15:02.275  4573  4573 D BtGatt.GattService: stop()
11-04 14:15:02.275  4573  4573 D BtGatt.AdvertiseManager: advertise clients cleared
11-04 14:15:02.276  4573  4573 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:02.276  4573  4573 V BluetoothAdapterState: isTurningOn()=false
,11-04 14:15:02.276  4573  4573 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:02.276  4573  4573 V BluetoothAdapterState: isBleTurningOff()=true
11-04 14:15:02.277  4573  4642 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-04 14:15:02.277  4573  4642 D BluetoothAdapterProperties: Setting state to 10
11-04 14:15:02.277  4573  4642 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 14:15:02.278   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-04 14:15:02.278  4573  4642 I BluetoothAdapterState: Entering OffState
,11-04 14:15:02.284  4573  4573 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 14:15:02.284  4573  4573 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 14:15:02.284  4573  4573 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-04 14:15:02.285  4573  4643 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 14:15:02.295  4573  4643 D bt_stack_manager: event_clean_up_stack finished.
,11-04 14:15:02.296  4573  4573 I art     : System.exit called, status: 0
11-04 14:15:02.296  4573  4573 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 14:15:02.332   928  3738 I ActivityManager: Process com.android.bluetooth (pid 4573) has died
,11-04 14:15:02.367  5536  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:02.381   928   945 I ActivityManager: Start proc 5730:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 14:15:02.433  5698  5720 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-04 14:15:02.435  5730  5730 D AdapterServiceConfig: Adding HeadsetService
,11-04 14:15:02.435  5730  5730 D AdapterServiceConfig: Adding A2dpService
11-04 14:15:02.435  5730  5730 D AdapterServiceConfig: Adding HidService
,11-04 14:15:02.436  5730  5730 D AdapterServiceConfig: Adding HealthService
11-04 14:15:02.436  5730  5730 D AdapterServiceConfig: Adding PanService
11-04 14:15:02.436  5730  5730 D AdapterServiceConfig: Adding GattService
11-04 14:15:02.436  5730  5730 D AdapterServiceConfig: Adding BluetoothMapService
,11-04 14:15:02.436  5730  5730 D AdapterServiceConfig: Adding SapService
,11-04 14:15:02.443   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93fbb5d:true
,11-04 14:15:02.443   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8fe1a3:true
11-04 14:15:02.443  5730  5730 D BluetoothAdapterState: make() - Creating AdapterState
,11-04 14:15:02.445  5730  5730 I bt_bluedroid: init
,11-04 14:15:02.445  5730  5743 I BluetoothAdapterState: Entering OffState
,11-04 14:15:02.447  5730  5744 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-04 14:15:02.447  5730  5744 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 14:15:02.447  5730  5744 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 14:15:02.447  5730  5744 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 14:15:02.448  5730  5730 I bt_bluedroid: get_profile_interface socket
,11-04 14:15:02.449  5730  5730 I bt_bluedroid: get_profile_interface sdp
,11-04 14:15:02.449  5730  5747 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 14:15:02.451  5730  5747 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 14:15:02.452  5730  5741 I bt_bluedroid: config_hci_snoop_log
11-04 14:15:02.452   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 14:15:02.456  5730  5743 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 14:15:02.456  5730  5743 D BluetoothAdapterProperties: Setting state to 14
11-04 14:15:02.456  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-04 14:15:02.457  5730  5743 D BluetoothBondStateMachine: make
,11-04 14:15:02.458  5730  5748 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 14:15:02.460  5730  5743 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:15:02.460  5730  5730 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 14:15:02.462  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
,11-04 14:15:02.462  5730  5730 D BtGatt.DebugUtils: handleDebugAction() action=null
11-04 14:15:02.462  5730  5730 D BtGatt.GattService: Received start request. Starting profile...
11-04 14:15:02.463  5730  5730 D BtGatt.GattService: start()
11-04 14:15:02.463  5730  5730 I bt_bluedroid: get_profile_interface gatt
,11-04 14:15:02.463  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:02.463  5730  5730 D BtGatt.AdvertiseManager: advertise manager created
,11-04 14:15:02.466  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:15:02.466  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:02.466  5730  5730 V BluetoothAdapterState: isBleTurningOn()=true
11-04 14:15:02.466  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:15:02.466  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-04 14:15:02.467  5730  5743 I bt_bluedroid: bt_bluedroid
11-04 14:15:02.467  5730  5744 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-04 14:15:02.468  5730  5744 I bt_hci  : start_up
,11-04 14:15:02.472  5730  5744 I bt_vendor: alloc value 0xf3bc8871
,11-04 14:15:02.472  5730  5744 I bt_vendor: init
11-04 14:15:02.472  5730  5744 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 14:15:02.472  5730  5744 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 14:15:02.581  5730  5744 D bt_hci  : start_up starting async portion
,11-04 14:15:02.581  5730  5752 I bt_hci  : event_finish_startup
11-04 14:15:02.581  5730  5752 I bt_hci_h4: hal_open
11-04 14:15:02.581  5730  5752 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-04 14:15:02.583  5730  5752 I bt_userial_vendor: device fd = 54 open
,11-04 14:15:02.579  5753  5753 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 14:15:02.596  5730  5752 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 14:15:02.598  5730  5752 D bt_hwcfg: Chipset BCM4358A3
,11-04 14:15:02.598  5730  5752 D bt_hwcfg: Target name = [BCM4358A3]
11-04 14:15:02.599  5730  5752 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 14:15:02.876  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-04 14:15:02.986  5730  5752 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 14:15:02.987  5730  5752 D bt_hwcfg: Settlement delay -- 100 ms
,11-04 14:15:02.987  5730  5752 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 14:15:03.111  5730  5752 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 14:15:03.112  5730  5752 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-04 14:15:03.113  5730  5752 I bt_hwcfg: vendor lib fwcfg completed
,11-04 14:15:03.113  5730  5752 I bt_vendor: firmware callback
11-04 14:15:03.114  5730  5752 I bt_hci  : firmware_config_callback
,11-04 14:15:03.122  5730  5755 I bt_btu  : btu_task pending for preload complete event
,11-04 14:15:03.122  5730  5755 I bt_btu_task: Bluetooth chip preload is complete
,11-04 14:15:03.122  5730  5755 I bt_btu  : btu_task received preload complete event
,11-04 14:15:03.129  5730  5755 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 14:15:03.129  5730  5755 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 14:15:03.129  5730  5755 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 14:15:03.129  5730  5755 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-04 14:15:03.129  5730  5755 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 14:15:03.129  5730  5755 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 14:15:03.129  5730  5755 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 14:15:03.129  5730  5755 I         : BTE_InitTraceLevels -- TRC_BTM
,11-04 14:15:03.130  5730  5755 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 14:15:03.130  5730  5755 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 14:15:03.130  5730  5755 I         : BTE_InitTraceLevels -- TRC_SDP
11-04 14:15:03.130  5730  5755 I         : BTE_InitTraceLevels -- TRC_GATT
,11-04 14:15:03.130  5730  5755 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 14:15:03.130  5730  5755 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 14:15:03.130  5730  5755 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 14:15:03.210  5730  5755 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b46549
,11-04 14:15:03.210  5730  5755 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b46549 
,11-04 14:15:03.228  5730  5747 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 14:15:03.230  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 14:15:03.230  5730  5747 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 14:15:03.236  5730  5747 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 14:15:03.239  5730  5747 D BluetoothAdapterProperties: Scan Mode:20
,11-04 14:15:03.240  5730  5747 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 14:15:03.240  5730  5747 D bt_hci  : do_postload posting postload work item
11-04 14:15:03.240  5730  5752 I bt_hci  : event_postload
11-04 14:15:03.240  5730  5752 I bt_vendor: sco_config_cb
11-04 14:15:03.242  5730  5752 I bt_hci  : sco_config_callback postload finished.
,11-04 14:15:03.243  5730  5747 D bt_bte_conf: Device ID record 1 : primary
11-04 14:15:03.243  5730  5747 D bt_bte_conf:   vendorId            = 000f
11-04 14:15:03.244  5730  5747 D bt_bte_conf:   vendorIdSource      = 0001
11-04 14:15:03.244  5730  5747 D bt_bte_conf:   product             = 1200
11-04 14:15:03.244  5730  5747 D bt_bte_conf:   version             = 1436
11-04 14:15:03.244  5730  5747 D bt_bte_conf:   clientExecutableURL = 
,11-04 14:15:03.244  5730  5747 D bt_bte_conf:   serviceDescription  = 
11-04 14:15:03.244  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.244  5730  5747 D bt_bte_conf:   documentationURL    = 
11-04 14:15:03.244  5730  5747 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-04 14:15:03.245  5730  5744 D bt_stack_manager: event_start_up_stack finished
11-04 14:15:03.245  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 14:15:03.246  5730  5743 D BluetoothAdapterProperties: Setting state to 15
,11-04 14:15:03.246  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 14:15:03.247  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.248  5730  5743 I BluetoothAdapterState: Entering BleOnState
11-04 14:15:03.249  5730  5752 I bt_vendor: low_power_mode_cb
11-04 14:15:03.250  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.252  5730  5743 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-04 14:15:03.252  5730  5743 D BluetoothAdapterProperties: Setting state to 11
11-04 14:15:03.252  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-04 14:15:03.259  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
,11-04 14:15:03.262  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.263  5730  5730 D HeadsetService: Received start request. Starting profile...
11-04 14:15:03.264  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.266  5730  5730 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 14:15:03.266  5730  5730 D HeadsetStateMachine: make
,11-04 14:15:03.270  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:03.274  5730  5743 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:15:03.275  5730  5730 D HeadsetStateMachine: max_hf_connections = 1
,11-04 14:15:03.275  5730  5730 I bt_bluedroid: get_profile_interface handsfree
,11-04 14:15:03.275  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 14:15:03.275  5730  5747 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-04 14:15:03.279  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
,11-04 14:15:03.279  5730  5730 D A2dpService: Received start request. Starting profile...
11-04 14:15:03.280  5730  5730 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 14:15:03.280  5730  5730 I bt_bluedroid: get_profile_interface avrcp
,11-04 14:15:03.286  5730  5730 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-04 14:15:03.286  5730  5730 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-04 14:15:03.287  5730  5730 D A2dpStateMachine: make
11-04 14:15:03.287  5730  5730 I bt_bluedroid: get_profile_interface a2dp
,11-04 14:15:03.289  5730  5763 D A2dpStateMachine: Enter Disconnected: -2
,11-04 14:15:03.290  5730  5730 I BluetoothHidServiceJni: classInitNative: succeeds
11-04 14:15:03.291  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-04 14:15:03.291  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:03.292  5730  5730 D HidService: Received start request. Starting profile...
11-04 14:15:03.293  5730  5730 I bt_bluedroid: get_profile_interface hidhost
11-04 14:15:03.293  5730  5730 D HidService: setHidService(): set to: null
11-04 14:15:03.293  5730  5747 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b2756d
11-04 14:15:03.293  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 14:15:03.293  5730  5730 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 14:15:03.294  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:03.295  5730  5730 D HealthService: Received start request. Starting profile...
11-04 14:15:03.295  5686  5686 D BluetoothInputDevice: Proxy object connected
,11-04 14:15:03.296  5730  5730 I bt_bluedroid: get_profile_interface health
,11-04 14:15:03.296  5686  5686 D HidProfile: Bluetooth service connected
11-04 14:15:03.297  5730  5730 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 14:15:03.297  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:03.298  5686  5686 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 14:15:03.299  5730  5730 D PanService: Received start request. Starting profile...
,11-04 14:15:03.299  5730  5730 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 14:15:03.299  5730  5730 I bt_bluedroid: get_profile_interface pan
11-04 14:15:03.299  5686  5686 D PanProfile: Bluetooth service connected
11-04 14:15:03.301  5730  5747 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-04 14:15:03.303  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:03.304  3510  3510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:15:03.306  5686  5686 D BluetoothMap: Proxy object connected
,11-04 14:15:03.306  5730  5730 D BluetoothMapService: Received start request. Starting profile...
11-04 14:15:03.306  5730  5730 D BluetoothMapService: start()
11-04 14:15:03.307  5686  5686 D MapProfile: Bluetooth service connected
11-04 14:15:03.307  5686  5686 D BluetoothMap: getConnectedDevices()
11-04 14:15:03.308  5686  5686 D BluetoothMap: Bluetooth is Not enabled
,11-04 14:15:03.309  5730  5730 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-04 14:15:03.310  5730  5730 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-04 14:15:03.311  5730  5730 D BluetoothMapAppObserver: createReceiver()
11-04 14:15:03.312  5730  5730 D BluetoothMapAppObserver: initObservers()
11-04 14:15:03.312  5730  5730 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 14:15:03.319  5730  5730 V SapService: SapBinder()
,11-04 14:15:03.319  5730  5730 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:03.319  5730  5730 D SapService: Received start request. Starting profile...
11-04 14:15:03.319  5730  5730 V SapService: start()
,11-04 14:15:03.321  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:15:03.321  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:03.321  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:15:03.322  5730  5761 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.322  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:03.323  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:03.323  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.323  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.323  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:03.324  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:03.324  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.324  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:15:03.325  5730  5730 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:03.325  5730  5730 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:03.325  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.325  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.326  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 14:15:03.326  5730  5743 D BluetoothAdapterProperties: ScanMode =  20
11-04 14:15:03.326  5730  5743 D BluetoothAdapterProperties: State =  11
11-04 14:15:03.326  5730  5743 D BluetoothAdapterProperties: Setting state to 12
11-04 14:15:03.326  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 14:15:03.327   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-04 14:15:03.327  5730  5743 I BluetoothAdapterState: Entering OnState
11-04 14:15:03.327  3068  3081 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:03.327   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:03.327   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 14:15:03.328  5730  5747 D BluetoothAdapterProperties: Scan Mode:21
11-04 14:15:03.328  5730  5747 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 14:15:03.329  3068  3901 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-04 14:15:03.329   928   928 D BluetoothA2dp: Proxy object connected
,11-04 14:15:03.331  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-04 14:15:03.333  5536  5536 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-04 14:15:03.333  3068  3081 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 14:15:03.333  3068  3068 D BluetoothInputDevice: Proxy object connected
11-04 14:15:03.335  3068  3068 D HidProfile: Bluetooth service connected
11-04 14:15:03.335  3068  3901 D BluetoothPan: onBluetoothStateChange on: true
11-04 14:15:03.335  5536  5536 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-04 14:15:03.336  3679  3908 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:03.337  3068  3068 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 14:15:03.337  3068  3068 D PanProfile: Bluetooth service connected
,11-04 14:15:03.338  5686  5696 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 14:15:03.338  5730  5730 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 14:15:03.339   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:03.339  5686  5697 D BluetoothPan: onBluetoothStateChange on: true
11-04 14:15:03.339  5730  5730 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 14:15:03.339  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:03.339  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:03.339  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:03.339  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:03.339  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:03.339  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:03.339  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:03.339  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:03.340  5686  5696 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 14:15:03.340  3068  3901 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-04 14:15:03.340  5730  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:15:03.341  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:03.343  5686  5697 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 14:15:03.343  3068  3068 D BluetoothA2dp: Proxy object connected
11-04 14:15:03.344  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:03.344  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:03.344  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:03.344  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:03.344  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:03.344  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:03.344  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:03.344  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:03.345  3068  3901 D BluetoothMap: onBluetoothStateChange: up=true
11-04 14:15:03.346  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:03.347  5730  5730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:15:03.348  5730  5730 D ObexServerSockets: Succeed to create listening sockets 
11-04 14:15:03.348  5730  5730 D ObexServerSockets0: startAccept()
11-04 14:15:03.348  5730  5730 D ObexServerSockets0: prepareForNewConnect()
11-04 14:15:03.348   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-04 14:15:03.348  3068  3068 D BluetoothMap: Proxy object connected
11-04 14:15:03.349  3068  3068 D MapProfile: Bluetooth service connected
11-04 14:15:03.349  3068  3068 D BluetoothMap: getConnectedDevices()
11-04 14:15:03.350  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:03.350  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:03.350  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:03.350  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:03.350  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:03.350  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:03.350  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:03.350  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:03.353  5686  5686 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-04 14:15:03.353  5730  5730 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 14:15:03.353  5730  5730 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 14:15:03.354  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:03.355  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 14:15:03.355  5730  5771 D ObexServerSockets0: Accepting socket connection...
,11-04 14:15:03.355  5730  5730 D BluetoothMapService: onReceive
11-04 14:15:03.355  5730  5730 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 14:15:03.355  5730  5730 D BluetoothMapService: STATE_ON
11-04 14:15:03.356  5730  5772 D ObexServerSockets0: Accepting socket connection...
11-04 14:15:03.357  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:03.358  5730  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:15:03.358  5686  5686 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-04 14:15:03.358  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.359  5730  5773 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 14:15:03.359  5730  5773 D BluetoothSdpJni: SDP Create record success - handle: 1
11-04 14:15:03.360  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:03.363  5686  5686 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-04 14:15:03.366  5686  5686 D BluetoothA2dp: Proxy object connected
,11-04 14:15:03.369  3510  3510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:15:03.371  5686  5686 D DockEventReceiver: finishStartingService: stopping service
,11-04 14:15:03.376  5686  5686 D BluetoothPbap: Proxy object connected
,11-04 14:15:03.377  5686  5686 D PbapServerProfile: Bluetooth service connected
11-04 14:15:03.378  5536  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.378  5536  5584 D io.jxcore.node.ConnectivityMonitor: stop
11-04 14:15:03.378  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:15:03.380  3068  3068 D BluetoothPbap: Proxy object connected
11-04 14:15:03.380  3068  3068 D PbapServerProfile: Bluetooth service connected
,11-04 14:15:03.381  5536  5584 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-04 14:15:03.382  5536  5584 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
11-04 14:15:03.384  5536  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:03.385  5730  5743 D BluetoothAdapterState: Current state: ON, message: 23
11-04 14:15:03.385  5730  5743 D BluetoothAdapterProperties: Setting state to 13
11-04 14:15:03.385  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-04 14:15:03.385  5730  5743 D BluetoothAdapterProperties: onBluetoothDisable()
11-04 14:15:03.386  5730  5743 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:15:03.388  5730  5747 D BluetoothAdapterProperties: Scan Mode:20
,11-04 14:15:03.389  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-04 14:15:03.390  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:15:03.390  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:03.390  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:03.390  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:03.390  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:03.390  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:15:03.390  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:03.390  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:03.390  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:03.391  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:15:03.391  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:03.393  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 14:15:03.393  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:03.393  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:03.393  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:03.393  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:03.393  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:15:03.393  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:03.393  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:03.393  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:03.394  5686  5686 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 14:15:03.394  5536  5536 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 14:15:03.394  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:03.396  5686  5686 D BluetoothPbap: Proxy object disconnected
11-04 14:15:03.396  5686  5686 D PbapServerProfile: Bluetooth service disconnected
11-04 14:15:03.397  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.399  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.400  3068  3068 D BluetoothPbap: Proxy object disconnected
11-04 14:15:03.400  3068  3068 D PbapServerProfile: Bluetooth service disconnected
,11-04 14:15:03.403  5686  5686 D DockEventReceiver: finishStartingService: stopping service
,11-04 14:15:03.407  5730  5730 D BluetoothMapService: onReceive
11-04 14:15:03.407  5730  5730 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-04 14:15:03.407  5730  5730 D BluetoothMapService: STATE_TURNING_OFF
11-04 14:15:03.408  5730  5730 D HeadsetService: Received stop request...Stopping profile...
,11-04 14:15:03.410  5730  5730 D A2dpService: Received stop request...Stopping profile...
11-04 14:15:03.410  5730  5763 D A2dpStateMachine: Exit Disconnected: -1
,11-04 14:15:03.411   928   928 D BluetoothA2dp: Proxy object disconnected
,11-04 14:15:03.411  3068  3068 D BluetoothA2dp: Proxy object disconnected
11-04 14:15:03.411  5686  5686 D BluetoothA2dp: Proxy object disconnected
11-04 14:15:03.412  5730  5730 D HidService: Received stop request...Stopping profile...
11-04 14:15:03.412  5730  5730 D HidService: Stopping Bluetooth HidService
,11-04 14:15:03.413  3068  3068 D BluetoothInputDevice: Proxy object disconnected
,11-04 14:15:03.413  3068  3068 D HidProfile: Bluetooth service disconnected
11-04 14:15:03.413  5686  5686 D BluetoothInputDevice: Proxy object disconnected
11-04 14:15:03.413  5686  5686 D HidProfile: Bluetooth service disconnected
,11-04 14:15:03.415  5730  5730 D HealthService: Received stop request...Stopping profile...
,11-04 14:15:03.416  3510  3510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:15:03.417  5730  5730 D PanService: Received stop request...Stopping profile...
11-04 14:15:03.418  5686  5686 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 14:15:03.418  3068  3068 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-04 14:15:03.418  3068  3068 D PanProfile: Bluetooth service disconnected
11-04 14:15:03.418  5686  5686 D PanProfile: Bluetooth service disconnected
,11-04 14:15:03.420  5730  5730 D BluetoothMapService: Received stop request...Stopping profile...
,11-04 14:15:03.420  5730  5730 D BluetoothMapService: stop()
11-04 14:15:03.420  5730  5730 D BluetoothMapAppObserver: deinitObservers()
11-04 14:15:03.420  5730  5730 D BluetoothMapAppObserver: removeReceiver()
,11-04 14:15:03.421  3068  3068 D BluetoothMap: Proxy object disconnected
11-04 14:15:03.421  3068  3068 D MapProfile: Bluetooth service disconnected
,11-04 14:15:03.422  5730  5730 D SapService: Received stop request...Stopping profile...
,11-04 14:15:03.422  5730  5730 V SapService: stop()
11-04 14:15:03.423  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:03.423  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:03.423  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.423  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.424  5730  5730 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-04 14:15:03.425  5730  5730 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-04 14:15:03.425  5730  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:03.425  5730  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-04 14:15:03.425  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:03.425  5730  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:03.425  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:03.425  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.425  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.425  5686  5686 D BluetoothMap: Proxy object disconnected
11-04 14:15:03.425  5686  5686 D MapProfile: Bluetooth service disconnected
11-04 14:15:03.426  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:03.426  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:03.426  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.426  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.426  5730  5730 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-04 14:15:03.426  5730  5730 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-04 14:15:03.427  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 14:15:03.427  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 14:15:03.427  5730  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:03.427  5730  5747 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-04 14:15:03.427  5730  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:03.427  5730  5747 E bt_btif : L2CAP - PSM: 0x0019 not found for deregist
11-04 14:15:03.427  5730  5755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 14:15:03.427  5730  5755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-04 14:15:03.427  5730  5755 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-04 14:15:03.427  5730  5755 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-04 14:15:03.428  5730  5730 V BluetoothAdapterState: isTurningOff()=true
,11-04 14:15:03.428  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:03.428  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.428  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.428  5730  5730 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-04 14:15:03.428  5730  5747 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-04 14:15:03.429  5730  5730 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-04 14:15:03.429  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:03.429  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:03.429  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.429  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:15:03.429  5730  5730 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-04 14:15:03.429  5730  5730 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-04 14:15:03.432  5730  5730 D BluetoothMapService: MAP Service closeService in
,11-04 14:15:03.432  5730  5730 D BluetoothMapMasInstance0: MAP Service shutdown
11-04 14:15:03.432  5730  5730 D ObexServerSockets0: shutdown(block = true)
11-04 14:15:03.432  5730  5771 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-04 14:15:03.433  5730  5730 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 14:15:03.433  5730  5730 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-04 14:15:03.433  5730  5772 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-04 14:15:03.433  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:03.433  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:03.433  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 14:15:03.433  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.433  5730  5757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-04 14:15:03.433  5730  5730 D BluetoothMapService: cleanup()
11-04 14:15:03.433  5730  5730 D BluetoothMapService: MAP Service closeService in
11-04 14:15:03.434  5730  5730 V BluetoothAdapterState: isTurningOff()=true
11-04 14:15:03.434  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:03.434  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.434  5730  5730 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:03.434  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-04 14:15:03.434  5730  5743 D BluetoothAdapterProperties: Setting state to 15
11-04 14:15:03.434  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-04 14:15:03.435  5730  5743 I BluetoothAdapterState: Entering BleOnState
11-04 14:15:03.435   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:03.435  3068  3081 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:03.435   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:03.435   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 14:15:03.435  5686  5697 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:03.436  3068  3901 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 14:15:03.436  3068  3082 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 14:15:03.437  3068  3081 D BluetoothPan: onBluetoothStateChange on: false
,11-04 14:15:03.437  3679  3697 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:03.437  5686  5696 D BluetoothMap: onBluetoothStateChange: up=false
11-04 14:15:03.438   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-04 14:15:03.438  5686  5697 D BluetoothPan: onBluetoothStateChange on: false
11-04 14:15:03.439  5686  5696 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-04 14:15:03.439  3068  3901 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 14:15:03.439  5686  5697 D BluetoothA2dp: onBluetoothStateChange: up=false
11-04 14:15:03.440  5686  5696 D BluetoothPbap: onBluetoothStateChange: up=false
11-04 14:15:03.441  3068  3082 D BluetoothMap: onBluetoothStateChange: up=false
11-04 14:15:03.441  5730  5743 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-04 14:15:03.441  5730  5743 D BluetoothAdapterProperties: Setting state to 16
11-04 14:15:03.441  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-04 14:15:03.442  5730  5743 D BluetoothAdapterProperties: onBleDisable
11-04 14:15:03.442  5730  5743 I BluetoothAdapterState: Entering PendingCommandState
11-04 14:15:03.443  5730  5744 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-04 14:15:03.444  5730  5747 D BluetoothAdapterProperties: Scan Mode:20
,11-04 14:15:03.444  5686  5686 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 14:15:03.444  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:03.445  5730  5755 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-04 14:15:03.445  5730  5755 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-04 14:15:03.446  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.446  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.448  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:03.449  3510  3510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:15:03.453  5686  5686 D DockEventReceiver: finishStartingService: stopping service
,11-04 14:15:03.646  5730  5747 I bt_hci  : shut_down
,11-04 14:15:03.646  5730  5752 D bt_hwcfg: hw_epilog_process
11-04 14:15:03.647  5730  5752 I bt_vendor: low_power_mode_cb
,11-04 14:15:03.651  5730  5752 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-04 14:15:03.651  5730  5752 I bt_vendor: epilog_cb
11-04 14:15:03.651  5730  5752 I bt_hci  : epilog_finished_callback
11-04 14:15:03.652  5730  5747 I bt_hci_h4: hal_close
,11-04 14:15:03.654  5730  5747 I bt_userial_vendor: device fd = 54 close
,11-04 14:15:03.776  5730  5744 D bt_stack_manager: event_shut_down_stack finished.
,11-04 14:15:03.777  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-04 14:15:03.781  5730  5743 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-04 14:15:03.781  5730  5730 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 14:15:03.782  5730  5730 D BtGatt.GattService: Received stop request...Stopping profile...
,11-04 14:15:03.782  5730  5730 D BtGatt.GattService: stop()
11-04 14:15:03.782  5730  5730 D BtGatt.AdvertiseManager: advertise clients cleared
11-04 14:15:03.786  5730  5730 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:15:03.787  5730  5730 V BluetoothAdapterState: isTurningOn()=false
11-04 14:15:03.787  5730  5730 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:03.787  5730  5730 V BluetoothAdapterState: isBleTurningOff()=true
11-04 14:15:03.788  5730  5743 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-04 14:15:03.788  5730  5743 D BluetoothAdapterProperties: Setting state to 10
11-04 14:15:03.788  5730  5743 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-04 14:15:03.789  5730  5743 I BluetoothAdapterState: Entering OffState
,11-04 14:15:03.791   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-04 14:15:03.803  5730  5730 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-04 14:15:03.804  5730  5730 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-04 14:15:03.806  5730  5730 I BluetoothServiceJni: cleanupNative: return from cleanup
11-04 14:15:03.807  5730  5744 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-04 14:15:03.814  5730  5730 I art     : System.exit called, status: 0
11-04 14:15:03.815  5730  5730 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-04 14:15:03.846   928  3085 I ActivityManager: Process com.android.bluetooth (pid 5730) has died
,11-04 14:15:03.889  5536  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-04 14:15:03.890  5536  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:03.890  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:03.890  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:03.890  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:03.890  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-04 14:15:03.890  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:03.890  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:03.890  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:03.890  5536  5599 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-04 14:15:03.890  5536  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:03.893  5536  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:03.920   928   945 I ActivityManager: Start proc 5785:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-04 14:15:03.987  5785  5785 D AdapterServiceConfig: Adding HeadsetService
,11-04 14:15:03.987  5785  5785 D AdapterServiceConfig: Adding A2dpService
,11-04 14:15:03.987  5785  5785 D AdapterServiceConfig: Adding HidService
11-04 14:15:03.988  5785  5785 D AdapterServiceConfig: Adding HealthService
11-04 14:15:03.988  5785  5785 D AdapterServiceConfig: Adding PanService
11-04 14:15:03.988  5785  5785 D AdapterServiceConfig: Adding GattService
11-04 14:15:03.988  5785  5785 D AdapterServiceConfig: Adding BluetoothMapService
11-04 14:15:03.988  5785  5785 D AdapterServiceConfig: Adding SapService
,11-04 14:15:04.000   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8e0a1db:true
,11-04 14:15:04.001  5785  5785 D BluetoothAdapterState: make() - Creating AdapterState
11-04 14:15:04.004  5785  5785 I bt_bluedroid: init
11-04 14:15:04.004  5785  5797 I BluetoothAdapterState: Entering OffState
11-04 14:15:04.006  5785  5798 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-04 14:15:04.006  5785  5798 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-04 14:15:04.006  5785  5798 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-04 14:15:04.006  5785  5798 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-04 14:15:04.006  5785  5785 I bt_bluedroid: get_profile_interface socket
,11-04 14:15:04.008  5785  5801 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-04 14:15:04.008  5785  5785 I bt_bluedroid: get_profile_interface sdp
11-04 14:15:04.009  5785  5801 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 14:15:04.013  5785  5796 I bt_bluedroid: config_hci_snoop_log
,11-04 14:15:04.014   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-04 14:15:04.017  5785  5797 D BluetoothAdapterState: Current state: OFF, message: 0
,11-04 14:15:04.017  5785  5797 D BluetoothAdapterProperties: Setting state to 14
11-04 14:15:04.017  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-04 14:15:04.019  5785  5797 D BluetoothBondStateMachine: make
,11-04 14:15:04.020  5785  5802 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-04 14:15:04.022  5785  5797 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:15:04.024  5785  5785 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-04 14:15:04.025  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:04.026  5785  5785 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-04 14:15:04.027  5785  5785 D BtGatt.GattService: Received start request. Starting profile...
11-04 14:15:04.027  5785  5785 D BtGatt.GattService: start()
11-04 14:15:04.027  5785  5785 I bt_bluedroid: get_profile_interface gatt
,11-04 14:15:04.028  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:04.028  5785  5785 D BtGatt.AdvertiseManager: advertise manager created
,11-04 14:15:04.032  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:04.032  5785  5785 V BluetoothAdapterState: isTurningOn()=false
,11-04 14:15:04.032  5785  5785 V BluetoothAdapterState: isBleTurningOn()=true
11-04 14:15:04.032  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:04.033  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-04 14:15:04.034  5785  5797 I bt_bluedroid: bt_bluedroid
11-04 14:15:04.034  5785  5798 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-04 14:15:04.035  5785  5798 I bt_hci  : start_up
,11-04 14:15:04.039  5785  5798 I bt_vendor: alloc value 0xf3bc8871
,11-04 14:15:04.040  5785  5798 I bt_vendor: init
11-04 14:15:04.040  5785  5798 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-04 14:15:04.040  5785  5798 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-04 14:15:04.151  5785  5798 D bt_hci  : start_up starting async portion
,11-04 14:15:04.151  5785  5805 I bt_hci  : event_finish_startup
,11-04 14:15:04.151  5785  5805 I bt_hci_h4: hal_open
,11-04 14:15:04.151  5785  5805 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-04 14:15:04.149  5806  5806 W irq/448-msm_hs_: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-04 14:15:04.155  5785  5805 I bt_userial_vendor: device fd = 54 open
,11-04 14:15:04.170  5785  5805 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 14:15:04.173  5785  5805 D bt_hwcfg: Chipset BCM4358A3
,11-04 14:15:04.173  5785  5805 D bt_hwcfg: Target name = [BCM4358A3]
11-04 14:15:04.174  5785  5805 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-04 14:15:04.401  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-04 14:15:04.559  5785  5805 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-04 14:15:04.559  5785  5805 D bt_hwcfg: Settlement delay -- 100 ms
11-04 14:15:04.560  5785  5805 I bt_hwcfg: Setting fw settlement delay to 100 
,11-04 14:15:04.682  5785  5805 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-04 14:15:04.682  5785  5805 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-04 14:15:04.683  5785  5805 I bt_hwcfg: vendor lib fwcfg completed
11-04 14:15:04.683  5785  5805 I bt_vendor: firmware callback
11-04 14:15:04.683  5785  5805 I bt_hci  : firmware_config_callback
,11-04 14:15:04.688  5785  5808 I bt_btu  : btu_task pending for preload complete event
,11-04 14:15:04.688  5785  5808 I bt_btu_task: Bluetooth chip preload is complete
11-04 14:15:04.688  5785  5808 I bt_btu  : btu_task received preload complete event
,11-04 14:15:04.693  5785  5808 I         : BTE_InitTraceLevels -- TRC_HCI
,11-04 14:15:04.693  5785  5808 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-04 14:15:04.693  5785  5808 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-04 14:15:04.693  5785  5808 I         : BTE_InitTraceLevels -- TRC_AVDT
11-04 14:15:04.693  5785  5808 I         : BTE_InitTraceLevels -- TRC_AVRC
11-04 14:15:04.693  5785  5808 I         : BTE_InitTraceLevels -- TRC_A2D
11-04 14:15:04.693  5785  5808 I         : BTE_InitTraceLevels -- TRC_BNEP
11-04 14:15:04.693  5785  5808 I         : BTE_InitTraceLevels -- TRC_BTM
11-04 14:15:04.693  5785  5808 I         : BTE_InitTraceLevels -- TRC_GAP
11-04 14:15:04.694  5785  5808 I         : BTE_InitTraceLevels -- TRC_PAN
11-04 14:15:04.694  5785  5808 I         : BTE_InitTraceLevels -- TRC_SDP
,11-04 14:15:04.694  5785  5808 I         : BTE_InitTraceLevels -- TRC_GATT
11-04 14:15:04.694  5785  5808 I         : BTE_InitTraceLevels -- TRC_SMP
11-04 14:15:04.694  5785  5808 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-04 14:15:04.694  5785  5808 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-04 14:15:04.775  5785  5808 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b46549
11-04 14:15:04.776  5785  5808 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b46549 
,11-04 14:15:04.788  5785  5801 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-04 14:15:04.789  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-04 14:15:04.790  5785  5801 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-04 14:15:04.791  5785  5801 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-04 14:15:04.794  5785  5801 D BluetoothAdapterProperties: Scan Mode:20
,11-04 14:15:04.795  5785  5801 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 14:15:04.795  5785  5801 D bt_hci  : do_postload posting postload work item
11-04 14:15:04.795  5785  5805 I bt_hci  : event_postload
11-04 14:15:04.795  5785  5805 I bt_vendor: sco_config_cb
11-04 14:15:04.795  5785  5805 I bt_hci  : sco_config_callback postload finished.
11-04 14:15:04.798  5785  5801 D bt_bte_conf: Device ID record 1 : primary
,11-04 14:15:04.798  5785  5801 D bt_bte_conf:   vendorId            = 000f
11-04 14:15:04.799  5785  5801 D bt_bte_conf:   vendorIdSource      = 0001
11-04 14:15:04.799  5785  5801 D bt_bte_conf:   product             = 1200
11-04 14:15:04.799  5785  5801 D bt_bte_conf:   version             = 1436
,11-04 14:15:04.799  5785  5801 D bt_bte_conf:   clientExecutableURL = 
,11-04 14:15:04.799  5785  5801 D bt_bte_conf:   serviceDescription  = 
11-04 14:15:04.799  5785  5801 D bt_bte_conf:   documentationURL    = 
11-04 14:15:04.799  5785  5801 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-04 14:15:04.799  5785  5798 D bt_stack_manager: event_start_up_stack finished
11-04 14:15:04.800  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:04.800  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-04 14:15:04.800  5785  5797 D BluetoothAdapterProperties: Setting state to 15
11-04 14:15:04.800  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-04 14:15:04.802  5785  5797 I BluetoothAdapterState: Entering BleOnState
11-04 14:15:04.802  5785  5805 I bt_vendor: low_power_mode_cb
11-04 14:15:04.803  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:04.804  5785  5797 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-04 14:15:04.804  5785  5797 D BluetoothAdapterProperties: Setting state to 11
11-04 14:15:04.804  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-04 14:15:04.810  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:04.811  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:04.815   928   928 D BluetoothHeadset: Proxy object connected
,11-04 14:15:04.815  5785  5785 D HeadsetService: Received start request. Starting profile...
11-04 14:15:04.815  3068  3081 D BluetoothHeadset: Proxy object connected
,11-04 14:15:04.815   928   928 D BluetoothHeadset: Proxy object connected
11-04 14:15:04.816  5686  5696 D BluetoothHeadset: Proxy object connected
11-04 14:15:04.816  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:04.816  3068  3068 D HeadsetProfile: Bluetooth service connected
11-04 14:15:04.817  3679  3908 D BluetoothHeadset: Proxy object connected
11-04 14:15:04.817  5785  5785 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-04 14:15:04.818   928   928 D BluetoothHeadset: Proxy object connected
11-04 14:15:04.818  5785  5785 D HeadsetStateMachine: make
11-04 14:15:04.819  5686  5686 D HeadsetProfile: Bluetooth service connected
11-04 14:15:04.822  5785  5797 I BluetoothAdapterState: Entering PendingCommandState
,11-04 14:15:04.826  5785  5785 D HeadsetStateMachine: max_hf_connections = 1
,11-04 14:15:04.826  5785  5785 I bt_bluedroid: get_profile_interface handsfree
11-04 14:15:04.826  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-04 14:15:04.827  5785  5801 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-04 14:15:04.829  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
,11-04 14:15:04.830  5785  5785 D A2dpService: Received start request. Starting profile...
11-04 14:15:04.830  5785  5785 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-04 14:15:04.830  5785  5785 I bt_bluedroid: get_profile_interface avrcp
,11-04 14:15:04.835  5785  5785 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-04 14:15:04.835  5785  5785 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-04 14:15:04.835  5785  5785 D A2dpStateMachine: make
11-04 14:15:04.836  5682  5682 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-04 14:15:04.836  5785  5785 I bt_bluedroid: get_profile_interface a2dp
,11-04 14:15:04.837  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-04 14:15:04.837  5682  5682 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-04 14:15:04.838  5785  5817 D A2dpStateMachine: Enter Disconnected: -2
11-04 14:15:04.838  5785  5785 I BluetoothHidServiceJni: classInitNative: succeeds
11-04 14:15:04.838  5682  5682 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-04 14:15:04.839  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
,11-04 14:15:04.840  5785  5785 D HidService: Received start request. Starting profile...
11-04 14:15:04.840  5785  5785 I bt_bluedroid: get_profile_interface hidhost
11-04 14:15:04.840  5785  5785 D HidService: setHidService(): set to: null
,11-04 14:15:04.840  5785  5801 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b2756d
11-04 14:15:04.840  5785  5801 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-04 14:15:04.842  5785  5785 I BluetoothHealthServiceJni: classInitNative: succeeds
11-04 14:15:04.842  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
,11-04 14:15:04.843  5785  5785 D HealthService: Received start request. Starting profile...
11-04 14:15:04.843  3510  3510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:15:04.845  5785  5785 I bt_bluedroid: get_profile_interface health
11-04 14:15:04.845  5785  5785 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-04 14:15:04.846  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:04.847  5785  5785 D PanService: Received start request. Starting profile...
11-04 14:15:04.847  5785  5785 D BluetoothPanServiceJni: initializeNative(L110): pan
11-04 14:15:04.847  5785  5785 I bt_bluedroid: get_profile_interface pan
11-04 14:15:04.847  5785  5801 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-04 14:15:04.849  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
,11-04 14:15:04.849  5785  5785 D BluetoothMapService: Received start request. Starting profile...
,11-04 14:15:04.849  5785  5785 D BluetoothMapService: start()
11-04 14:15:04.852  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-04 14:15:04.853  5785  5785 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-04 14:15:04.853  5785  5785 D BluetoothMapAppObserver: createReceiver()
11-04 14:15:04.854  5785  5785 D BluetoothMapAppObserver: initObservers()
11-04 14:15:04.854  5785  5785 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-04 14:15:04.859  5785  5785 V SapService: SapBinder()
,11-04 14:15:04.859  5785  5785 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
11-04 14:15:04.860  5785  5785 D SapService: Received start request. Starting profile...
11-04 14:15:04.860  5785  5785 V SapService: start()
11-04 14:15:04.862  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:04.862  5785  5785 V BluetoothAdapterState: isTurningOn()=true
,11-04 14:15:04.862  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:04.862  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:04.863  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:04.863  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:04.863  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:04.863  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:04.863  5785  5815 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-04 14:15:04.863  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:04.863  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:04.863  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 14:15:04.863  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:04.864  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:04.864  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:04.864  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:04.864  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:15:04.864  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:04.865  5785  5785 V BluetoothAdapterState: isTurningOn()=true
,11-04 14:15:04.865  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
,11-04 14:15:04.865  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:15:04.865  5785  5785 V BluetoothAdapterState: isTurningOff()=false
,11-04 14:15:04.865   928  2897 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-04 14:15:04.865  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:04.865  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:04.865  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
11-04 14:15:04.866   928  2897 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-04 14:15:04.866   928  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:15:04.866  5785  5785 V BluetoothAdapterState: isTurningOff()=false
11-04 14:15:04.866  5785  5785 V BluetoothAdapterState: isTurningOn()=true
11-04 14:15:04.866  5785  5785 V BluetoothAdapterState: isBleTurningOn()=false
11-04 14:15:04.866  5785  5785 V BluetoothAdapterState: isBleTurningOff()=false
,11-04 14:15:04.866  5785  5797 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-04 14:15:04.866  5785  5797 D BluetoothAdapterProperties: ScanMode =  20
11-04 14:15:04.867  5785  5797 D BluetoothAdapterProperties: State =  11
11-04 14:15:04.867  5785  5797 D BluetoothAdapterProperties: Setting state to 12
11-04 14:15:04.867  5785  5797 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-04 14:15:04.867   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:04.868  3068  3082 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:04.868  5785  5801 D BluetoothAdapterProperties: Scan Mode:21
11-04 14:15:04.868  5785  5801 D BluetoothAdapterProperties: Discoverable Timeout:120
11-04 14:15:04.868  5785  5797 I BluetoothAdapterState: Entering OnState
,11-04 14:15:04.868   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:04.868   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 14:15:04.868  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 14:15:04.869  5686  5697 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:04.870  3068  3081 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 14:15:04.870   928   928 D BluetoothA2dp: Proxy object connected
11-04 14:15:04.872  3068  3901 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 14:15:04.872  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:04.872  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:04.872  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:04.872  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:04.872  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:04.872  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:04.872  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:04.872  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:04.872  3068  3068 D BluetoothInputDevice: Proxy object connected
11-04 14:15:04.872  3068  3068 D HidProfile: Bluetooth service connected
11-04 14:15:04.873  3068  3082 D BluetoothPan: onBluetoothStateChange on: true
11-04 14:15:04.874  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:04.875  3679  3900 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:04.875  5686  5696 D BluetoothMap: onBluetoothStateChange: up=true
11-04 14:15:04.875  3068  3068 D BluetoothPan: BluetoothPAN Proxy object connected
,11-04 14:15:04.876  3068  3068 D PanProfile: Bluetooth service connected
11-04 14:15:04.877   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-04 14:15:04.877  5686  5697 D BluetoothPan: onBluetoothStateChange on: true
11-04 14:15:04.877  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:04.877  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:04.877  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:04.877  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:04.877  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:04.877  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:04.877  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:04.877  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:04.879  5785  5785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-04 14:15:04.879  5686  5696 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-04 14:15:04.879  5785  5785 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-04 14:15:04.879  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:04.880  3068  3901 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 14:15:04.880  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:15:04.882  3068  3068 D BluetoothA2dp: Proxy object connected
11-04 14:15:04.882  5686  5697 D BluetoothA2dp: onBluetoothStateChange: up=true
11-04 14:15:04.882  5785  5785 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:15:04.883  5785  5785 D ObexServerSockets: Succeed to create listening sockets 
11-04 14:15:04.883  5785  5785 D ObexServerSockets0: startAccept()
11-04 14:15:04.883  5785  5785 D ObexServerSockets0: prepareForNewConnect()
11-04 14:15:04.885  5785  5785 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-04 14:15:04.885  5785  5785 D BluetoothSdpJni: SDP Create record success - handle: 0
11-04 14:15:04.885  5686  5696 D BluetoothPbap: onBluetoothStateChange: up=true
11-04 14:15:04.886  5785  5824 D ObexServerSockets0: Accepting socket connection...
11-04 14:15:04.886  5785  5825 D ObexServerSockets0: Accepting socket connection...
11-04 14:15:04.889  3068  3081 D BluetoothMap: onBluetoothStateChange: up=true
,11-04 14:15:04.890  3068  3068 D BluetoothMap: Proxy object connected
11-04 14:15:04.890  3068  3068 D MapProfile: Bluetooth service connected
11-04 14:15:04.890  3068  3068 D BluetoothMap: getConnectedDevices()
11-04 14:15:04.890   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-04 14:15:04.891   928   928 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
11-04 14:15:04.891  5686  5686 D BluetoothMap: Proxy object connected
11-04 14:15:04.891  5686  5686 D MapProfile: Bluetooth service connected
11-04 14:15:04.891  5686  5686 D BluetoothMap: getConnectedDevices()
11-04 14:15:04.891  5785  5785 D BluetoothMapService: onReceive
11-04 14:15:04.891  5785  5785 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-04 14:15:04.892  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-04 14:15:04.892  5785  5785 D BluetoothMapService: STATE_ON
11-04 14:15:04.894  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:04.894   928  2897 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
11-04 14:15:04.895  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:04.896  5785  5828 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:15:04.897  5785  5828 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-04 14:15:04.897  5785  5828 D BluetoothSdpJni: SDP Create record success - handle: 1
11-04 14:15:04.898  5686  5686 D BluetoothPan: BluetoothPAN Proxy object connected
11-04 14:15:04.898  5686  5686 D PanProfile: Bluetooth service connected
11-04 14:15:04.898  5686  5686 D BluetoothInputDevice: Proxy object connected
11-04 14:15:04.898  5686  5686 D HidProfile: Bluetooth service connected
,11-04 14:15:04.900  5686  5686 D BluetoothA2dp: Proxy object connected
11-04 14:15:04.903  5536  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:04.903  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:04.903  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:04.903  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:04.903  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:04.903  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:04.903  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:04.903  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:04.904  5536  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:04.905  5686  5686 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-04 14:15:04.905  5536  5584 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
11-04 14:15:04.906   928  4762 D WifiService: setWifiEnabled: false pid=5536, uid=10077
11-04 14:15:04.906   928  4762 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-04 14:15:04.909  5536  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:04.909  5686  5686 D DockEventReceiver: finishStartingService: stopping service
,11-04 14:15:04.912  3510  3510 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-04 14:15:04.919  5686  5686 D BluetoothPbap: Proxy object connected
,11-04 14:15:04.919  5686  5686 D PbapServerProfile: Bluetooth service connected
,11-04 14:15:04.919  5785  5785 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-04 14:15:04.919  5785  5785 D ObexServerSockets0: prepareForNewConnect()
11-04 14:15:04.920  3068  3068 D BluetoothPbap: Proxy object connected
11-04 14:15:04.920  3068  3068 D PbapServerProfile: Bluetooth service connected
,11-04 14:15:04.928  5785  5833 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 14:15:04.931   928  2897 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 14:15:04.937  5682  5682 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 14:15:04.941  5785  5837 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-04 14:15:04.942  5785  5837 I BtOppRfcommListener: Accept thread started.
,11-04 14:15:04.951   928   928 D RttService: SCAN_AVAILABLE : 1
,11-04 14:15:04.951   928  2998 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 14:15:04.960   928  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-04 14:15:04.961   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-04 14:15:04.963   928  2897 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-04 14:15:04.964  5682  5682 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-04 14:15:04.969  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:04.969  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:04.969  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:04.969  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:15:04.969  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:04.969  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:04.969  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:04.969  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:04.970  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:04.973  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:04.973  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:04.973  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:04.973  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:15:04.973  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:04.973  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:04.973  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:04.973  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:04.973  5682  5682 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-04 14:15:04.975  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:04.977  5682  5682 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,11-04 14:15:04.983  5682  5682 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-04 14:15:04.988  5682  5682 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-04 14:15:05.092  4433  4433 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 14:15:05.092   928  2897 D wifi    : In wifi stop Hal
11-04 14:15:05.092   928  2897 D wifi    : halHandle = 0x7f61a66680, mVM = 0x7f7e0cd140, mCls = 0x198a
11-04 14:15:05.093   928  5681 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-04 14:15:05.093   928  5681 D WifiHAL : Got a signal to exit!!!
11-04 14:15:05.093   928  5681 I WifiHAL : Exit wifi_event_loop
11-04 14:15:05.093   928  2897 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-04 14:15:05.093   928  2897 E WifiHAL : Event processing terminated
11-04 14:15:05.093   928  2897 D wifi    : In wifi cleaned up handler
11-04 14:15:05.093   928  2897 I WifiHAL : Internal cleanup completed
11-04 14:15:05.095  3864  4123 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-04 14:15:05.099  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:05.102  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:05.124   928  5681 D wifi    : set interface wlan0 flags (DOWN)
,11-04 14:15:05.124   928  2897 D WifiNative-HAL: HAL event thread stopped successfully
,11-04 14:15:05.330   928   945 D Tethering: InitialState.processMessage what=4
,11-04 14:15:05.337   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-04 14:15:05.420  5536  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:05.420  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:05.420  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:05.420  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-04 14:15:05.420  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:05.420  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:05.420  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:05.420  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-04 14:15:05.425  5536  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:05.428   928   939 D WifiService: setWifiEnabled: true pid=5536, uid=10077
,11-04 14:15:05.429   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:15:05.432  5536  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-04 14:15:05.436   506   921 D SoftapController: Softap fwReload - Ok
,11-04 14:15:05.441   506   921 D CommandListener: Setting iface cfg
,11-04 14:15:05.441   506   921 D CommandListener: Trying to bring down wlan0
,11-04 14:15:05.443   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-04 14:15:05.448   928  2897 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-04 14:15:05.936   928  3085 D WifiService: setWifiEnabled: true pid=5536, uid=10077
,11-04 14:15:05.941   928  3085 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:15:06.051   928  2897 D wifi    : set interface wlan0 flags (UP)
11-04 14:15:06.051   928  2897 I WifiHAL : Initializing wifi
,11-04 14:15:06.051   928  2897 I WifiHAL : Creating socket
,11-04 14:15:06.058   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-04 14:15:06.061   928  2897 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-04 14:15:06.062   928  2897 D wifi    : Did set static halHandle = 0x7f61a66680
,11-04 14:15:06.062   928  2897 D wifi    : halHandle = 0x7f61a66680, mVM = 0x7f7e0cd140, mCls = 0x201376
,11-04 14:15:06.063   928  2897 D wifi    : array field set
,11-04 14:15:06.065   928  2897 I WifiNative-HAL: interface[0] = wlan0
11-04 14:15:06.066   928  5840 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547099141760
11-04 14:15:06.066   928  5840 D wifi    : waitForHalEvents called, vm = 0x7f7e0cd140, obj = 0x201376, env = 0x7f61a7c6c0
,11-04 14:15:06.128  5841  5841 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-04 14:15:06.167   928  2897 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-04 14:15:06.171  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:06.174  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:06.209  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 14:15:06.219  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-04 14:15:06.219  5841  5841 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-04 14:15:06.231   928  2897 D WifiConfigStore: Loading config and enabling all networks 
,11-04 14:15:06.240  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:06.240  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:06.240  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:06.240  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:06.240  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:06.240  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:06.240  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:06.240  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:06.243  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:06.247   928  2897 D WifiConfigStore: loaded 0 passpoint configs
,11-04 14:15:06.247   928  2897 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-04 14:15:06.248   928  2897 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-04 14:15:06.248   928  2897 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-04 14:15:06.248   928  2897 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-04 14:15:06.249   928  2897 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-04 14:15:06.249   928  2897 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-04 14:15:06.249   928  2897 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-04 14:15:06.249   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-04 14:15:06.249  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:06.249  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:06.249  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:06.249  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:06.249  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:06.249  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:06.249  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:06.249  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:06.249   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-04 14:15:06.249   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-04 14:15:06.249   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-04 14:15:06.249   928  2897 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-04 14:15:06.251   928  2897 D WifiNative-HAL: Setting external_sim to 1
11-04 14:15:06.252   928  2897 D wifi    : setting dfs flag to true, 0x7f65db59a0
11-04 14:15:06.252   928  2897 D WifiStateMachine: Setting OUI to DA-A1-19
11-04 14:15:06.252   928  2897 D wifi    : setting scan oui 0x7f65db59a0
11-04 14:15:06.252   928  2897 D WifiHAL : Sending mac address OUI
,11-04 14:15:06.252  4433  4433 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-04 14:15:06.253  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:06.255   928  2897 E native  : do suspend false
,11-04 14:15:06.261   928  2897 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-04 14:15:06.261   928   928 D RttService: SCAN_AVAILABLE : 3
11-04 14:15:06.262   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-04 14:15:06.262   928  2998 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-04 14:15:06.263   506   921 D CommandListener: Setting iface cfg
,11-04 14:15:06.267   928  2882 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
11-04 14:15:06.267   928  2882 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-04 14:15:06.271   928  2882 D WifiNative-HAL: p2pGetDeviceAddress
,11-04 14:15:06.276   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=111405 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=9 mControllerEnergyUsed=34 }
11-04 14:15:06.277   928  2882 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-04 14:15:06.455  5536  5599 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:06.455  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:06.455  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:06.455  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:06.455  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:06.455  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:06.455  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:06.455  5536  5599 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:06.461  5536  5599 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,11-04 14:15:06.466  5536  5584 D BluetoothAdapter: enable(): BT is already enabled..!
,11-04 14:15:06.466   928  4762 D WifiService: setWifiEnabled: true pid=5536, uid=10077
11-04 14:15:06.467   928  4762 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-04 14:15:06.468  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-04 14:15:06.468  5536  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 14:15:06.468  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:15:06.468  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:15:06.468  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-04 14:15:06.468  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc7f67 removed from the list
11-04 14:15:06.469  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 14:15:06.469  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbdd114 removed from the list
11-04 14:15:06.469  5536  5584 D io.jxcore.node.ConnectivityMonitor: stop
,11-04 14:15:06.469  5536  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-04 14:15:06.469  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:15:06.472  5536  5584 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-04 14:15:06.474  5536  5584 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-04 14:15:06.475  5536  5584 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
11-04 14:15:06.477  5536  5584 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,11-04 14:15:06.479  5536  5584 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
11-04 14:15:06.480  5536  5584 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-04 14:15:06.483  5536  5584 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-04 14:15:06.483  5536  5584 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-04 14:15:06.486  5536  5584 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
11-04 14:15:06.489  5536  5584 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
11-04 14:15:06.489  5536  5584 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4300bca Bundle[{}]
11-04 14:15:06.490  5536  5584 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,11-04 14:15:06.490  5536  5584 I io.jxcore.node.LifeCycleMonitor: start: OK
11-04 14:15:06.490  5536  5584 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-04 14:15:06.491  5536  5584 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-04 14:15:06.491  5536  5584 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-04 14:15:06.491  5536  5584 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-04 14:15:06.491  5536  5584 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-04 14:15:06.492  5536  5584 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-04 14:15:06.492  5536  5584 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-04 14:15:06.492  5536  5584 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-04 14:15:06.493  5536  5584 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-04 14:15:06.495  5536  5584 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,11-04 14:15:06.499  5536  5584 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-04 14:15:06.500  5536  5584 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
11-04 14:15:06.501  5536  5584 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-04 14:15:06.502  5536  5584 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-04 14:15:06.503  5536  5584 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-04 14:15:06.506  5536  5584 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-04 14:15:06.507  5536  5584 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-04 14:15:06.508  5536  5584 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-04 14:15:06.511  5536  5584 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-04 14:15:06.512  5536  5584 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
11-04 14:15:06.512  5536  5584 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
11-04 14:15:06.513  5536  5584 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
11-04 14:15:06.513  5536  5584 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
11-04 14:15:06.513  5536  5584 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-04 14:15:06.513  5536  5584 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 143)
11-04 14:15:06.514  5536  5584 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-04 14:15:06.516  5536  5584 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-04 14:15:06.517  5536  5584 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-04 14:15:06.518  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-04 14:15:06.518  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@487ab03 added. We now have 3 listener(s)
11-04 14:15:06.520  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:15:06.520  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-04 14:15:06.520  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-04 14:15:06.521  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-04 14:15:06.521  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30ea80 added. We now have 3 listener(s)
11-04 14:15:06.521  5536  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 14:15:06.522  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 14:15:06.527  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:15:06.532  5536  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-04 14:15:06.532  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:06.532  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:06.532  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:06.532  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:06.532  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-04 14:15:06.532  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-04 14:15:06.532  5536  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-04 14:15:06.534  5536  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
11-04 14:15:06.534  5536  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-04 14:15:06.536  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:06.538  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-04 14:15:06.542  5796  5796 W Binder_2: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32422]" dev="sockfs" ino=32422 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:06.542  5796  5796 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32422]" dev="sockfs" ino=32422 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:15:06.541  5536  5584 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
11-04 14:15:06.541  5536  5584 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-04 14:15:06.541  5536  5584 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-04 14:15:06.542  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-04 14:15:06.542  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-04 14:15:06.542  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:15:06.542  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-04 14:15:06.542  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:15:06.543  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-04 14:15:06.543  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:15:06.544  5536  5843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:15:06.543  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:15:06.544  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:15:06.544  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-04 14:15:06.544  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:15:06.544  5536  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:15:06.544  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-04 14:15:06.545  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:15:06.545  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 14:15:06.547  5536  5843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-04 14:15:06.552  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:15:06.552  5536  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:15:06.552  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-04 14:15:06.556  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 14:15:06.556  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:15:06.556  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:15:06.558  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.558  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 14:15:06.558  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:15:06.558  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 D4
,11-04 14:15:06.559  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:15:06.559  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.559  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.559  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.559  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:06.560  5536  5584 D BluetoothAdapter: STATE_ON
,11-04 14:15:06.564  5785  5814 D BtGatt.GattService: registerClient() - UUID=dbdf3897-b68e-414c-995e-e52fc496c0c4
,11-04 14:15:06.564  5785  5801 D BtGatt.GattService: onClientRegistered() - UUID=dbdf3897-b68e-414c-995e-e52fc496c0c4, clientIf=5
,11-04 14:15:06.565  5536  5547 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-04 14:15:06.567  5785  5803 D BtGatt.AdvertiseManager: message : 0
,11-04 14:15:06.570  5785  5803 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:15:06.582  5785  5801 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-04 14:15:06.585  5785  5801 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-04 14:15:06.586  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:06.586  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.586  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:15:06.586  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.586  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.586  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.586  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.586  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.586  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 14:15:06.588  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 14:15:06.588  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.589  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.589  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.589  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:06.589  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-04 14:15:06.589  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:15:06.590  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 14:15:06.590  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 14:15:06.590  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:15:06.590  5536  5536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:15:06.590  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:15:06.590  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:15:06.590  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-04 14:15:06.590  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:15:06.590  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 14:15:06.590  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
11-04 14:15:06.590  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-04 14:15:06.593  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-04 14:15:06.593  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:15:06.594  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 14:15:06.594  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 14:15:06.594  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:15:06.594  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
,11-04 14:15:06.594  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-04 14:15:07.095  5536  5536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-04 14:15:07.095  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-04 14:15:07.095  5536  5536 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 14:15:09.779   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-04 14:15:09.779   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-04 14:15:10.091  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,11-04 14:15:10.092  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-04 14:15:10.092  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:15:10.092  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:15:10.092  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-04 14:15:10.093  5536  5843 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 14:15:10.093  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:15:10.093  5536  5843 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-04 14:15:10.093  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-04 14:15:10.093  5536  5843 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:15:10.093  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-04 14:15:10.094  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-04 14:15:10.094  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-04 14:15:10.094  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-04 14:15:10.094  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 14:15:10.094  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
11-04 14:15:10.094  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:15:10.094  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 14:15:10.095  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.095  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.098  5536  5584 D BluetoothAdapter: STATE_ON
,11-04 14:15:10.099  5536  5584 D BluetoothLeScanner: could not find callback wrapper
11-04 14:15:10.099  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-04 14:15:10.099  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.099  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.099  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 14:15:10.100  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.101  5785  5803 D BtGatt.AdvertiseManager: message : 1
11-04 14:15:10.103  5785  5803 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-04 14:15:10.120  5785  5801 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-04 14:15:10.120  5785  5801 D BtGatt.GattService: Client app is not null!
,11-04 14:15:10.122  5785  5822 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 14:15:10.123  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-04 14:15:10.123  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.124  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 14:15:10.124  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.124  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.124  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.124  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-04 14:15:10.124  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-04 14:15:10.125  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.125  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.125  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,11-04 14:15:10.125  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.128  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.128  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 14:15:10.128  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.128  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.128  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.129  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.129  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.129  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:15:10.129  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 14:15:10.130  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:15:10.131  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.133  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.133  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.133  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.134  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-04 14:15:10.134  5536  5536 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 14:15:10.134  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:15:10.134  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:15:10.134  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-04 14:15:10.137  5536  5584 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
11-04 14:15:10.138  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 14:15:10.139  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 14:15:10.139  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-04 14:15:10.139  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-04 14:15:10.139  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:15:10.139  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-04 14:15:10.146  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:15:10.146  5536  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:15:10.146  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-04 14:15:10.153  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-04 14:15:10.154  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-04 14:15:10.154  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-04 14:15:10.159  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.160  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 14:15:10.160  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 14:15:10.160  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-04 14:15:10.161  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 14:15:10.161  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.162  5536  5584 D BluetoothAdapter: STATE_ON
,11-04 14:15:10.166  5785  5795 D BtGatt.GattService: registerClient() - UUID=33289227-586d-4b0b-9bcf-77f0674edeab
,11-04 14:15:10.166  5785  5801 D BtGatt.GattService: onClientRegistered() - UUID=33289227-586d-4b0b-9bcf-77f0674edeab, clientIf=5
,11-04 14:15:10.167  5536  5576 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-04 14:15:10.168  5785  5814 D BtGatt.GattService: start scan with filters
11-04 14:15:10.172  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-04 14:15:10.172  5785  5804 D BtGatt.ScanManager: handling starting scan
11-04 14:15:10.172  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.172  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 14:15:10.173  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.173  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.173  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 14:15:10.173  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-04 14:15:10.173  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.173  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.173  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
11-04 14:15:10.174  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.175  5785  5804 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e9a221f
,11-04 14:15:10.177  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.177  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-04 14:15:10.177  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.177  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-04 14:15:10.177  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.177  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.178  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-04 14:15:10.180  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-04 14:15:10.180  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:10.184  5785  5801 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-04 14:15:10.184  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.184  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:15:10.184  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.184  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:10.185  5785  5804 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 14:15:10.192  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 14:15:10.192  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:15:10.193  5785  5804 D BtGatt.ScanManager: Starting BLE batch scan
11-04 14:15:10.193  5785  5804 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-04 14:15:10.206  5785  5801 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-04 14:15:10.206  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:15:10.214  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-04 14:15:10.214  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:15:10.678  5536  5536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-04 14:15:10.679  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 14:15:10.679  5536  5536 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 14:15:13.187  5536  5584 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-04 14:15:13.188  5536  5584 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-04 14:15:13.188  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,11-04 14:15:13.189  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-04 14:15:13.189  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-04 14:15:13.193  5536  5584 D BluetoothAdapter: STATE_ON
11-04 14:15:13.195  5785  5827 D BtGatt.GattService: stopScan() - queue size =1
11-04 14:15:13.197  5785  5812 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-04 14:15:13.198  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 14:15:13.199  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.199  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 14:15:13.199  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-04 14:15:13.199  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:13.199  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-04 14:15:13.199  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-04 14:15:13.200  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-04 14:15:13.200  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-04 14:15:13.200  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:13.202  5536  5584 D BluetoothAdapter: STATE_ON
11-04 14:15:13.204  5785  5785 D BtGatt.ScanManager: awakened up at time 118333
,11-04 14:15:13.208  5785  5822 D BtGatt.GattService: registerClient() - UUID=e281a6af-e6ad-4b4f-aeb1-b1a1927d8897
11-04 14:15:13.208  5785  5801 D BtGatt.GattService: onClientRegistered() - UUID=e281a6af-e6ad-4b4f-aeb1-b1a1927d8897, clientIf=5
11-04 14:15:13.209  5536  5547 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-04 14:15:13.209  5785  5827 D BtGatt.GattService: start scan with filters
11-04 14:15:13.209  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 14:15:13.209  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:15:13.209  5785  5804 D BtGatt.ScanManager: stopping BLe Batch
,11-04 14:15:13.213  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-04 14:15:13.213  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.213  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-04 14:15:13.213  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.213  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.213  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-04 14:15:13.213  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-04 14:15:13.214  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.214  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.214  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 14:15:13.214  5536  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-04 14:15:13.214  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-04 14:15:13.214  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-04 14:15:13.215  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-04 14:15:13.215  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-04 14:15:13.216  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-04 14:15:13.216  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-04 14:15:13.216  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-04 14:15:13.216  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-04 14:15:13.216  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-04 14:15:13.216  5536  5846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-04 14:15:13.217  5536  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-04 14:15:13.217  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-04 14:15:13.217  5536  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-04 14:15:13.215  5826  5826 W Binder_6: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34023]" dev="sockfs" ino=34023 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:15:13.219  5826  5826 W Binder_6: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34023]" dev="sockfs" ino=34023 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-04 14:15:13.218  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-04 14:15:13.219  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:15:13.219  5785  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 14:15:13.221  5536  5846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-04 14:15:13.227  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:13.227  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.227  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-04 14:15:13.227  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:15:13.227  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 D4
11-04 14:15:13.227  5536  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-04 14:15:13.228  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.228  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:13.228  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.228  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -44]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.229  5536  5584 D BluetoothAdapter: STATE_ON
,11-04 14:15:13.232  5785  5796 D BtGatt.GattService: registerClient() - UUID=d1798239-01eb-4436-b09a-2d895fe27ce2
,11-04 14:15:13.232  5785  5801 D BtGatt.GattService: onClientRegistered() - UUID=d1798239-01eb-4436-b09a-2d895fe27ce2, clientIf=6
,11-04 14:15:13.233  5536  5546 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,11-04 14:15:13.234  5785  5803 D BtGatt.AdvertiseManager: message : 0
,11-04 14:15:13.236  5785  5803 D BtGatt.AdvertiseManager: starting multi advertising
,11-04 14:15:13.240  5785  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
11-04 14:15:13.240  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:15:13.241  5785  5801 D BtGatt.GattService: current time is 118369987040
,11-04 14:15:13.241  5785  5801 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -75, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -83, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -84, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-04 14:15:13.243  5785  5804 D BtGatt.ScanManager: handling starting scan
11-04 14:15:13.243  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-04 14:15:13.245  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-04 14:15:13.245  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 14:15:13.245  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 14:15:13.245  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-04 14:15:13.252  5785  5801 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-04 14:15:13.257  5785  5801 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-04 14:15:13.257  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:15:13.257  5785  5804 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-04 14:15:13.262  5785  5801 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-04 14:15:13.263  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:13.263  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.263  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-04 14:15:13.263  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.263  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.263  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.263  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.263  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:13.263  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.263  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.263  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.264  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
11-04 14:15:13.264  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-04 14:15:13.264  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-04 14:15:13.265  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-04 14:15:13.265  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.267  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-04 14:15:13.267  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:15:13.267  5785  5804 D BtGatt.ScanManager: Starting BLE batch scan
11-04 14:15:13.267  5785  5804 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-04 14:15:13.268  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.268  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.268  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:13.269  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 14:15:13.269  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.269  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,11-04 14:15:13.270  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-75, mTimestampNanos=116620751246}
11-04 14:15:13.270  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 14:15:13.271  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=116220751246}
11-04 14:15:13.271  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 14:15:13.271  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-84, mTimestampNanos=116320751246}
11-04 14:15:13.271  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 14:15:13.271  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-83, mTimestampNanos=115970751246}
11-04 14:15:13.271  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
11-04 14:15:13.271  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=116370751246}
,11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.272  5536  5536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.272  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
11-04 14:15:13.272  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.274  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-04 14:15:13.275  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-04 14:15:13.275  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.275  5536  5536 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.275  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-04 14:15:13.275  5536  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
11-04 14:15:13.275  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
11-04 14:15:13.279  5785  5801 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-04 14:15:13.279  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:15:13.284  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-04 14:15:13.284  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:15:13.776  5536  5536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-04 14:15:13.776  5536  5536 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 14:15:13.777  5536  5536 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-04 14:15:14.780   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:15.781   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:16.272  5536  5584 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
11-04 14:15:16.273  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-04 14:15:16.273  5536  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-04 14:15:16.273  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-04 14:15:16.274  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,11-04 14:15:16.274  5536  5846 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-04 14:15:16.274  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
11-04 14:15:16.275  5536  5846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-04 14:15:16.275  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-04 14:15:16.275  5536  5846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-04 14:15:16.275  5536  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-04 14:15:16.275  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-04 14:15:16.275  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-04 14:15:16.275  5536  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@487ab03 removed from the list
11-04 14:15:16.275  5536  5536 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-04 14:15:16.276  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-04 14:15:16.276  5536  5536 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-04 14:15:16.276  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-04 14:15:16.276  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,11-04 14:15:16.276  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-04 14:15:16.276  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.277  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.277  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-04 14:15:16.280  5536  5584 D BluetoothAdapter: STATE_ON
,11-04 14:15:16.282  5785  5814 D BtGatt.GattService: stopScan() - queue size =1
,11-04 14:15:16.284  5785  5822 D BtGatt.GattService: unregisterClient() - clientIf=5
11-04 14:15:16.285  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-04 14:15:16.286  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.286  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-04 14:15:16.286  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.286  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.286  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-04 14:15:16.286  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-04 14:15:16.287  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.287  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.287  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
11-04 14:15:16.287  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:16.293  5785  5785 D BtGatt.ScanManager: awakened up at time 121422
,11-04 14:15:16.293  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.294  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:15:16.294  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.294  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.295  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.295  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.295  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-04 14:15:16.295  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.297  5785  5803 D BtGatt.AdvertiseManager: message : 1
,11-04 14:15:16.298  5785  5803 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-04 14:15:16.302  5785  5801 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-04 14:15:16.302  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-04 14:15:16.302  5785  5804 D BtGatt.ScanManager: stopping BLe Batch
,11-04 14:15:16.312  5785  5801 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-04 14:15:16.313  5785  5801 D BtGatt.GattService: Client app is not null!
11-04 14:15:16.314  5785  5795 D BtGatt.GattService: unregisterClient() - clientIf=6
11-04 14:15:16.314  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-04 14:15:16.315  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.315  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-04 14:15:16.315  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:16.315  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:16.315  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.315  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-04 14:15:16.316  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-04 14:15:16.316  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.316  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.316  5536  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
11-04 14:15:16.316  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:16.318  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.318  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:15:16.318  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.319  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.319  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.319  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.319  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.319  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-04 14:15:16.319  5536  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-04 14:15:16.320  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
11-04 14:15:16.321  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:16.323  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-04 14:15:16.323  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.323  5536  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-04 14:15:16.323  5536  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b30ea80 removed from the list
11-04 14:15:16.323  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:15:16.323  5536  5584 D io.jxcore.node.ConnectivityMonitor: stop
11-04 14:15:16.323  5536  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-04 14:15:16.323  5536  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-04 14:15:16.323  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
11-04 14:15:16.323  5536  5536 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-04 14:15:16.326  5536  5584 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-04 14:15:16.326  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-04 14:15:16.326  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-04 14:15:16.326  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-04 14:15:16.326  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-04 14:15:16.327  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-04 14:15:16.327  5536  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-04 14:15:16.328  5536  5584 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-04 14:15:16.329  5785  5801 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-04 14:15:16.329  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:15:16.329  5536  5584 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-04 14:15:16.330  5785  5804 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-04 14:15:16.330  5536  5584 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-04 14:15:16.331  5536  5584 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-04 14:15:16.332  5536  5584 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-04 14:15:16.333  5536  5584 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-04 14:15:16.333  5536  5584 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-04 14:15:16.334  5536  5584 I io.jxcore.node.StartStopOperationTest: Starting test: testGet,Callback
,11-04 14:15:16.352  5785  5801 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-04 14:15:16.352  5785  5801 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-04 14:15:16.352  5785  5801 D BtGatt.GattService: current time is 121481527770
,11-04 14:15:16.352  5785  5801 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -75, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -83, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -83, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -89, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-04 14:15:16.352  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-04 14:15:16.353  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-04 14:15:16.353  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-04 14:15:16.353  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-04 14:15:16.353  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-04 14:15:16.353  5785  5801 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-04 14:15:16.761   928  2897 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-04 14:15:16.783   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:16.825  5536  5536 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-04 14:15:16.862   928  2897 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-04 14:15:17.784   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:18.340  5536  5584 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-04 14:15:18.491  5536  5848 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 14:15:18.491  5536  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:15:18.785   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:19.123   928  2897 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-04 14:15:19.125   928  2897 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-04 14:15:19.126   928  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:15:19.138   928  2897 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-04 14:15:19.173   928  2897 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-04 14:15:19.178  5841  5841 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-04 14:15:19.276  5536  5848 W !!      : call onHalfStreamCopied
,11-04 14:15:19.276  5536  5848 I testCopyDataAndClose: closing input stream
,11-04 14:15:19.658  5841  5841 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-04 14:15:19.702  5841  5841 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-04 14:15:19.703  5841  5841 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-04 14:15:19.714   928  2897 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 14:15:19.715   928  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-04 14:15:19.715   928  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-04 14:15:19.733   928  2897 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-04 14:15:19.751   506   921 D CommandListener: Setting iface cfg
,11-04 14:15:19.757   928  2897 D WifiStateMachine: Start Dhcp Watchdog 2
,11-04 14:15:19.763   928  5852 D DhcpClient: Receive thread started
,11-04 14:15:19.768   928  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 14:15:19.768   928  2897 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-04 14:15:19.769   928  2904 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-04 14:15:19.785   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-04 14:15:19.850   928  2897 E native  : do suspend false
,11-04 14:15:19.859   928  5851 D DhcpClient: Broadcasting DHCPDISCOVER
,11-04 14:15:19.872   928  5852 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.105, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172717, domain null
,11-04 14:15:19.872   928  5851 D DhcpClient: Got pending lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172717 seconds
,11-04 14:15:19.873   928  5851 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.105 serverid=192.168.1.1
,11-04 14:15:19.886   928  5852 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.105, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-04 14:15:19.887   928  5851 D DhcpClient: Confirmed lease: IP address 192.168.1.105/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-04 14:15:19.888   506   921 D CommandListener: Setting iface cfg
,11-04 14:15:19.891   928  2897 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-04 14:15:19.893   928  5851 D DhcpClient: Scheduling renewal in 86399s
,11-04 14:15:19.900   928  2897 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-04 14:15:19.900   928  2897 D WifiConfigStore: No blacklist allowed without epno enabled
11-04 14:15:19.901   928  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-04 14:15:19.902   928  2897 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-04 14:15:19.908   928  2904 D ConnectivityService: Adding iface wlan0 to network 101
,11-04 14:15:19.938   928  2904 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-04 14:15:19.938   928  2904 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-04 14:15:19.940   928  2904 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-04 14:15:19.942   928  2904 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-04 14:15:19.944   928  2904 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-04 14:15:19.953   928  2904 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 14:15:19.958   928  2904 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-04 14:15:19.958   928  2904 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-04 14:15:19.958   928  2904 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-04 14:15:19.958   928  2904 D ConnectivityService:    accepting network in place of null
11-04 14:15:19.958   928  2897 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-04 14:15:19.958   928  2897 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-04 14:15:19.959   928  2904 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-04 14:15:19.969   928  5850 D NetlinkSocketObserver: NeighborEvent{elapsedMs=125098, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-04 14:15:19.980   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:15:20.000   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-04 14:15:20.005   928  2904 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-04 14:15:20.005   928  2904 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-04 14:15:20.005  3642  3784 W QCNEJ   : |CORE| network available: 101
11-04 14:15:20.007   928  2904 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-04 14:15:20.010   928   945 D Tethering: MasterInitialState.processMessage what=3
11-04 14:15:20.012  3642  3784 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-04 14:15:20.013  3642  3784 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-04 14:15:20.015  3642  3784 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.105/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-04 14:15:20.020  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:20.020  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:20.020  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:20.020  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:20.020  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:20.020  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:15:20.020  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:15:20.020  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-04 14:15:20.023  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,11-04 14:15:20.027  3878  3878 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-04 14:15:20.028  5536  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-04 14:15:20.028  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-04 14:15:20.028  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-04 14:15:20.028  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-04 14:15:20.028  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-04 14:15:20.028  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-04 14:15:20.028  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-04 14:15:20.028  5536  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-04 14:15:20.030  3954  3954 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-04 14:15:20.031  5536  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
11-04 14:15:20.033  3954  3954 D SystemUpdateService: onCreate
,11-04 14:15:20.036  3954  3954 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-04 14:15:20.045  5536  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 14:15:20.047  3954  3954 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-04 14:15:20.053  3954  5861 I SystemUpdateService: active receiver: enabled
,11-04 14:15:20.059   928  5849 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-04 14:15:20.068  3954  3954 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-04 14:15:20.070  3954  3954 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-04 14:15:20.073  5619  5619 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-04 14:15:20.077  5619  5619 D SprintDMHelper: simOperator: 
11-04 14:15:20.077  5619  5619 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-04 14:15:20.101  3954  5861 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-04 14:15:20.106  3954  5861 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-04 14:15:20.106  3954  5861 I SystemUpdateService: now status is 0 (complete)
11-04 14:15:20.106  3954  5861 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-04 14:15:20.106  3954  5861 I SystemUpdateService: file has been verified
11-04 14:15:20.107  3954  5861 I SystemUpdateService: OTA package size = 21989297
,11-04 14:15:20.055  3954  4166 I iu.UploadsManager: num queued entries: 0
,11-04 14:15:20.112  3954  4166 I iu.UploadsManager: num updated entries: 0
,11-04 14:15:20.114  3954  5861 I SystemUpdateService: showing system update notification
,11-04 14:15:20.115  3954  4166 I iu.SyncManager: NEXT; no task
,11-04 14:15:20.121   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-04 14:15:20.122   928  5849 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Nov 2016 13:15:20 GMT], X-Android-Received-Millis=[1478265320121], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1478265320093]}
,11-04 14:15:20.122   928  2904 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-04 14:15:20.122  3954  3954 D SystemUpdateService: onDestroy
,11-04 14:15:20.122   928  2904 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-04 14:15:20.123   928  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-04 14:15:20.123   928  2904 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-04 14:15:21.007   928  2904 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-04 14:15:21.270   928  2897 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,11-04 14:15:22.789   928  2904 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-04 14:15:24.472  5536  5584 I StreamCopyingThreadTest: Starting test: testRun
,11-04 14:15:24.475  5536  5869 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:15:24.475  5536  5869 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:15:24.786   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:25.788   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:26.789   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:27.791   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:27.964   928  2904 D ConnectivityService: handlePromptUnvalidated 101
,11-04 14:15:28.792   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:29.483  5536  5870 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,11-04 14:15:29.486  5536  5584 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-04 14:15:29.622  5536  5871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 14:15:29.622  5536  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:15:29.793   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-04 14:15:31.213  3577  3638 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-04 14:15:31.213  3577  3638 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-04 14:15:31.247  3510  3510 I ConfigService: onCreate
,11-04 14:15:31.264  5536  5871 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 14:15:31.264  5536  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:15:31.264  5536  5871 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 14:15:31.264  5536  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:15:31.264  5536  5871 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 14:15:31.265  5536  5871 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-04 14:15:31.265  5536  5871 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 14:15:31.265  5536  5871 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-04 14:15:31.265  5536  5871 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 14:15:31.265  5536  5871 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-04 14:15:31.265  5536  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-04 14:15:35.516  5536  5584 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-04 14:15:35.518  5536  5873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:15:35.518  5536  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-04 14:15:35.519  5536  5873 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:15:35.519  5536  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 14:15:35.519  5536  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-04 14:15:35.519  5536  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 14:15:35.519  5536  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-04 14:15:35.519  5536  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-04 14:15:35.519  5536  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-04 14:15:35.519  5536  5873 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-04 14:15:35.519  5536  5873 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-04 14:15:35.520  5536  5873 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:15:35.520  5536  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-04 14:15:35.521  5536  5584 I StreamCopyingThreadTest: Starting test: testSetBufferSize
11-04 14:15:35.521  5536  5584 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-04 14:15:35.522  5536  5584 I StreamCopyingThreadTest: Starting test: testRunWithException
11-04 14:15:35.524  5536  5874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:15:35.524  5536  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-04 14:15:35.525  5536  5874 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
,11-04 14:15:35.525  5536  5874 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:15:35.525  5536  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-04 14:15:35.526  5536  5874 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-04 14:15:35.526  5536  5874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
11-04 14:15:35.526  5536  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-04 14:15:35.528  5536  5584 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
,11-04 14:15:35.528  5536  5584 E com.test.thalitest.ThaliTestRunner: 
11-04 14:15:35.528  5536  5584 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-04 14:15:35.528  5536  5584 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRun,ner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
11-04 14:15:35.529 , 5536  5584 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner:      but: was <false>
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268),
,11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	,at org.junit.runners.Suite.runChild(Suite.java:27)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:35.529  5536  5584 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
11-04 14:15:35.533  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG UnitTest_app: 'Running unit tests'
11-04 14:15:35.533  5536  5584 I jxcore-log: 
11-04 14:15:35.533  5536  5584 I jxcore-log: *Native tests were executed*
11-04 14:15:35.533  5536  5584 I jxcore-log: 
11-04 14:15:35.533  5536  5584 I jxcore-log: Total number of executed tests:  82
11-04 14:15:35.533  5536  5584 I jxcore-log: 
11-04 14:15:35.533  5536  5584 I jxcore-log: Number of passed tests:  80
11-04 14:15:35.533  5536  5584 I jxcore-log: 
11-04 14:15:35.533  5536  5584 I jxcore-log: Number of failed tests:  2
11-04 14:15:35.533  5536  5584 I jxcore-log: 
11-04 14:15:35.533  5536  5584 I jxcore-log: Number of ignored tests:  0
11-04 14:15:35.533  5536  5584 I jxcore-log: 
11-04 14:15:35.533  5536  5584 I jxcore-log: Total duration:  43143
11-04 14:15:35.533  5536  5584 I jxcore-log: 
11-04 14:15:35.534  5536  5584 I jxcore-log: Failed to execute UT.
11-04 14:15:35.534  5536  5584 I jxcore-log: 
11-04 14:15:35.534  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-04 14:15:35.534  5536  5584 I jxcore-log: 
11-04 14:15:35.536  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-04 14:15:35.536  5536  5584 I jxcore-log: 
11-04 14:15:35.538  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"b,luetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:15:35.538  5536  5584 I jxcore-log: 
11-04 14:15:35.539  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.539  5536  5584 I jxcore-log: 
11-04 14:15:35.540  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:15:35.540  5536  5584 I jxcore-log: 
11-04 14:15:35.540  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.540  5536  5584 I jxcore-log: 
11-04 14:15:35.541  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:15:35.541  5536  5584 I jxcore-log: 
11-04 14:15:35.541  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.541  5536  5584 I jxcore-log: 
11-04 14:15:35.542  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 14:15:35.542  5536  5584 I jxcore-log: 
11-04 14:15:35.542  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 14:15:35.542  5536  5584 I jxcore-log: 
11-04 14:15:35.542  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 14:15:35.542  5536  5584 I jxcore-log: 
11-04 14:15:35.542  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 14:15:35.542  5536  5584 I jxcore-log: 
11-04 14:15:35.543  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:15:35.543  5536  5584 I jxcore-log: 
11-04 14:15:35.543  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.543  5536  5584 I jxcore-log: 
11-04 14:15:35.543  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.543  5536  5584 I jxcore-log: 
11-04 14:15:35.543  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.543  5536  5584 I jxcore-log: 
11-04 14:15:35.543  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.543  5536  5584 I jxcore-log: 
11-04 14:15:35.544  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.544  5536  5584 I jxcore-log: 
11-04 14:15:35.544  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.544  5536  5584 I jxcore-log: 
11-04 14:15:35.544  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.544  5536  5584 I jxcore-log: 
11-04 14:15:35.544  5536  5584 I jxcore-log: 2016-11-04 13:15:35, - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 14:15:35.544  5536  5584 I jxcore-log: 
11-04 14:15:35.545  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:15:35.545  5536  5584 I jxcore-log: 
11-04 14:15:35.545  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.545  5536  5584 I jxcore-log: 
11-04 14:15:35.545  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:15:35.545  5536  5584 I jxcore-log: 
11-04 14:15:35.545  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.545  5536  5584 I jxcore-log: 
11-04 14:15:35.545  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:15:35.545  5536  5584 I jxcore-log: 
11-04 14:15:35.546  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.546  5536  5584 I jxcore-log: 
11-04 14:15:35.546  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.546  5536  5584 I jxcore-log: 
11-04 14:15:35.546  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.546  5536  5584 I jxcore-log: 
,11-04 14:15:35.546  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.546  5536  5584 I jxcore-log: 
11-04 14:15:35.547  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.547  5536  5584 I jxcore-log: 
11-04 14:15:35.548  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.548  5536  5584 I jxcore-log: 
11-04 14:15:35.548  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.548  5536  5584 I jxcore-log: 
11-04 14:15:35.548  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
,11-04 14:15:35.548  5536  5584 I jxcore-log: 
11-04 14:15:35.549  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.549  5536  5584 I jxcore-log: 
11-04 14:15:35.549  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.549  5536  5584 I jxcore-log: 
11-04 14:15:35.549  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.549  5536  5584 I jxcore-log: 
11-04 14:15:35.549  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.549  5536  5584 I jxcore-log: 
,11-04 14:15:35.550  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.550  5536  5584 I jxcore-log: 
11-04 14:15:35.550  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.550  5536  5584 I jxcore-log: 
11-04 14:15:35.550  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.550  5536  5584 I jxcore-log: 
,11-04 14:15:35.550  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.550  5536  5584 I jxcore-log: 
11-04 14:15:35.550  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.550  5536  5584 I jxcore-log: 
11-04 14:15:35.551  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.551  5536  5584 I jxcore-log: 
11-04 14:15:35.551  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.551  5536  5584 I jxcore-log: 
,11-04 14:15:35.551  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.551  5536  5584 I jxcore-log: 
11-04 14:15:35.551  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.551  5536  5584 I jxcore-log: 
11-04 14:15:35.551  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.551  5536  5584 I jxcore-log: 
11-04 14:15:35.551  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.551  5536  5584 I jxcore-log: 
11-04 14:15:35.552  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.552  5536  5584 I jxcore-log: 
,11-04 14:15:35.552  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.552  5536  5584 I jxcore-log: 
11-04 14:15:35.552  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.552  5536  5584 I jxcore-log: 
11-04 14:15:35.552  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.552  5536  5584 I jxcore-log: 
11-04 14:15:35.552  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.552  5536  5584 I jxcore-log: 
11-04 14:15:35.553  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.553  5536  5584 I jxcore-log: 
11-04 14:15:35.553  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.553  5536  5584 I jxcore-log: 
11-04 14:15:35.553  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.553  5536  5584 I jxcore-log: 
11-04 14:15:35.553  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:15:35.553  5536  5584 I jxcore-log: 
11-04 14:15:35.553  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.553  5536  5584 I jxcore-log: 
11-04 14:15:35.553  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:15:35.553  5536  5584 I jxcore-log: 
,11-04 14:15:35.554  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.554  5536  5584 I jxcore-log: 
11-04 14:15:35.554  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-04 14:15:35.554  5536  5584 I jxcore-log: 
11-04 14:15:35.554  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.554  5536  5584 I jxcore-log: 
11-04 14:15:35.554  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.554  5536  5584 I jxcore-log: 
,11-04 14:15:35.554  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.554  5536  5584 I jxcore-log: 
11-04 14:15:35.555  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.555  5536  5584 I jxcore-log: 
11-04 14:15:35.555  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.555  5536  5584 I jxcore-log: 
11-04 14:15:35.555  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.555  5536  5584 I jxcore-log: 
11-04 14:15:35.555  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).',
11-04 14:15:35.555  5536  5584 I jxcore-log: 
11-04 14:15:35.555  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-04 14:15:35.555  5536  5584 I jxcore-log: 
11-04 14:15:35.555  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.555  5536  5584 I jxcore-log: 
11-04 14:15:35.556  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-04 14:15:35.556  5536  5584 I jxcore-log: 
11-04 14:15:35.556  5536  5536 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-04 14:15:35.556  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-04 14:15:35.556  5536  5584 I jxcore-log: 
,11-04 14:15:35.556  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-04 14:15:35.556  5536  5584 I jxcore-log: 
11-04 14:15:35.556  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-04 14:15:35.556  5536  5584 I jxcore-log: 
11-04 14:15:35.557  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:15:35.557  5536  5584 I jxcore-log: 
11-04 14:15:35.557  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.557  5536  5584 I jxcore-log: 
11-04 14:15:35.557  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
11-04 14:15:35.557  5536  5584 I jxcore-log: 
11-04 14:15:35.557  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-04 14:15:35.557  5536  5584 I jxcore-log: 
,11-04 14:15:35.562  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-04 14:15:35.562  5536  5584 I jxcore-log: 
11-04 14:15:35.563  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - WARN testUtils: 'myNameCallback not set!'
11-04 14:15:35.563  5536  5584 I jxcore-log: 
11-04 14:15:35.563  5536  5584 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
11-04 14:15:35.564  5536  5584 I jxcore-log: 2016-11-04 13:15:35 - DEBUG UnitTest_app: 'Running for NATIVE network type'
11-04 14:15:35.564  5536  5584 I jxcore-log: 
,11-04 14:15:36.289  3510  3510 I ConfigService: onDestroy
,11-04 14:15:37.553  5536  5584 I jxcore-log: 2016-11-04 13:15:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-04 14:15:37.553  5536  5584 I jxcore-log: 
,11-04 14:15:37.876  5536  5584 I jxcore-log: 2016-11-04 13:15:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-04 14:15:37.876  5536  5584 I jxcore-log: 
,11-04 14:15:37.890  5536  5584 I jxcore-log: 2016-11-04 13:15:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-04 14:15:37.890  5536  5584 I jxcore-log: 
,11-04 14:15:38.958  5536  5584 I jxcore-log: 2016-11-04 13:15:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-04 14:15:38.958  5536  5584 I jxcore-log: 
,11-04 14:15:39.121  5536  5584 I jxcore-log: 2016-11-04 13:15:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-04 14:15:39.121  5536  5584 I jxcore-log: 
,11-04 14:15:39.127  5536  5584 I jxcore-log: 2016-11-04 13:15:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-04 14:15:39.127  5536  5584 I jxcore-log: 
,11-04 14:15:39.131  5536  5584 I jxcore-log: 2016-11-04 13:15:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-04 14:15:39.131  5536  5584 I jxcore-log: 
,11-04 14:15:39.599  5536  5584 I jxcore-log: 2016-11-04 13:15:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-04 14:15:39.599  5536  5584 I jxcore-log: 
,11-04 14:15:39.641  5536  5584 I jxcore-log: 2016-11-04 13:15:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-04 14:15:39.641  5536  5584 I jxcore-log: 
,11-04 14:15:39.654  5536  5584 I jxcore-log: 2016-11-04 13:15:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-04 14:15:39.654  5536  5584 I jxcore-log: 
,11-04 14:15:39.658  5536  5584 I jxcore-log: 2016-11-04 13:15:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-04 14:15:39.658  5536  5584 I jxcore-log: 
,11-04 14:15:39.794   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:39.933  5536  5584 I jxcore-log: 2016-11-04 13:15:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-04 14:15:39.933  5536  5584 I jxcore-log: 
,11-04 14:15:40.070  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-04 14:15:40.070  5536  5584 I jxcore-log: 
,11-04 14:15:40.436  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-04 14:15:40.436  5536  5584 I jxcore-log: 
,11-04 14:15:40.472  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-04 14:15:40.472  5536  5584 I jxcore-log: 
,11-04 14:15:40.479  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-04 14:15:40.479  5536  5584 I jxcore-log: 
,11-04 14:15:40.485  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-04 14:15:40.485  5536  5584 I jxcore-log: 
,11-04 14:15:40.494  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-04 14:15:40.494  5536  5584 I jxcore-log: 
,11-04 14:15:40.507  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-04 14:15:40.507  5536  5584 I jxcore-log: 
,11-04 14:15:40.513  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-04 14:15:40.513  5536  5584 I jxcore-log: 
,11-04 14:15:40.541  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-04 14:15:40.541  5536  5584 I jxcore-log: 
,11-04 14:15:40.578  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-04 14:15:40.578  5536  5584 I jxcore-log: 
,11-04 14:15:40.586  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-04 14:15:40.586  5536  5584 I jxcore-log: 
,11-04 14:15:40.592  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-04 14:15:40.592  5536  5584 I jxcore-log: 
,11-04 14:15:40.607  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-04 14:15:40.607  5536  5584 I jxcore-log: 
,11-04 14:15:40.611  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-04 14:15:40.611  5536  5584 I jxcore-log: 
,11-04 14:15:40.617  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-04 14:15:40.617  5536  5584 I jxcore-log: 
,11-04 14:15:40.622  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-04 14:15:40.622  5536  5584 I jxcore-log: 
,11-04 14:15:40.635  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-04 14:15:40.635  5536  5584 I jxcore-log: 
,11-04 14:15:40.642  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-04 14:15:40.642  5536  5584 I jxcore-log: 
,11-04 14:15:40.663  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-04 14:15:40.663  5536  5584 I jxcore-log: 
,11-04 14:15:40.674  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-04 14:15:40.674  5536  5584 I jxcore-log: 
,11-04 14:15:40.686  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-04 14:15:40.686  5536  5584 I jxcore-log: 
,11-04 14:15:40.696  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-04 14:15:40.696  5536  5584 I jxcore-log: 
,11-04 14:15:40.709  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-04 14:15:40.709  5536  5584 I jxcore-log: 
,11-04 14:15:40.718  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-04 14:15:40.718  5536  5584 I jxcore-log: 
,11-04 14:15:40.725  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-04 14:15:40.725  5536  5584 I jxcore-log: 
,11-04 14:15:40.731  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-04 14:15:40.731  5536  5584 I jxcore-log: 
,11-04 14:15:40.736  5536  5584 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-04 14:15:40.737  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - INFO testUtils: 'BLE multiple advertisement supported'
11-04 14:15:40.737  5536  5584 I jxcore-log: 
,11-04 14:15:40.795   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:40.926  5536  5584 I jxcore-log: 2016-11-04 13:15:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:40.926  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:40.926  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:40.926  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:40.926  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:40.926  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:40.926  5536  5584 I jxcore-log: 
,11-04 14:15:41.245  5536  5584 I jxcore-log: 2016-11-04 13:15:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:41.245  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:41.245  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:41.245  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:41.245  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:41.245  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:41.245  5536  5584 I jxcore-log: 
,11-04 14:15:41.252  5536  5584 I jxcore-log: 2016-11-04 13:15:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:41.252  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:41.252  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:41.252  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:41.252  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:41.252  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:41.252  5536  5584 I jxcore-log: 
,11-04 14:15:41.741  5536  5584 I jxcore-log: 2016-11-04 13:15:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:41.741  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:41.741  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:41.741  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:41.741  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:41.741  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:41.741  5536  5584 I jxcore-log: 
,11-04 14:15:41.745  5536  5584 I jxcore-log: 2016-11-04 13:15:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:41.745  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:41.745  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:41.745  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:41.745  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:41.745  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:41.745  5536  5584 I jxcore-log: 
,11-04 14:15:41.796   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:42.698  5536  5584 I jxcore-log: 2016-11-04 13:15:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:42.698  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:42.698  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:42.698  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:42.698  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:42.698  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:42.698  5536  5584 I jxcore-log: 
,11-04 14:15:42.703  5536  5584 I jxcore-log: 2016-11-04 13:15:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:42.703  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:42.703  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:42.703  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:42.703  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:42.703  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:42.703  5536  5584 I jxcore-log: 
,11-04 14:15:42.797   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:43.654  5536  5584 I jxcore-log: 2016-11-04 13:15:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:43.654  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:43.654  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:43.654  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:43.654  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:43.654  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:43.654  5536  5584 I jxcore-log: 
,11-04 14:15:43.659  5536  5584 I jxcore-log: 2016-11-04 13:15:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:43.659  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:43.659  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:43.659  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:43.659  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:43.659  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:43.659  5536  5584 I jxcore-log: 
,11-04 14:15:43.798   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-04 14:15:44.698  5536  5584 I jxcore-log: 2016-11-04 13:15:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:44.698  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:44.698  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:44.698  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:44.698  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:44.698  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:44.698  5536  5584 I jxcore-log: 
,11-04 14:15:44.703  5536  5584 I jxcore-log: 2016-11-04 13:15:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:44.703  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:44.703  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:44.703  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:44.703  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:44.703  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:44.703  5536  5584 I jxcore-log: 
,11-04 14:15:44.798   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-04 14:15:45.960  5536  5584 I jxcore-log: 2016-11-04 13:15:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:45.960  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:45.960  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:45.960  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:45.960  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:45.960  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:45.960  5536  5584 I jxcore-log: 
,11-04 14:15:45.965  5536  5584 I jxcore-log: 2016-11-04 13:15:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:45.965  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:45.965  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:45.965  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:45.965  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:45.965  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:45.965  5536  5584 I jxcore-log: 
,11-04 14:15:47.001  5536  5584 I jxcore-log: 2016-11-04 13:15:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:47.001  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:47.001  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:47.001  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:47.001  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:47.001  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:47.001  5536  5584 I jxcore-log: 
,11-04 14:15:47.005  5536  5584 I jxcore-log: 2016-11-04 13:15:47 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:47.005  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:47.005  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:47.005  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:47.005  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:47.005  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:47.005  5536  5584 I jxcore-log: 
,11-04 14:15:47.715   928   948 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,11-04 14:15:47.719  3124  3124 W Binder_5: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32927]" dev="sockfs" ino=32927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:47.725  3577  3577 I Keyboard.Facilitator: onFinishInput()
11-04 14:15:47.722  3124  3124 W Binder_5: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[32927]" dev="sockfs" ino=32927 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:47.732   928   948 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 14:15:47.732   928   948 I Adreno  : Build Date                       : 12/06/15
11-04 14:15:47.732   928   948 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 14:15:47.732   928   948 I Adreno  : Local Branch                     : mybranch17112971
11-04 14:15:47.732   928   948 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 14:15:47.732   928   948 I Adreno  : Remote Branch                    : NONE
11-04 14:15:47.732   928   948 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 14:15:47.765   383   406 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (178 us)
,11-04 14:15:48.029  5536  5584 I jxcore-log: 2016-11-04 13:15:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:48.029  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:48.029  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:48.029  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:48.029  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:48.029  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:48.029  5536  5584 I jxcore-log: 
,11-04 14:15:48.031  5536  5584 I jxcore-log: 2016-11-04 13:15:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:48.031  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:48.031  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:48.031  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:48.031  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:48.031  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:48.031  5536  5584 I jxcore-log: 
,11-04 14:15:48.459  5536  5536 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-04 14:15:48.460  5536  5536 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,11-04 14:15:48.488   928   948 I sensors : batch
,11-04 14:15:48.488   928   948 V KeyguardServiceDelegate: onScreenTurnedOff()
,11-04 14:15:48.490  5536  5536 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4300bca Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@181a744, 16908290=android.view.AbsSavedState$1@181a744}, android:focusedViewId=100}]}]
,11-04 14:15:48.490  5536  5536 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
11-04 14:15:48.491  5536  5536 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-04 14:15:48.491  5536  5536 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,11-04 14:15:48.494   928  2685 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
11-04 14:15:48.495   928   948 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
11-04 14:15:48.495   928   948 I sensors : activate
,11-04 14:15:48.496   928   946 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,11-04 14:15:48.498   383   383 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f83383c00
11-04 14:15:48.498   383   383 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,11-04 14:15:48.502   928  2685 I hubconnection: sensorhub said: 'activate 7 enable:0'
,11-04 14:15:48.715   506   921 D TetherController: Setting IP forward enable = 1
,11-04 14:15:48.786   383   478 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,11-04 14:15:48.787   383   383 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,11-04 14:15:48.787   928  3013 D SurfaceControl: Excessive delay in setPowerMode(): 291ms
,11-04 14:15:48.792   928   948 I DreamManagerService: Entering dreamland.
,11-04 14:15:48.793   928   948 I PowerManagerService: Dozing...
11-04 14:15:48.793   928   943 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,11-04 14:15:48.809  4763  4763 W Binder_B: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[34100]" dev="sockfs" ino=34100 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:48.809  4763  4763 W Binder_B: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[34100]" dev="sockfs" ino=34100 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:15:48.813   928  3722 I sensors : batch
,11-04 14:15:48.815   928  3722 I sensors : activate
,11-04 14:15:48.818   928  2685 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,11-04 14:15:48.820   928  2685 I hubconnection: sensorhub said: 'activate 21 enable:1'
,11-04 14:15:48.823   511  2925 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,11-04 14:15:48.827   928  2897 E native  : do suspend false
,11-04 14:15:48.833   928  2897 D WifiConfigStore: No blacklist allowed without epno enabled
,11-04 14:15:48.841  3679  4660 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,11-04 14:15:48.841  3679  4660 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 14:15:48.841  3679  4660 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
,11-04 14:15:48.841   524  1329 D         : oem-qmi: Connection accepted
11-04 14:15:48.842   524  1329 D         : oem-qmi: Waiting to accept connection
,11-04 14:15:48.844   928   928 I sensors : activate
,11-04 14:15:48.844  3679  4660 D         : oem_qmi_lib:output 0
11-04 14:15:48.844  3679  4660 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
11-04 14:15:48.844   511  2959 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
11-04 14:15:48.846   928  2897 E native  : do suspend true
,11-04 14:15:48.846   928  2685 I hubconnection: sensorhub said: 'activate 31 enable:0'
,11-04 14:15:48.863  3679  4660 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,11-04 14:15:48.864  3679  4660 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
11-04 14:15:48.864  3679  4660 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
11-04 14:15:48.864   524  1329 D         : oem-qmi: Connection accepted
11-04 14:15:48.864   524  1329 D         : oem-qmi: Waiting to accept connection
,11-04 14:15:48.866  3679  4660 D         : oem_qmi_lib:output 0
,11-04 14:15:48.866  3679  4660 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,11-04 14:15:49.056  5536  5584 I jxcore-log: 2016-11-04 13:15:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:49.056  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:49.056  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:49.056  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:49.056  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:49.056  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:49.056  5536  5584 I jxcore-log: 
,11-04 14:15:49.059  5536  5584 I jxcore-log: 2016-11-04 13:15:49 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:49.059  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:49.059  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:49.059  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:49.059  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:49.059  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:49.059  5536  5584 I jxcore-log: 
,11-04 14:15:49.327   928  2897 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,11-04 14:15:50.130  5536  5584 I jxcore-log: 2016-11-04 13:15:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:50.130  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:50.130  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:50.130  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:50.130  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:50.130  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:50.130  5536  5584 I jxcore-log: 
,11-04 14:15:50.136  5536  5584 I jxcore-log: 2016-11-04 13:15:50 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:50.136  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:50.136  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:50.136  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:50.136  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:50.136  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:50.136  5536  5584 I jxcore-log: 
,11-04 14:15:51.170  5536  5584 I jxcore-log: 2016-11-04 13:15:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:51.170  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:51.170  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:51.170  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:51.170  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:51.170  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:51.170  5536  5584 I jxcore-log: 
,11-04 14:15:51.176  5536  5584 I jxcore-log: 2016-11-04 13:15:51 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:51.176  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:51.176  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:51.176  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:51.176  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:51.176  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:51.176  5536  5584 I jxcore-log: 
,11-04 14:15:52.207  5536  5584 I jxcore-log: 2016-11-04 13:15:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:52.207  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:52.207  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:52.207  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:52.207  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:52.207  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:52.207  5536  5584 I jxcore-log: 
,11-04 14:15:52.213  5536  5584 I jxcore-log: 2016-11-04 13:15:52 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:52.213  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:52.213  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:52.213  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:52.213  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:52.213  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:52.213  5536  5584 I jxcore-log: 
,11-04 14:15:52.221   928  5850 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157350, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-04 14:15:52.358  3864  4368 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-04 14:15:53.243  5536  5584 I jxcore-log: 2016-11-04 13:15:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:53.243  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:53.243  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:53.243  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:53.243  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:53.243  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:53.243  5536  5584 I jxcore-log: 
,11-04 14:15:53.247  5536  5584 I jxcore-log: 2016-11-04 13:15:53 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:53.247  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:53.247  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:53.247  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:53.247  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:53.247  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:53.247  5536  5584 I jxcore-log: 
,11-04 14:15:54.280  5536  5584 I jxcore-log: 2016-11-04 13:15:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:54.280  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:54.280  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:54.280  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:54.280  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:54.280  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:54.280  5536  5584 I jxcore-log: 
,11-04 14:15:54.284  5536  5584 I jxcore-log: 2016-11-04 13:15:54 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:54.284  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:54.284  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:54.284  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:54.284  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:54.284  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:54.284  5536  5584 I jxcore-log: 
,11-04 14:15:55.319  5536  5584 I jxcore-log: 2016-11-04 13:15:55 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-04 14:15:55.319  5536  5584 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-04 14:15:55.319  5536  5584 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-04 14:15:55.319  5536  5584 I jxcore-log: emit@events.js:82:1
11-04 14:15:55.319  5536  5584 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-04 14:15:55.319  5536  5584 I jxcore-log: emit@events.js:82:1'
11-04 14:15:55.319  5536  5584 I jxcore-log: 
,11-04 14:15:55.330  5536  5584 E jxcore  : Error!: error is undefined
11-04 14:15:55.330  5536  5584 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-04 14:15:55.336  5536  5584 I jxcore-log: 2016-11-04 13:15:55 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-04 14:15:55.336  5536  5584 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
11-04 14:15:55.336  5536  5584 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-04 14:15:55.336  5536  5584 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-04 14:15:55.336  5536  5584 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-04 14:15:55.336  5536  5584 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-04 14:15:55.336  5536  5584 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-04 14:15:55.336  5536  5584 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-04 14:15:55.339  5536  5584 I jxcore-log: 2016-11-04 13:15:55 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-04 14:15:55.339  5536  5584 I jxcore-log: 
11-04 14:15:55.341  5536  5584 E jxcore-log: TypeError: 
11-04 14:15:55.341  5536  5584 E jxcore-log: error is undefined
11-04 14:15:55.342  5536  5584 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
11-04 14:15:55.342  5536  5584 E jxcore-log: 
,11-04 14:15:55.441   928  2903 D WifiService: Client connection lost with reason: 4
11-04 14:15:55.441   928  3738 I WindowState: WIN DEATH: Window{fc75357 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-04 14:15:55.439   928  3527 D GraphicsStats: Buffer count: 2
,11-04 14:15:55.449   526   526 I Zygote  : Process 5536 exited cleanly (139)
,11-04 14:15:55.450   928  3722 I ActivityManager: Process com.test.thalitest (pid 5536) has died
,11-04 14:15:55.465   928  3722 I ActivityManager: Start proc 5920:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,11-04 14:15:55.535  5920  5920 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-04 14:15:55.554  5920  5920 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-04 14:15:55.560  5920  5920 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 687-689)
,11-04 14:15:55.560  5920  5920 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-04 14:15:55.570  5920  5920 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b4db527}
,11-04 14:15:55.570  5920  5920 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-04 14:15:55.571  5920  5920 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-04 14:15:55.574  5920  5920 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-04 14:15:55.575  5920  5920 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-04 14:15:55.586  5920  5920 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-04 14:15:55.594  5920  5920 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-04 14:15:55.594  5920  5920 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-04 14:15:55.594  5920  5920 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-04 14:15:55.594  5920  5920 I Adreno  : Build Date                       : 12/06/15
11-04 14:15:55.594  5920  5920 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-04 14:15:55.594  5920  5920 I Adreno  : Local Branch                     : mybranch17112971
11-04 14:15:55.594  5920  5920 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-04 14:15:55.594  5920  5920 I Adreno  : Remote Branch                    : NONE
11-04 14:15:55.594  5920  5920 I Adreno  : Reconstruct Branch               : NOTHING
,11-04 14:15:55.627   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20a7bd4:true
,11-04 14:15:55.639   404   404 W Binder_1: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[16008]" dev="sockfs" ino=16008 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:55.639   404   404 W Binder_1: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[16008]" dev="sockfs" ino=16008 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:55.651  5920  5920 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-04 14:15:55.659  5920  5920 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-04 14:15:55.689   404   404 W Binder_1: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[32659]" dev="sockfs" ino=32659 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:55.694  5920  5956 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-04 14:15:55.689   404   404 W Binder_1: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[32659]" dev="sockfs" ino=32659 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:55.692  3051  3051 W Binder_3: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[13998]" dev="sockfs" ino=13998 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:55.692  3051  3051 W Binder_3: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[13998]" dev="sockfs" ino=13998 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:55.699  5920  5943 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-04 14:15:55.726  5920  5956 I OpenGLRenderer: Initialized EGL, version 1.4
,11-04 14:15:55.740   928  3722 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5536 uid 10077
,11-04 14:15:55.742  3577  3577 I Keyboard.Facilitator: onFinishInput()
,11-04 14:15:55.736  3722  3722 W Binder_8: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[14000]" dev="sockfs" ino=14000 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:15:55.736  3722  3722 W Binder_8: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[14000]" dev="sockfs" ino=14000 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:55.739  4763  4763 W Binder_B: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[13999]" dev="sockfs" ino=13999 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:15:55.739  4763  4763 W Binder_B: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[13999]" dev="sockfs" ino=13999 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:55.761  5920  5920 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5920
11-04 14:15:55.762   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +277ms (total +311ms)
,11-04 14:15:55.814  5920  5920 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-04 14:15:55.876  5918  5918 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-04 14:15:55.891  5918  5918 D AndroidRuntime: CheckJNI is OFF
,11-04 14:15:55.911  5918  5918 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-04 14:15:55.938  5918  5918 I Radio-JNI: register_android_hardware_Radio DONE
,11-04 14:15:55.944  5920  5957 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -564135632
,11-04 14:15:55.947  5920  5957 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-04 14:15:55.947  5920  5957 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-04 14:15:55.947  5920  5957 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-04 14:15:55.947  5920  5957 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-04 14:15:55.947  5920  5957 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-04 14:15:55.947  5920  5957 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3b928a added. We now have 1 listener(s)
,11-04 14:15:55.949  5920  5957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-04 14:15:55.950  5920  5957 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-04 14:15:55.950  5920  5957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-04 14:15:55.950  5920  5957 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 7413
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 6
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 2
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 3
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 2
11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-04 14:15:55.952  5920  5957 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1484d56 added. We now have 1 listener(s)
11-04 14:15:55.952  5920  5957 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-04 14:15:55.953  5918  5918 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-04 14:15:55.955   928  2903 D WifiService: New client listening to asynchronous messages
,11-04 14:15:55.955  5920  5957 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-04 14:15:55.958  5920  5957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-04 14:15:55.958  5920  5957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-04 14:15:55.960   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-04 14:15:55.960   928   941 I ActivityManager: Killing 5920:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-04 14:15:55.998   928   939 D GraphicsStats: Buffer count: 2
,11-04 14:15:55.999   928  3527 I WindowState: WIN DEATH: Window{9d504b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-04 14:15:55.999   928  2903 D WifiService: Client connection lost with reason: 4
,11-04 14:15:56.063   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-04 14:15:56.063   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-04 14:15:56.064   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-04 14:15:56.064   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-04 14:15:56.064   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:56.064   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:56.064   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 14:15:56.064   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-04 14:15:56.065   928   951 I art     : Starting a blocking GC Explicit
,11-04 14:15:56.065   928   941 I ActivityManager:   Force finishing activity ActivityRecord{7adad7f u0 com.test.thalitest/.MainActivity t68}
,11-04 14:15:56.071   928  3085 W ActivityManager: Spurious death for ProcessRecord{c32572b 0:com.test.thalitest/u0a77}, curProc for 5920: null
,11-04 14:15:56.145   928   951 I art     : Explicit concurrent mark sweep GC freed 16432(1105KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 1.619ms total 80.325ms
,11-04 14:15:56.163   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-04 14:15:56.166  5918  5918 I art     : System.exit called, status: 0
11-04 14:15:56.166  5918  5918 I AndroidRuntime: VM exiting with result code 0.
,11-04 14:15:56.187   928   951 I ActivityManager: Start proc 5973:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-04 14:15:56.188   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-04 14:15:56.198   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-04 14:15:56.201  3577  3577 I Keyboard.Facilitator: resetDictionaries() : en_US
11-04 14:15:56.203  5785  5785 D BluetoothMapAppObserver: onReceive
11-04 14:15:56.203  5785  5785 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-04 14:15:56.210  3864  4028 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-04 14:15:56.233   928  2868 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-04 14:15:56.234  3577  5985 I Keyboard.Facilitator.DecoderInitializer: run()
,11-04 14:15:56.239  3328  5987 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-04 14:15:56.258  3679  3679 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-04 14:15:56.268   928  3527 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5920 uid 10077
,11-04 14:15:56.266  3527  3527 W Binder_7: type=1400 audit(0.0:141): avc: denied { ioctl } for path="socket:[28097]" dev="sockfs" ino=28097 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-04 14:15:56.266  3527  3527 W Binder_7: type=1400 audit(0.0:142): avc: denied { ioctl } for path="socket:[28097]" dev="sockfs" ino=28097 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-04 14:15:56.269  3577  3577 I Keyboard.Facilitator: onFinishInput()
,11-04 14:15:56.276  3510  3510 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-04 14:15:56.276  3510  3510 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-04 14:15:56.276   642   642 W kworker/1:2: type=1400 audit(0.0:143): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 14:15:56.283  3577  5985 I Decoder : createOrResetDecoder
,11-04 14:15:56.282   642   642 W kworker/1:2: type=1400 audit(0.0:144): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 14:15:56.286   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-04 14:15:56.309  3699  3832 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-04 14:15:56.312   642   642 W kworker/1:2: type=1400 audit(0.0:145): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-04 14:15:56.322   928  3722 I ActivityManager: Start proc 5992:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-04 14:15:56.323  3699  3832 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-04 14:15:56.323  3699  3832 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3699
11-04 14:15:56.323  3699  3832 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:56.323  3699  3832 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-04 14:15:56.326   928  3124 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-04 14:15:56.326   928  5998 E DropBoxManagerService: Can't write: system_app_crash
11-04 14:15:56.326   928  5998 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 14:15:56.326   928  5998 E DropBoxManagerService: 	... 5 more
,11-04 14:15:56.331  3699  3832 I Process : Sending signal. PID: 3699 SIG: 9
11-04 14:15:56.340  3954  6005 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-04 14:15:56.341  3954  6005 D AccountUtils: Clearing selected account for com.test.thalitest
11-04 14:15:56.347  3510  3510 I ConfigService: onCreate
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-04 14:15:56.351  3510  6009 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-04 14:15:56.351  3510  6009 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-04 14:15:56.353  3510  6009 W SQLiteOpenHelper: Opened config.db in read-only mode
11-04 14:15:56.354  3328  3352 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj3FDBD89E0) - 
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/ns.db'.
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:56.362  3510  3510 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-04 14:15:56.363  3510  3510 D AndroidRuntime: Shutting down VM
11-04 14:15:56.363  3577  5985 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-04 14:15:56.363  3510  3510 E AndroidRuntime: FATAL EXCEPTION: main
11-04 14:15:56.363  3510  3510 E AndroidRuntime: Process: com.google.process.gapps, PID: 3510
11-04 14:15:56.363  3510  3510 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.n.b(SourceFile:262)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.k.a(SourceFile:55)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at com.google.android.gms.gcm.nts.l.handleMessage(SourceFile:176)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-04 14:15:56.363  3510  3510 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-04 14:15:56.368  3510  3510 I Process : Sending signal. PID: 3510 SIG: 9
11-04 14:15:56.368   928  6011 E DropBoxManagerService: Can't write: system_app_crash
11-04 14:15:56.368   928  6011 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-04 14:15:56.368   928  6011 E DropBoxManagerService: 	... 5 more
11-04 14:15:56.383   383   478 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
