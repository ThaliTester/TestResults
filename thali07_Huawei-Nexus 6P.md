#### Test 94785159d624ac3_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-22 16:22:43.348  3902  4250 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-22 16:22:43.433  3902  4250 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-22 16:22:43.849  5632  5632 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-22 16:22:43.854  5632  5632 D AndroidRuntime: CheckJNI is OFF
11-22 16:22:43.883  5632  5632 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-22 16:22:43.917  5632  5632 I Radio-JNI: register_android_hardware_Radio DONE
11-22 16:22:43.932  5632  5632 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-22 16:22:43.935   927  3795 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-22 16:22:43.952  5632  5632 D AndroidRuntime: Shutting down VM
11-22 16:22:43.959  4006  4320 W SearchService: Abort, client detached.
11-22 16:22:43.971  4006  4006 I HotwordDetector: Closing mic
11-22 16:22:43.971  4006  4221 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8087924
11-22 16:22:43.987   927  3886 I ActivityManager: Start proc 5641:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-22 16:22:44.054   511  4247 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-22 16:22:44.057   511  4247 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-22 16:22:44.060   511  4247 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-22 16:22:44.060   511  4247 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-22 16:22:44.061   511  3032 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-22 16:22:44.063  4006  4235 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-22 16:22:44.064  4006  4243 I MicroRecognitionRnrImpl: Detection finished
11-22 16:22:44.084  5641  5641 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-22 16:22:44.103  5641  5641 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-22 16:22:44.117   927  3010 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
11-22 16:22:44.151  5641  5641 I LibraryLoader: Time to load native libraries: 44 ms (timestamps 84-128)
11-22 16:22:44.151  5641  5641 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 16:22:44.170  5641  5641 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6ad4b1d}
11-22 16:22:44.170  5641  5641 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-22 16:22:44.171  5641  5641 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-22 16:22:44.174  5641  5641 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-22 16:22:44.175  5641  5641 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-22 16:22:44.210  5641  5641 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-22 16:22:44.218  5641  5641 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 16:22:44.218  5641  5641 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-22 16:22:44.218  5641  5641 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-22 16:22:44.218  5641  5641 I Adreno  : Build Date                       : 12/06/15
11-22 16:22:44.218  5641  5641 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-22 16:22:44.218  5641  5641 I Adreno  : Local Branch                     : mybranch17112971
11-22 16:22:44.218  5641  5641 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-22 16:22:44.218  5641  5641 I Adreno  : Remote Branch                    : NONE
11-22 16:22:44.218  5641  5641 I Adreno  : Reconstruct Branch               : NOTHING
,11-22 16:22:44.264   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@618510f:true
,11-22 16:22:44.293   400   400 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[26161]" dev="sockfs" ino=26161 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 16:22:44.293   400   400 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26161]" dev="sockfs" ino=26161 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 16:22:44.305  5641  5641 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-22 16:22:44.316  5641  5641 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-22 16:22:44.343   403   403 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32025]" dev="sockfs" ino=32025 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 16:22:44.346  5641  5678 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 16:22:44.343   403   403 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32025]" dev="sockfs" ino=32025 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-22 16:22:44.346  3188  3188 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[26173]" dev="sockfs" ino=26173 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 16:22:44.351  5641  5665 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-22 16:22:44.346  3188  3188 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[26173]" dev="sockfs" ino=26173 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 16:22:44.374  5641  5678 I OpenGLRenderer: Initialized EGL, version 1.4
,11-22 16:22:44.446  3860  3860 W Binder_A: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31577]" dev="sockfs" ino=31577 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 16:22:44.446  3860  3860 W Binder_A: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31577]" dev="sockfs" ino=31577 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 16:22:44.451   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +481ms
,11-22 16:22:44.450  3892  3892 W Binder_D: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31576]" dev="sockfs" ino=31576 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 16:22:44.455  3700  3700 I Keyboard.Facilitator: onFinishInput()
11-22 16:22:44.450  3892  3892 W Binder_D: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31576]" dev="sockfs" ino=31576 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 16:22:44.506  5641  5641 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5641
,11-22 16:22:44.602  5641  5641 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-22 16:22:44.781  5641  5680 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -583272144
,11-22 16:22:44.785  5641  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-22 16:22:44.785  5641  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-22 16:22:44.785  5641  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-22 16:22:44.785  5641  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-22 16:22:44.785  5641  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-22 16:22:44.785  5641  5680 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b1cf38 added. We now have 1 listener(s)
,11-22 16:22:44.787  5641  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-22 16:22:44.788  5641  5680 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:22:44.788  5641  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 16:22:44.788  5641  5680 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-22 16:22:44.790  5641  5680 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f40ca77 added. We now have 1 listener(s)
,11-22 16:22:44.790  5641  5680 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 16:22:44.795   927  3011 D WifiService: New client listening to asynchronous messages
,11-22 16:22:44.795  5641  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 16:22:44.795  5641  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-22 16:22:44.796  5641  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-22 16:22:44.796  5641  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-22 16:22:44.796  5641  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-22 16:22:44.796  5641  5680 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-22 16:22:44.796  5641  5680 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-22 16:22:44.797  5641  5680 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-22 16:22:44.898  5641  5641 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-22 16:22:45.382  5641  5689 W jxcore-log: Initializing JXcore engine
,11-22 16:22:45.382  5641  5689 W jxcore-log: JXcore engine is ready
,11-22 16:22:45.403  5689  5689 W Thread-62: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11621 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-22 16:22:45.403  5689  5689 W Thread-62: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[16401]" dev="sockfs" ino=16401 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-22 16:22:45.403  5689  5689 W Thread-62: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-22 16:22:45.403  5689  5689 W Thread-62: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31546]" dev="sockfs" ino=31546 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-22 16:22:45.414  5641  5689 W jxcore-log: Starting JXcore engine
,11-22 16:22:45.465  5641  5689 W jxcore-log: Platform android
11-22 16:22:45.465  5641  5689 W jxcore-log: 
,11-22 16:22:45.465  5641  5689 W jxcore-log: Process ARCH arm
11-22 16:22:45.465  5641  5689 W jxcore-log: 
,11-22 16:22:45.649  5641  5689 I jxcore-log: JXcore Cordova bridge is ready!
11-22 16:22:45.649  5641  5689 I jxcore-log: 
,11-22 16:22:45.649  5641  5689 W jxcore-log: JXcore engine is started
,11-22 16:22:45.660  5641  5680 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-22 16:22:45.666  5641  5641 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-22 16:22:46.240   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 16:22:47.489   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:22:47.491  3620  3620 I ConfigService: onDestroy
,11-22 16:22:48.490   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:22:48.978   927  3892 I ActivityManager: Killing 5281:org.codeaurora.ims/1001 (adj 15): empty #17
,11-22 16:22:49.038   927  3892 I ActivityManager: Killing 5191:com.google.android.youtube/u0a75 (adj 15): empty #18
,11-22 16:22:49.491   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:22:50.493   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:22:51.494   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:22:52.495   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 16:22:54.056  4006  5690 W CronetSyncConnectionRcs: Upload content type not set.
,11-22 16:22:55.280  5641  5689 I jxcore-log: 2016-11-22 15:22:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-22 16:22:55.280  5641  5689 I jxcore-log: 
,11-22 16:22:55.282  5641  5689 I jxcore-log: 2016-11-22 15:22:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-22 16:22:55.282  5641  5689 I jxcore-log: 
,11-22 16:22:55.288  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-22 16:22:55.288  5641  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 16:22:55.288  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:22:55.288  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:22:55.288  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:22:55.288  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 16:22:55.288  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 16:22:55.288  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 16:22:55.288  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 16:22:55.288  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 16:22:55.289  5641  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 16:22:55.290  5641  5689 I jxcore-log: 2016-11-22 15:22:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-22 16:22:55.290  5641  5689 I jxcore-log: 
,11-22 16:22:55.291  5641  5689 I jxcore-log: 2016-11-22 15:22:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-22 16:22:55.291  5641  5689 I jxcore-log: 
,11-22 16:22:55.311   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 16:22:55.534  5641  5689 I jxcore-log: 2016-11-22 15:22:55 - DEBUG UnitTest_app: 'Running unit tests'
11-22 16:22:55.534  5641  5689 I jxcore-log: 
,11-22 16:22:55.534  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 16:22:55.534  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@86bb8a6 added. We now have 2 listener(s)
11-22 16:22:55.535  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 16:22:55.535  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 16:22:55.535  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 16:22:55.536  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 16:22:55.536  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8462e7 added. We now have 2 listener(s)
11-22 16:22:55.536  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 16:22:55.536  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 16:22:55.537  5641  5689 D executeNativeTests: Running unit tests
,11-22 16:22:55.572  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 16:22:55.572  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 added. We now have 3 listener(s)
,11-22 16:22:55.573  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-22 16:22:55.573  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-22 16:22:55.573  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 16:22:55.573  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:22:55.573  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad added. We now have 3 listener(s)
11-22 16:22:55.573  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:22:55.574  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 16:22:55.575  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 16:22:55.576  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 16:22:55.576  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 16:22:55.576  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 16:22:55.576  5641  5689 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-22 16:22:55.576  5641  5689 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 16:22:55.576  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-22 16:22:55.576  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 16:22:55.576  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 16:22:55.577  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 16:22:55.577  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:22:55.577  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:22:55.577  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:22:55.577  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:22:55.577  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:22:55.577  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:22:55.577  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 removed from the list
11-22 16:22:55.577  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:22:55.577  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad removed from the list
11-22 16:22:55.577  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:22:55.578  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.578  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.578  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.578  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.578  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.578  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 16:22:55.578  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:22:55.578  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:22:55.579  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:22:55.579  5641  5689 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-22 16:22:55.580  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:22:55.580  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:22:55.580  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:22:55.580  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:22:55.580  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:22:55.580  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:22:55.580  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:22:55.580  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:22:55.580  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:22:55.580  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.580  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.580  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.581  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.581  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.581  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:22:55.581  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:22:55.581  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:22:55.581  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-22 16:22:55.583  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 16:22:55.584  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:22:55.584  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:22:55.584  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:22:55.584  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:22:55.584  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:22:55.584  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:22:55.584  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:22:55.584  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:22:55.584  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:22:55.584  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.584  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.585  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.585  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.585  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.585  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:22:55.585  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:22:55.585  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:22:55.585  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:22:55.585  5641  5689 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 16:22:55.586  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:22:55.586  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 16:22:55.593  5641  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 16:22:55.593  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:22:55.593  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:22:55.593  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:22:55.593  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 16:22:55.593  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 16:22:55.593  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 16:22:55.593  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 16:22:55.593  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 16:22:55.594  5641  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 16:22:55.594  5641  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 16:22:55.594  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 16:22:55.594  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 16:22:55.594  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 16:22:55.595  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:22:55.595  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 16:22:55.598  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 16:22:55.599  5641  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 16:22:55.599  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 16:22:55.601  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:22:55.602  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.603  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 16:22:55.603  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 16:22:55.604  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 16:22:55.604  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 16:22:55.605  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:22:55.605  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-22 16:22:55.606  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-22 16:22:55.606  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.607  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 16:22:55.607  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 16:22:55.607  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 16:22:55.607  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 16:22:55.607  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.607  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:22:55.609  4689  4703 D BtGatt.GattService: registerClient() - UUID=3e755a8f-d5b4-4c8f-93ef-7721b8ef0c62
11-22 16:22:55.611  4689  4752 D BtGatt.GattService: onClientRegistered() - UUID=3e755a8f-d5b4-4c8f-93ef-7721b8ef0c62, clientIf=5
11-22 16:22:55.612  5641  5651 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 16:22:55.613  4689  4900 D BtGatt.GattService: start scan with filters
11-22 16:22:55.619  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 16:22:55.619  4689  4755 D BtGatt.ScanManager: handling starting scan
11-22 16:22:55.619  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.619  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 16:22:55.619  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.619  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 16:22:55.619  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 16:22:55.619  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:22:55.620  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 16:22:55.620  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.620  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 16:22:55.620  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 16:22:55.620  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:22:55.620  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 16:22:55.620  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.620  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.620  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:22:55.620  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:22:55.620  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 16:22:55.621  5641  5689 I io.jxcore.node.ConnectionHelper: start: OK
11-22 16:22:55.621  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:22:55.622  4689  4755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:22:55.625  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 16:22:55.625  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:22:55.625  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:22:55.625  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:22:55.625  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:22:55.630  4689  4752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 16:22:55.630  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:22:55.631  4689  4755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 16:22:55.637  4689  4752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 16:22:55.637  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:22:55.637  4689  4755 D BtGatt.ScanManager: Starting BLE batch scan
11-22 16:22:55.637  4689  4755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 16:22:55.649  4689  4752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 16:22:55.649  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:22:55.655  4689  4752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 16:22:55.655  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:22:56.126  5641  5641 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-22 16:22:56.127  5641  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 16:22:56.127  5641  5641 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 16:23:00.625  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 16:23:00.625  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:00.625  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 16:23:00.625  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:23:00.626  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 16:23:00.626  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 16:23:00.626  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-22 16:23:00.626  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-22 16:23:00.626  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:00.626  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-22 16:23:00.626  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 16:23:00.627  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.627  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.627  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.627  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 16:23:00.627  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:00.628  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:23:00.629  4689  4902 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 16:23:00.629  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 16:23:00.630  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:23:00.631  4689  4755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 16:23:00.631  4689  4705 D BtGatt.GattService: stopScan() - queue size =1
11-22 16:23:00.632  4689  4909 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 16:23:00.632  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 16:23:00.632  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.632  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 16:23:00.632  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:00.633  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.633  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.633  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.633  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 16:23:00.633  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:00.633  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.634  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.634  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 16:23:00.634  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 16:23:00.635  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 16:23:00.635  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.636  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.637  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:23:00.637  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:00.637  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:00.637  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:00.637  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:23:00.637  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:23:00.637  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:23:00.638  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 16:23:00.638  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:00.638  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:00.638  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:23:00.638  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
,11-22 16:23:00.638  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:00.638  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 16:23:00.638  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 16:23:00.638  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:23:00.639  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-22 16:23:00.639  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 16:23:00.639  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:23:00.639  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 16:23:00.640  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:23:00.641  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 16:23:00.641  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 16:23:00.641  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:23:00.642  4689  4689 D BtGatt.ScanManager: awakened up at time 96620
11-22 16:23:00.644  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 16:23:00.644  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:23:00.644  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 16:23:00.691  4689  4752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-22 16:23:00.691  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:00.691  4689  4752 D BtGatt.GattService: current time is 96669160618
11-22 16:23:00.691  4689  4752 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -86, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -84, 92, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 16:23:00.693  4689  4752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 16:23:00.694  4689  4752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-22 16:23:00.701  4689  4752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 16:23:00.701  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:00.701  4689  4755 D BtGatt.ScanManager: stopping BLe Batch
,11-22 16:23:00.709  4689  4752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-22 16:23:00.709  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:00.709  4689  4755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 16:23:00.716  4689  4752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 16:23:00.716  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:23:00.773  4885  4933 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-22 16:23:00.774  4885  4885 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-22 16:23:01.141  5641  5641 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 16:23:04.399   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 16:23:05.640  5641  5689 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-22 16:23:05.643  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-22 16:23:05.643  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 16:23:05.658  5641  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 16:23:05.658  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:05.658  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:05.658  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:23:05.658  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 16:23:05.658  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 16:23:05.658  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 16:23:05.658  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 16:23:05.658  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-22 16:23:05.664  5641  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 16:23:05.664  5641  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 16:23:05.664  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 16:23:05.664  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 16:23:05.664  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 16:23:05.664  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:23:05.664  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 16:23:05.667  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 16:23:05.667  5641  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 16:23:05.668  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 16:23:05.668  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:05.672  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:05.673  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:05.673  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 16:23:05.674  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 16:23:05.674  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 16:23:05.674  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 16:23:05.677  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.677  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 16:23:05.677  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 16:23:05.677  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 16:23:05.678  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 16:23:05.678  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.679  5641  5689 D BluetoothAdapter: STATE_ON
,11-22 16:23:05.681  4689  4900 D BtGatt.GattService: registerClient() - UUID=28668b1c-da22-4bbe-bd5f-04876ede9894
,11-22 16:23:05.682  4689  4752 D BtGatt.GattService: onClientRegistered() - UUID=28668b1c-da22-4bbe-bd5f-04876ede9894, clientIf=5
11-22 16:23:05.683  5641  5685 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 16:23:05.683  4689  4703 D BtGatt.GattService: start scan with filters
,11-22 16:23:05.686  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 16:23:05.686  4689  4755 D BtGatt.ScanManager: handling starting scan
11-22 16:23:05.686  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.686  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 16:23:05.686  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.686  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 16:23:05.686  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 16:23:05.686  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.686  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 16:23:05.686  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 16:23:05.686  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.686  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-22 16:23:05.686  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.687  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.687  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 16:23:05.687  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:05.691  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.691  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:23:05.691  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.691  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.691  5641  5689 I io.jxcore.node.ConnectionHelper: start: OK
11-22 16:23:05.691  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.693  4689  4752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 16:23:05.693  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:05.693  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:05.693  5641  5689 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 16:23:05.693  4689  4755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 16:23:05.693  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:05.693  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 16:23:05.693  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:23:05.694  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-22 16:23:05.694  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 16:23:05.694  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 16:23:05.695  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.695  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.695  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.696  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:23:05.696  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 16:23:05.696  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:05.696  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 16:23:05.696  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 16:23:05.696  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.696  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.696  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.696  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 16:23:05.696  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:05.697  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:23:05.698  4689  4909 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 16:23:05.698  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 16:23:05.699  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:23:05.699  4689  4705 D BtGatt.GattService: stopScan() - queue size =1
11-22 16:23:05.700  4689  4752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 16:23:05.700  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:05.700  4689  4755 D BtGatt.ScanManager: Starting BLE batch scan
11-22 16:23:05.700  4689  4755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 16:23:05.700  4689  4902 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.701  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 16:23:05.701  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 16:23:05.703  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:23:05.703  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.704  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.704  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:23:05.704  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.704  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.704  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:05.704  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:23:05.704  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:23:05.704  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:23:05.704  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:23:05.704  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:05.704  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 16:23:05.704  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:05.704  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:05.704  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.704  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:05.705  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 16:23:05.705  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:05.705  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 16:23:05.705  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 16:23:05.705  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.705  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.705  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal,.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.705  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:23:05.705  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.705  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.706  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.706  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.706  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.706  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.706  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.707  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.707  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.707  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.707  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:05.707  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:05.707  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:05.708  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:05.708  5641  5689 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-22 16:23:05.709  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:23:05.710  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 16:23:05.710  4689  4752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 16:23:05.710  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:05.716  4689  4752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-22 16:23:05.716  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:05.717  5641  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 16:23:05.717  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:05.717  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:05.717  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:23:05.717  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 16:23:05.717  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 16:23:05.717  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 16:23:05.717  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 16:23:05.717  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 16:23:05.718  4689  4755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 16:23:05.720  5641  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 16:23:05.720  5641  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 16:23:05.720  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 16:23:05.720  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 16:23:05.720  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 16:23:05.720  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:23:05.720  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 16:23:05.722  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 16:23:05.722  5641  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 16:23:05.722  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 16:23:05.723  4689  4752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 16:23:05.723  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:05.723  4689  4752 E BtGatt.ContextMap: Context not found for ID 5
,11-22 16:23:05.723  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 16:23:05.727  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 16:23:05.727  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.727  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-22 16:23:05.728  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 16:23:05.728  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 16:23:05.728  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 16:23:05.731  4689  4752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 16:23:05.731  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:23:05.731  4689  4755 D BtGatt.ScanManager: stopping BLe Batch
11-22 16:23:05.732  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.732  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 16:23:05.732  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 16:23:05.732  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 16:23:05.732  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-22 16:23:05.732  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:05.733  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:23:05.735  4689  4902 D BtGatt.GattService: registerClient() - UUID=c862adf7-e104-480f-98ae-b5f4fa7c10ff
11-22 16:23:05.736  4689  4752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 16:23:05.736  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:05.736  4689  4752 D BtGatt.GattService: onClientRegistered() - UUID=c862adf7-e104-480f-98ae-b5f4fa7c10ff, clientIf=5
11-22 16:23:05.736  4689  4755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 16:23:05.737  5641  5685 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 16:23:05.737  4689  4900 D BtGatt.GattService: start scan with filters
,11-22 16:23:05.740  4689  4752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 16:23:05.741  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:23:05.742  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-22 16:23:05.742  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.742  4689  4755 D BtGatt.ScanManager: handling starting scan
11-22 16:23:05.742  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 16:23:05.743  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.743  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 16:23:05.743  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 16:23:05.743  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.743  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-22 16:23:05.743  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 16:23:05.743  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.743  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.743  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.743  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.744  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 16:23:05.744  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.746  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.746  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:23:05.746  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.746  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:05.746  5641  5689 I io.jxcore.node.ConnectionHelper: start: OK
11-22 16:23:05.746  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 16:23:05.748  4689  4752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 16:23:05.748  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 16:23:05.748  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:05.748  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.748  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:23:05.748  4689  4755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 16:23:05.748  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-22 16:23:05.753  4689  4752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 16:23:05.753  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:05.753  4689  4755 D BtGatt.ScanManager: Starting BLE batch scan
11-22 16:23:05.753  4689  4755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 16:23:05.761  4689  4752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 16:23:05.761  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:23:05.766  4689  4752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 16:23:05.766  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:23:06.250  5641  5641 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-22 16:23:06.250  5641  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 16:23:06.250  5641  5641 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 16:23:07.416   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 16:23:07.423   927  3012 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-22 16:23:10.443   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 16:23:10.447   927  3012 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-22 16:23:10.747  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 16:23:10.747  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:10.747  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 16:23:10.747  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:23:10.748  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-22 16:23:10.748  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:10.748  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-22 16:23:10.748  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-22 16:23:10.748  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.749  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 16:23:10.749  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 16:23:10.749  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:10.749  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.750  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.750  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-22 16:23:10.750  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.752  5641  5689 D BluetoothAdapter: STATE_ON
,11-22 16:23:10.753  4689  4902 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 16:23:10.753  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 16:23:10.754  4689  4755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 16:23:10.756  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:23:10.757  4689  4909 D BtGatt.GattService: stopScan() - queue size =1
,11-22 16:23:10.759  4689  4705 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 16:23:10.760  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 16:23:10.760  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:10.760  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 16:23:10.760  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.760  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.761  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.761  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.761  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 16:23:10.761  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.761  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:10.762  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.762  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 16:23:10.762  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 16:23:10.763  4689  4689 D BtGatt.ScanManager: awakened up at time 106741
11-22 16:23:10.765   927  3886 I ActivityManager: Killing 5321:com.android.settings/1000 (adj 15): empty #17
,11-22 16:23:10.766  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:23:10.767  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.769  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.769  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-22 16:23:10.769  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.769  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:10.770  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:23:10.770  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:23:10.770  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-22 16:23:10.770  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:23:10.770  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 16:23:10.770  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 16:23:10.770  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:23:10.770  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-22 16:23:10.771  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:23:10.771  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:23:10.771  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 16:23:10.771  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:23:10.774  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 16:23:10.774  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:23:10.775  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-22 16:23:10.807  4689  4752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,11-22 16:23:10.807  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:10.807  4689  4752 D BtGatt.GattService: current time is 106785485682
11-22 16:23:10.808  4689  4752 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -86, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -84, 98, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -89, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -89, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -88, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-22 16:23:10.808  4689  4752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-22 16:23:10.808  4689  4752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-22 16:23:10.808  4689  4752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-22 16:23:10.809  4689  4752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-22 16:23:10.809  4689  4752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-22 16:23:10.814  4689  4752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 16:23:10.814  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:10.815  4689  4755 D BtGatt.ScanManager: stopping BLe Batch
11-22 16:23:10.820  4689  4752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 16:23:10.820  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:23:10.820  4689  4755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 16:23:10.825  4689  4752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 16:23:10.825  4689  4752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:23:11.272  5641  5641 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 16:23:11.272  5641  5641 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 16:23:11.272  5641  5641 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-22 16:23:15.771  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 16:23:15.771  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:15.771  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 16:23:15.772  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:15.772  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:23:15.772  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:23:15.772  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 16:23:15.773  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.773  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.773  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
,11-22 16:23:15.773  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:15.773  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 16:23:15.776  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.776  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.779  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.779  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.779  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.779  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:15.780  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:15.780  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.780  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.781  5641  5689 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-22 16:23:15.783  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:15.783  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:15.783  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:15.783  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:15.784  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.784  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.784  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.784  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.784  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:15.784  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.785  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.788  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.788  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.789  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.789  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 16:23:15.789  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:15.789  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.789  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.791  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-22 16:23:15.791  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:15.791  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:15.791  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 16:23:15.791  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:15.791  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.792  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.792  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.792  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.792  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:23:15.792  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.792  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.794  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.795  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.795  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.795  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:15.795  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 16:23:15.795  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.795  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
,11-22 16:23:15.796  5641  5689 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-22 16:23:15.796  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:15.797  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:15.797  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:15.797  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 16:23:15.797  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.797  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.797  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:23:15.797  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.797  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:15.798  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.798  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.800  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.800  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.800  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.800  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:15.800  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:15.800  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.800  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
,11-22 16:23:15.801  5641  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-22 16:23:15.802  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:15.802  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 16:23:15.802  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:15.802  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 16:23:15.802  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.802  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.802  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:23:15.803  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.803  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:15.803  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.803  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.805  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.805  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.805  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.805  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:15.805  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 16:23:15.805  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.805  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.806  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 16:23:15.807  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-22 16:23:15.807  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 16:23:15.807  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 16:23:15.807  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-22 16:23:15.807  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 16:23:15.807  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-22 16:23:15.807  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-22 16:23:15.807  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-22 16:23:15.808  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:15.808  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:15.808  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:15.808  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 16:23:15.808  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.808  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.808  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.808  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.809  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:15.809  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.809  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.811  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.812  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.812  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.813  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:15.814  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 16:23:15.814  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.814  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.817  5641  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 16:23:15.817  5641  5689 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 16:23:15.818  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-22 16:23:15.823  5641  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-22 16:23:15.824  5641  5689 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-22 16:23:15.825  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-22 16:23:15.825  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-22 16:23:15.825  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-22 16:23:15.825  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-22 16:23:15.826  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-22 16:23:15.826  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-22 16:23:15.826  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-22 16:23:15.826  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-22 16:23:15.826  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-22 16:23:15.826  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-22 16:23:15.826  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-22 16:23:15.826  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-22 16:23:15.826  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-22 16:23:15.827  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-22 16:23:15.827  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-22 16:23:15.827  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-22 16:23:15.827  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-22 16:23:15.828  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-22 16:23:15.828  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-22 16:23:15.828  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-22 16:23:15.828  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-22 16:23:15.828  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-22 16:23:15.828  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-22 16:23:15.829  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-22 16:23:15.829  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-22 16:23:15.829  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-22 16:23:15.829  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-22 16:23:15.829  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-22 16:23:15.829  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-22 16:23:15.829  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-22 16:23:15.830  5641  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-22 16:23:15.830  5641  5689 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 16:23:15.830  5641  5689 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-22 16:23:15.830  5641  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 16:23:15.830  5641  5689 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 16:23:15.831  5641  5689 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-22 16:23:15.831  5641  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 16:23:15.831  5641  5689 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-22 16:23:15.831  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-22 16:23:15.838  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-22 16:23:15.839  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-22 16:23:15.839  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-22 16:23:15.840  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-22 16:23:15.840  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,11-22 16:23:15.840  5641  5689 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-22 16:23:15.840  5641  5689 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-22 16:23:15.840  5641  5689 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-22 16:23:15.840  5641  5694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 126)
11-22 16:23:15.841  5641  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-22 16:23:15.841  5641  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-22 16:23:15.841  5641  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-22 16:23:15.841  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:15.841  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:15.841  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:15.842  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:15.842  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.842  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-22 16:23:15.843  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.843  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.843  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
,11-22 16:23:15.843  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:15.843  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.844  5641  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 126
11-22 16:23:15.844  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.844  5641  5694 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-22 16:23:15.844  5641  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-22 16:23:15.844  5641  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 126)
11-22 16:23:15.844  5641  5694 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 16:23:15.844  5641  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 126)
,11-22 16:23:15.843  4900  4900 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32060]" dev="sockfs" ino=32060 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 16:23:15.843  4900  4900 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32060]" dev="sockfs" ino=32060 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 16:23:15.845  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.845  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.845  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.845  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:15.845  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:15.845  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.846  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.846  5641  5689 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-22 16:23:15.847  5641  5694 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-22 16:23:15.847  5641  5694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-22 16:23:15.847  5641  5694 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 126)
,11-22 16:23:15.847  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:15.847  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:15.847  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:15.848  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:15.848  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.848  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.848  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.848  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
,11-22 16:23:15.848  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:15.848  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.848  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.850  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.850  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.850  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.850  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:15.850  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 16:23:15.850  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.850  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.851  5641  5689 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-22 16:23:15.851  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:15.851  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:15.851  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:15.852  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 16:23:15.852  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.852  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.853  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.853  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.854  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:15.854  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.854  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.856  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.856  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.856  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.856  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:15.856  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:15.856  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.856  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.857  5641  5689 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,11-22 16:23:15.857  5641  5689 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-22 16:23:15.857  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 16:23:15.857  5641  5689 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-22 16:23:15.857  5641  5689 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 16:23:15.857  5641  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-22 16:23:15.857  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-22 16:23:15.857  5641  5689 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-22 16:23:15.858  5641  5689 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-22 16:23:15.858  5641  5689 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-22 16:23:15.858  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 16:23:15.858  5641  5689 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,11-22 16:23:15.858  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:15.858  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:15.858  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:15.858  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:15.858  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.858  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.858  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:23:15.858  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.858  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:15.858  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.858  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.860  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.860  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:15.860  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:15.860  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:15.860  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:15.860  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:15.860  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.861  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:15.861  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:15.861  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:15.861  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:23:15.861  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:15.861  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:23:17.088   927  5410 D NetlinkSocketObserver: NeighborEvent{elapsedMs=113065, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 16:23:17.495   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-22 16:23:17.496   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-22 16:23:19.527   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 16:23:20.862  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:23:20.862  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.862  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:20.863  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:20.863  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:20.863  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 16:23:20.863  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:20.863  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:20.864  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 16:23:20.864  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:20.864  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:20.864  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.864  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
,11-22 16:23:20.864  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:20.865  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.865  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.869  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:20.870  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.870  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.870  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 16:23:20.870  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:20.870  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.871  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
,11-22 16:23:20.883  4909  4909 W Binder_5: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33113]" dev="sockfs" ino=33113 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 16:23:20.883  4909  4909 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33113]" dev="sockfs" ino=33113 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-22 16:23:20.874  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-22 16:23:20.875  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:23:20.875  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-22 16:23:20.881  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-22 16:23:20.882  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-22 16:23:20.883  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-22 16:23:20.883  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-22 16:23:20.883  5641  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-22 16:23:20.883  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-22 16:23:20.883  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-22 16:23:20.883  5641  5641 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-22 16:23:20.884  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:20.884  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-22 16:23:20.884  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-22 16:23:20.884  5641  5696 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 16:23:20.884  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-22 16:23:20.884  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 16:23:20.885  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 16:23:20.885  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-22 16:23:20.885  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
,11-22 16:23:20.885  5641  5641 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-22 16:23:20.885  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.885  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 16:23:20.885  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.886  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-22 16:23:20.886  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 16:23:20.886  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.887  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.887  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:23:20.887  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:20.887  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.887  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.887  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:23:20.888  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 16:23:20.888  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:23:20.888  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:23:20.888  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:20.888  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:20.888  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 16:23:20.888  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-22 16:23:20.888  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:20.888  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.888  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.888  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:23:20.888  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.889  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.889  5641  5696 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-22 16:23:20.889  5641  5696 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-22 16:23:20.889  5641  5696 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-22 16:23:20.890  5641  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-22 16:23:20.891  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.891  5641  5641 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:20.891  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.891  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.891  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:20.891  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:20.891  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.891  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.893  5641  5689 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-22 16:23:20.893  5641  5689 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-22 16:23:20.893  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-22 16:23:20.893  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 16:23:20.893  5641  5689 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-22 16:23:20.894  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:20.894  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:20.894  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:20.894  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 16:23:20.894  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:20.894  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:20.894  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.894  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.894  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:20.895  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.896  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.901  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.902  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:23:20.902  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.902  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:20.902  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:20.902  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.902  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.906  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:20.907  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 16:23:20.907  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:20.907  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:20.907  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:20.907  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:20.907  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.907  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.907  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:23:20.907  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.907  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.908  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.909  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.909  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.909  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:20.909  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:20.909  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.909  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.910  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:23:20.911  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:23:20.911  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:23:20.911  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:23:20.911  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:23:20.911  5641  5689 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da0e4c4 not in the list
11-22 16:23:20.911  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.911  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.911  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:20.911  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.911  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.913  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.913  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.913  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:23:20.913  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:23:20.913  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:23:20.913  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:20.913  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd4fad not in the list
11-22 16:23:20.914  5641  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-22 16:23:20.914  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 16:23:20.914  5641  5689 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-22 16:23:20.914  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-22 16:23:20.914  5641  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-22 16:23:20.914  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-22 16:23:20.916  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-22 16:23:20.916  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-22 16:23:20.916  5641  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-22 16:23:20.916  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 16:23:20.916  5641  5689 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-22 16:23:20.917  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-22 16:23:20.917  5641  5689 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-22 16:23:20.917  5641  5689 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-22 16:23:20.917  5641  5689 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-22 16:23:20.917  5641  5689 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-22 16:23:20.917  5641  5689 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-22 16:23:20.917  5641  5689 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-22 16:23:20.917  5641  5689 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-22 16:23:20.918  5641  5689 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-22 16:23:20.918  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:23:20.918  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b06b892 added. We now have 3 listener(s)
11-22 16:23:20.918  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:23:20.921  5641  5689 D BluetoothAdapter: enable(): BT is already enabled..!
11-22 16:23:20.921   927  3821 D WifiService: setWifiEnabled: true pid=5641, uid=10077
11-22 16:23:20.921   927  3821 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 16:23:20.973  4689  4872 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-22 16:23:20.973  4689  4898 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-22 16:23:21.389  5641  5641 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 16:23:22.497   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:23.498   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:24.124   927  3010 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-22 16:23:24.499   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:25.500   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:25.577   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-22 16:23:25.927  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 16:23:25.928  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1054263 added. We now have 4 listener(s)
,11-22 16:23:25.928  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 16:23:25.941  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:23:25.941  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1054263 removed from the list
,11-22 16:23:25.941  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:23:25.943  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 16:23:25.943  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5099e60 added. We now have 4 listener(s)
11-22 16:23:25.944  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 16:23:25.950  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:23:25.950  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5099e60 removed from the list
11-22 16:23:25.950  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:23:25.951  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:23:25.952  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@199df19 added. We now have 4 listener(s)
11-22 16:23:25.952  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 16:23:25.956   927  3795 D WifiService: setWifiEnabled: false pid=5641, uid=10077
,11-22 16:23:25.957   927  3795 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 16:23:25.965   927  3010 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-22 16:23:25.965   927  3010 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-22 16:23:25.967   927  3010 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 16:23:25.967   927  3010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 16:23:25.972  4689  4748 D BluetoothAdapterState: Current state: ON, message: 23
,11-22 16:23:25.972  4689  4748 D BluetoothAdapterProperties: Setting state to 13
11-22 16:23:25.972  4689  4748 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-22 16:23:25.973  4689  4748 D BluetoothAdapterProperties: onBluetoothDisable()
11-22 16:23:25.974  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:23:25.974  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 16:23:25.975  4689  4748 I BluetoothAdapterState: Entering PendingCommandState
,11-22 16:23:25.983  4689  4689 D BluetoothMapService: onReceive
,11-22 16:23:25.983  4689  4689 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 16:23:25.983  4689  4689 D BluetoothMapService: STATE_TURNING_OFF
11-22 16:23:25.984  4689  4689 D BluetoothMapService: MAP Service closeService in
11-22 16:23:25.984  4689  4689 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 16:23:25.984  4689  4689 D ObexServerSockets0: shutdown(block = true)
11-22 16:23:25.985  4689  4689 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-22 16:23:25.985  4689  4911 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-22 16:23:25.985  4689  4689 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 16:23:25.985  4689  4898 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 16:23:25.986  4689  4912 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 16:23:25.986   927  5411 D DhcpClient: Clearing IP address
11-22 16:23:25.986   506   921 D CommandListener: Clearing all IP addresses on wlan0
11-22 16:23:25.986  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:25.986  5641  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-22 16:23:25.986  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:25.986  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:25.986  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:23:25.986  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 16:23:25.986  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 16:23:25.986  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 16:23:25.986  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 16:23:25.986  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 16:23:25.987  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:25.987  5641  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-22 16:23:25.988  5641  5689 D io.jxcore.node.ConnectivityMonitor: start: OK
11-22 16:23:25.991  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:25.993  4689  4689 I BtOppRfcommListener: stopping Accept Thread
,11-22 16:23:25.994  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 16:23:25.994  4689  5341 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-22 16:23:25.995  4689  5341 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-22 16:23:25.995   506   921 D CommandListener: Setting iface cfg
11-22 16:23:26.003  3620  5463 V NativeCrypto: Read error: ssl=0x7f91113700: I/O error during system call, Connection timed out
11-22 16:23:26.005  3620  5463 V NativeCrypto: SSL shutdown failed: ssl=0x7f91113700: I/O error during system call, Broken pipe
11-22 16:23:26.006   927  5412 D DhcpClient: Receive thread stopped
11-22 16:23:26.007   927  3821 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-22 16:23:26.008   927  5409 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-22 16:23:26.011   927   940 I ActivityManager: Start proc 5700:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-22 16:23:26.011  4689  4752 D BluetoothAdapterProperties: Scan Mode:20
11-22 16:23:26.012  4689  4748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-22 16:23:26.013   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 16:23:26.013   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-22 16:23:26.013   927  5409 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-22 16:23:26.016   532   532 E Parcel  : Reading a NULL string not supported here.
,11-22 16:23:26.016  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 16:23:26.016  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:23:26.016  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:26.016  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:26.016  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:23:26.016  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 16:23:26.016  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 16:23:26.016  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 16:23:26.016  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 16:23:26.016  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 16:23:26.017  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:26.017  5641  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 16:23:26.018  4689  4689 D HeadsetService: Received stop request...Stopping profile...
,11-22 16:23:26.021   927  3012 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-22 16:23:26.023  3778  3924 W QCNEJ   : |CORE| network lost: 100
11-22 16:23:26.024  3778  3924 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-22 16:23:26.025   927   927 D RttService: SCAN_AVAILABLE : 1
,11-22 16:23:26.026   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:26.026  3166  3179 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:26.027  4689  4689 D A2dpService: Received stop request...Stopping profile...
11-22 16:23:26.029  3820  3838 D BluetoothHeadset: Proxy object disconnected
,11-22 16:23:26.028   927  3120 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-22 16:23:26.030  4689  4904 D A2dpStateMachine: Exit Disconnected: -1
11-22 16:23:26.031   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:26.031   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:26.032  4689  4689 D HidService: Received stop request...Stopping profile...
11-22 16:23:26.032   927   927 D BluetoothA2dp: Proxy object disconnected
11-22 16:23:26.032  4689  4689 D HidService: Stopping Bluetooth HidService
11-22 16:23:26.033   927  3010 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 16:23:26.034  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:26.034  4689  4689 V BluetoothAdapterState: isTurningOn()=false
,11-22 16:23:26.034  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:26.034  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:26.035  4689  4689 D HealthService: Received stop request...Stopping profile...
,11-22 16:23:26.039  4689  4689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 16:23:26.039  4689  4689 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 16:23:26.040  4689  4689 D PanService: Received stop request...Stopping profile...
11-22 16:23:26.040  4689  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:26.040  4689  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:26.041  4689  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:26.040  4689  4752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 16:23:26.042  4689  4752 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 16:23:26.042   927  3010 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 16:23:26.046  4689  4689 D BluetoothMapService: Received stop request...Stopping profile...
,11-22 16:23:26.046  4689  4689 D BluetoothMapService: stop()
11-22 16:23:26.047  4689  4689 D BluetoothMapAppObserver: deinitObservers()
,11-22 16:23:26.047  4689  4689 D BluetoothMapAppObserver: removeReceiver()
,11-22 16:23:26.047  3166  3166 D HeadsetProfile: Bluetooth service disconnected
,11-22 16:23:26.047  3166  3166 D BluetoothA2dp: Proxy object disconnected
11-22 16:23:26.048  3166  3166 D BluetoothInputDevice: Proxy object disconnected
11-22 16:23:26.048  3166  3166 D HidProfile: Bluetooth service disconnected
11-22 16:23:26.048  3166  3166 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 16:23:26.048  3166  3166 D PanProfile: Bluetooth service disconnected
11-22 16:23:26.049  3166  3166 D BluetoothMap: Proxy object disconnected
11-22 16:23:26.049  3166  3166 D MapProfile: Bluetooth service disconnected
11-22 16:23:26.049  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:26.049  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:26.049  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:26.049  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:26.049  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:26.049  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:26.049  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:26.049  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:26.051  4689  4689 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 16:23:26.051  4689  4752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-22 16:23:26.051  4689  4689 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 16:23:26.051  4689  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:26.051  4689  4752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 16:23:26.051  4689  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:26.051  4689  4872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 16:23:26.051  4689  4872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 16:23:26.051  4689  4872 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 16:23:26.051  4689  4872 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 16:23:26.051  4689  4689 D SapService: Received stop request...Stopping profile...
11-22 16:23:26.051  4689  4689 V SapService: stop()
11-22 16:23:26.052  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:26.052  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:26.052  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 16:23:26.052  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:26.053  4689  4689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-22 16:23:26.053  4689  4752 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 16:23:26.053  4689  4689 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 16:23:26.053  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:26.054  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:26.054  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:26.054  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:26.054  4689  4689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 16:23:26.054  4689  4689 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-22 16:23:26.056  4689  4689 D BluetoothMapService: MAP Service closeService in
11-22 16:23:26.056  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:26.056  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:26.056  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:26.056  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:26.056  4689  4689 D BluetoothMapService: cleanup()
11-22 16:23:26.056  4689  4689 D BluetoothMapService: MAP Service closeService in
11-22 16:23:26.057  4689  4689 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:26.057  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:26.057  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:26.057  4689  4689 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 16:23:26.057  4689  4748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-22 16:23:26.057  4689  4748 D BluetoothAdapterProperties: Setting state to 15
11-22 16:23:26.057  4689  4748 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-22 16:23:26.058  4689  4748 I BluetoothAdapterState: Entering BleOnState
11-22 16:23:26.064  5700  5700 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-22 16:23:26.065   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-22 16:23:26.065  3820  3846 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-22 16:23:26.066  3166  3178 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 16:23:26.066   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:26.066   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:26.066   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:26.067  3166  3179 D BluetoothPan: onBluetoothStateChange on: false
11-22 16:23:26.067   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 16:23:26.067  3166  3966 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 16:23:26.068  3166  3178 D BluetoothPbap: onBluetoothStateChange: up=false
,11-22 16:23:26.069  3166  3179 D BluetoothMap: onBluetoothStateChange: up=false
11-22 16:23:26.069  3166  3966 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:26.070  4689  4748 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 16:23:26.070  4689  4748 D BluetoothAdapterProperties: Setting state to 16
11-22 16:23:26.070  4689  4748 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,11-22 16:23:26.070  4689  4748 D BluetoothAdapterProperties: onBleDisable
11-22 16:23:26.071  4689  4748 I BluetoothAdapterState: Entering PendingCommandState
11-22 16:23:26.071  4689  4749 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 16:23:26.072  4689  4752 D BluetoothAdapterProperties: Scan Mode:20
,11-22 16:23:26.073  4689  4872 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-22 16:23:26.073  4689  4872 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:26.074  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:26.074  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:23:26.074  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:26.074  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:26.074  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:23:26.074  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 16:23:26.074  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 16:23:26.074  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 16:23:26.074  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 16:23:26.074  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 16:23:26.077  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:26.078  5700  5700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 16:23:26.085  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 16:23:26.086   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ce42e1:true
,11-22 16:23:26.092   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 16:23:26.092   506   921 D CommandListener: Clearing all IP addresses on wlan0
11-22 16:23:26.093   506   921 D TetherController: Setting IP forward enable = 0
11-22 16:23:26.094   927  3012 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-22 16:23:26.095   927  3012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 16:23:26.096   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-22 16:23:26.099   927  3010 D DhcpClient: doQuit
,11-22 16:23:26.099   927  3010 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-22 16:23:26.099  3487  3487 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-22 16:23:26.100   927  5411 D DhcpClient: onQuitting
,11-22 16:23:26.100  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:26.101  5299  5299 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2f469d9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-22 16:23:26.104  4006  4006 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-22 16:23:26.105  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:26.105  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:23:26.105  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:26.105  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:26.105  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 16:23:26.105  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 16:23:26.105  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 16:23:26.105  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 16:23:26.105  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 16:23:26.105  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 16:23:26.106  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:26.106  5641  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 16:23:26.106  5085  5109 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 16:23:26.106  5085  5109 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 16:23:26.106  5085  5109 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 16:23:26.107  5085  5109 E SarControlService: no key has been found,reset the power
11-22 16:23:26.107  5085  5122 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 16:23:26.107  5085  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-22 16:23:26.107  5085  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 16:23:26.107  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 16:23:26.107  5110  5110 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 16:23:26.109  5085  5122 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 16:23:26.109  5085  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 16:23:26.109  5085  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 16:23:26.110  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 16:23:26.110  5110  5110 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 16:23:26.113  5110  5124 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e0a25c7 HexData = [00000000ea03000000000000ffffffff]
11-22 16:23:26.113  5110  5124 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 16:23:26.113  5110  5124 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,11-22 16:23:26.113  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 16:23:26.113  5085  5095 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-22 16:23:26.117  5110  5124 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e0a25c7 HexData = [00000000eb03000000000000ffffffff]
,11-22 16:23:26.117  5110  5124 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 16:23:26.117  5110  5124 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-22 16:23:26.117  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 16:23:26.118  5085  5096 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 16:23:26.118  3487  3487 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-22 16:23:26.122  3487  3487 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-22 16:23:26.126  5700  5700 D LocalBluetoothProfileManager: Adding local MAP profile
,11-22 16:23:26.128  5700  5700 D BluetoothMap: Create BluetoothMap proxy object
,11-22 16:23:26.134  5700  5700 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-22 16:23:26.141  5700  5700 D DockEventReceiver: finishStartingService: stopping service
,11-22 16:23:26.144  5700  5700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 16:23:26.147   506   921 E Netd    : netlink response contains error (No such file or directory)
,11-22 16:23:26.148   506   921 D TetherController: Setting IP forward enable = 0
11-22 16:23:26.149  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 16:23:26.149   927  3012 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-22 16:23:26.150   927  3012 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 16:23:26.150  5700  5700 D DockEventReceiver: finishStartingService: stopping service
11-22 16:23:26.152   927  3892 I ActivityManager: Killing 5438:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-22 16:23:26.154  3487  3487 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 16:23:26.164  3487  3487 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 16:23:26.181  3902  3902 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-22 16:23:26.184  3902  3902 D SystemUpdateService: onCreate
,11-22 16:23:26.187  3902  3902 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 16:23:26.192  3902  5736 I SystemUpdateService: active receiver: enabled
,11-22 16:23:26.195  3902  3902 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 16:23:26.200  3902  5436 I iu.UploadsManager: num queued entries: 0
,11-22 16:23:26.200  3902  5436 I iu.UploadsManager: num updated entries: 0
11-22 16:23:26.201  3902  5436 I iu.SyncManager: NEXT; no task
,11-22 16:23:26.204  3902  3902 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 16:23:26.205  3902  3902 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 16:23:26.206  3902  5736 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 16:23:26.209  3902  5736 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-22 16:23:26.210  3902  5736 I SystemUpdateService: now status is 0 (complete)
11-22 16:23:26.210  3902  5736 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 16:23:26.210  3902  5736 I SystemUpdateService: file has been verified
,11-22 16:23:26.210  3902  5736 I SystemUpdateService: OTA package size = 21989297
,11-22 16:23:26.216  3902  5736 I SystemUpdateService: showing system update notification
,11-22 16:23:26.217   927  3451 I ActivityManager: Start proc 5738:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-22 16:23:26.230   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 16:23:26.232  3902  3902 D SystemUpdateService: onDestroy
,11-22 16:23:26.252  5738  5738 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-22 16:23:26.254  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 16:23:26.261  5738  5738 D SprintDMHelper: simOperator: 
,11-22 16:23:26.261  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 16:23:26.268   927  3010 D wifi    : In wifi stop Hal
,11-22 16:23:26.268   927  3010 D wifi    : halHandle = 0x7f8fe19e00, mVM = 0x7fac40d140, mCls = 0x100a02
11-22 16:23:26.268   927  3486 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-22 16:23:26.268   927  3486 D WifiHAL : Got a signal to exit!!!
11-22 16:23:26.268   927  3486 I WifiHAL : Exit wifi_event_loop
11-22 16:23:26.269   927  3010 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-22 16:23:26.269   927  3010 E WifiHAL : Event processing terminated
11-22 16:23:26.269   927  3010 D wifi    : In wifi cleaned up handler
11-22 16:23:26.269   927  3010 I WifiHAL : Internal cleanup completed
11-22 16:23:26.270  5047  5047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 16:23:26.270  4102  4256 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 16:23:26.271  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:26.274  5047  5750 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 16:23:26.277   927  3860 I ActivityManager: Killing 5299:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-22 16:23:26.294   927  3486 D wifi    : set interface wlan0 flags (DOWN)
,11-22 16:23:26.294   927  3010 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 16:23:26.311  4689  4752 I bt_hci  : shut_down
11-22 16:23:26.320   927  3860 I ActivityManager: Start proc 5751:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
11-22 16:23:26.324  4689  4756 D bt_hwcfg: hw_epilog_process
11-22 16:23:26.324  4689  4756 I bt_vendor: low_power_mode_cb
11-22 16:23:26.327  4689  4756 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-22 16:23:26.327  4689  4756 I bt_vendor: epilog_cb
11-22 16:23:26.327  4689  4756 I bt_hci  : epilog_finished_callback
11-22 16:23:26.330  4689  4752 I bt_hci_h4: hal_close
11-22 16:23:26.332  4689  4752 I bt_userial_vendor: device fd = 54 close
,11-22 16:23:26.354  5751  5751 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-22 16:23:26.361   927  3889 I ActivityManager: Killing 3935:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-22 16:23:26.437  4689  4749 D bt_stack_manager: event_shut_down_stack finished.
,11-22 16:23:26.437  4689  4748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-22 16:23:26.439  4689  4689 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 16:23:26.440  4689  4748 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-22 16:23:26.440  4689  4689 D BtGatt.GattService: Received stop request...Stopping profile...
11-22 16:23:26.440  4689  4689 D BtGatt.GattService: stop()
,11-22 16:23:26.440  4689  4689 D BtGatt.AdvertiseManager: advertise clients cleared
11-22 16:23:26.442  4689  4689 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:26.442  4689  4689 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:26.442  4689  4689 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 16:23:26.442  4689  4689 V BluetoothAdapterState: isBleTurningOff()=true
,11-22 16:23:26.442  4689  4748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 16:23:26.442  4689  4748 D BluetoothAdapterProperties: Setting state to 10
11-22 16:23:26.442  4689  4748 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-22 16:23:26.443  4689  4748 I BluetoothAdapterState: Entering OffState
11-22 16:23:26.444   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 16:23:26.452  4689  4689 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 16:23:26.453  4689  4689 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 16:23:26.453  4689  4689 I BluetoothServiceJni: cleanupNative: return from cleanup
11-22 16:23:26.453  4689  4749 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 16:23:26.459  4689  4689 I art     : System.exit called, status: 0
11-22 16:23:26.459  4689  4689 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 16:23:26.483   927  3188 I ActivityManager: Process com.android.bluetooth (pid 4689) has died
,11-22 16:23:26.496   927   944 D Tethering: InitialState.processMessage what=4
,11-22 16:23:26.500   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 16:23:26.500   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:27.501   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-22 16:23:30.990   927  3889 D WifiService: setWifiEnabled: true pid=5641, uid=10077
,11-22 16:23:30.990   927  3889 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 16:23:31.001   506   921 D SoftapController: Softap fwReload - Ok
,11-22 16:23:31.006   506   921 D CommandListener: Setting iface cfg
,11-22 16:23:31.006   506   921 D CommandListener: Trying to bring down wlan0
11-22 16:23:31.008   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-22 16:23:31.014   927  3010 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 16:23:31.605   927  3010 D wifi    : set interface wlan0 flags (UP)
11-22 16:23:31.609   927  3010 I WifiHAL : Initializing wifi
11-22 16:23:31.609   927  3010 I WifiHAL : Creating socket
,11-22 16:23:31.614   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-22 16:23:31.616   927  3010 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-22 16:23:31.616   927  3010 D wifi    : Did set static halHandle = 0x7f8fe19e00
11-22 16:23:31.616   927  3010 D wifi    : halHandle = 0x7f8fe19e00, mVM = 0x7fac40d140, mCls = 0x1019be
,11-22 16:23:31.617   927  3010 D wifi    : array field set
,11-22 16:23:31.617   927  3010 I WifiNative-HAL: interface[0] = wlan0
,11-22 16:23:31.621   927  5769 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547874774528
,11-22 16:23:31.622   927  5769 D wifi    : waitForHalEvents called, vm = 0x7fac40d140, obj = 0x1019be, env = 0x7f9155c5c0
,11-22 16:23:31.705  5770  5770 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 16:23:31.723   927  3010 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-22 16:23:31.731  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 16:23:31.789  5770  5770 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 16:23:31.797  5770  5770 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 16:23:31.797  5770  5770 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 16:23:31.810   927  3010 D WifiConfigStore: Loading config and enabling all networks 
,11-22 16:23:31.815  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 16:23:31.815  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:23:31.815  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:31.815  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:31.815  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:23:31.815  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 16:23:31.815  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 16:23:31.815  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 16:23:31.815  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 16:23:31.815  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 16:23:31.815  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:31.815  5641  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 16:23:31.826   927  3010 D WifiConfigStore: loaded 0 passpoint configs
,11-22 16:23:31.826   927  3010 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-22 16:23:31.826   927  3010 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 16:23:31.827   927  3010 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-22 16:23:31.827   927  3010 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-22 16:23:31.827   927  3010 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-22 16:23:31.828   927  3010 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-22 16:23:31.828   927  3010 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-22 16:23:31.828   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-22 16:23:31.828   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-22 16:23:31.828   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-22 16:23:31.828   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 16:23:31.828   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 16:23:31.831   927  3010 D WifiNative-HAL: Setting external_sim to 1
,11-22 16:23:31.831   927  3010 D wifi    : setting dfs flag to true, 0x7f914f7240
11-22 16:23:31.831  5047  5047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-22 16:23:31.831   927  3010 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 16:23:31.831   927  3010 D wifi    : setting scan oui 0x7f914f7240
11-22 16:23:31.831   927  3010 D WifiHAL : Sending mac address OUI
,11-22 16:23:31.834   927  3010 E native  : do suspend false
,11-22 16:23:31.841   927  3010 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-22 16:23:31.841   927   927 D RttService: SCAN_AVAILABLE : 3
11-22 16:23:31.841   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-22 16:23:31.842   927  3120 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-22 16:23:31.842   506   921 D CommandListener: Setting iface cfg
,11-22 16:23:31.846   927  3009 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-22 16:23:31.846   927  3009 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 16:23:31.855   927  3009 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 16:23:31.855   927  3009 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-22 16:23:31.859   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=127837 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-22 16:23:32.502   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:33.503   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:34.504   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:34.927  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 16:23:34.930  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 16:23:34.935  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 16:23:34.940  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 16:23:34.988   927  3010 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 16:23:34.990   927  3010 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-22 16:23:34.990   927  3010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 16:23:35.002   927  3010 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 16:23:35.039   927  3010 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 16:23:35.044  5770  5770 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 16:23:35.464  5770  5770 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 16:23:35.496  5770  5770 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 16:23:35.497  5770  5770 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 16:23:35.505   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:35.511   927  3010 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 16:23:35.511   927  3010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 16:23:35.511   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 16:23:35.527   927  3010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 16:23:35.544   506   921 D CommandListener: Setting iface cfg
,11-22 16:23:35.551   927  3010 D WifiStateMachine: Start Dhcp Watchdog 2
,11-22 16:23:35.557   927  5776 D DhcpClient: Receive thread started
,11-22 16:23:35.561   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 16:23:35.561   927  3010 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-22 16:23:35.562   927  3012 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-22 16:23:35.649   927  3010 E native  : do suspend false
,11-22 16:23:35.660   927  5775 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 16:23:35.672   927  5776 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-22 16:23:35.673   927  5775 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
11-22 16:23:35.675   927  5775 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 16:23:35.687   927  5776 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 16:23:35.687   927  5775 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 16:23:35.690   506   921 D CommandListener: Setting iface cfg
,11-22 16:23:35.693   927  3010 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 16:23:35.698   927  5775 D DhcpClient: Scheduling renewal in 86399s
,11-22 16:23:35.706   927  3010 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-22 16:23:35.707   927  3010 D WifiConfigStore: No blacklist allowed without epno enabled
11-22 16:23:35.708   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-22 16:23:35.710   927  3012 D ConnectivityService: Adding iface wlan0 to network 101
,11-22 16:23:35.721   927  3010 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 16:23:35.759   927  3012 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-22 16:23:35.759   927  3012 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-22 16:23:35.761   927  3012 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-22 16:23:35.764   927  3012 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-22 16:23:35.767   927  3012 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-22 16:23:35.775   927  3012 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 16:23:35.779   927  3012 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-22 16:23:35.780   927  3012 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-22 16:23:35.780   927  3012 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-22 16:23:35.780   927  3010 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 16:23:35.780   927  3012 D ConnectivityService:    accepting network in place of null
11-22 16:23:35.780   927  3010 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 16:23:35.780   927  3012 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 16:23:35.787   927  5774 D NetlinkSocketObserver: NeighborEvent{elapsedMs=131765, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 16:23:35.804   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 16:23:35.826   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 16:23:35.830   927  3012 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-22 16:23:35.830   927  3012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 16:23:35.830  3778  3924 W QCNEJ   : |CORE| network available: 101
11-22 16:23:35.831   927  3012 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-22 16:23:35.832  3778  3924 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 16:23:35.833  3778  3924 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 16:23:35.833  3778  3924 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-22 16:23:35.835   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-22 16:23:35.837  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-22 16:23:35.837  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:23:35.837  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:35.837  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:35.837  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:23:35.837  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 16:23:35.837  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 16:23:35.837  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 16:23:35.837  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 16:23:35.837  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 16:23:35.837  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:35.837  5641  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 16:23:35.849  5085  5109 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-22 16:23:35.849  5085  5109 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 16:23:35.849  5085  5109 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 16:23:35.849  5085  5109 E SarControlService: no key has been found,reset the power
11-22 16:23:35.849  5085  5122 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 16:23:35.849  5085  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 16:23:35.850  5085  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 16:23:35.850  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 16:23:35.850  5110  5110 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 16:23:35.852  4006  4006 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-22 16:23:35.852  5085  5122 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-22 16:23:35.852  5085  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 16:23:35.852  5085  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 16:23:35.853  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 16:23:35.853  5110  5110 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 16:23:35.853   927  5773 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-22 16:23:35.855  3902  3902 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 16:23:35.858  5110  5124 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e0a25c7 HexData = [00000000ec03000000000000ffffffff]
11-22 16:23:35.858  5110  5124 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 16:23:35.858  5110  5124 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-22 16:23:35.858  5110  5124 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e0a25c7 HexData = [00000000ed03000000000000ffffffff]
11-22 16:23:35.859  5110  5124 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 16:23:35.859  5110  5124 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-22 16:23:35.859  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 16:23:35.860  5085  5095 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 16:23:35.860  3902  3902 D SystemUpdateService: onCreate
11-22 16:23:35.861  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 16:23:35.861  5085  5096 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 16:23:35.866  3902  3902 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 16:23:35.877  3902  3902 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-22 16:23:35.883  3902  5436 I iu.UploadsManager: num queued entries: 0
,11-22 16:23:35.884  3902  5436 I iu.UploadsManager: num updated entries: 0
11-22 16:23:35.884  3902  5436 I iu.SyncManager: NEXT; no task
,11-22 16:23:35.885  3902  5786 I SystemUpdateService: active receiver: enabled
,11-22 16:23:35.889  3902  3902 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 16:23:35.890  3902  3902 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 16:23:35.892  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 16:23:35.896  5738  5738 D SprintDMHelper: simOperator: 
11-22 16:23:35.896  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 16:23:35.913   927  5773 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 15:23:35 GMT], X-Android-Received-Millis=[1479828215912], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479828215888]}
,11-22 16:23:35.914   927  3012 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-22 16:23:35.914   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-22 16:23:35.914   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-22 16:23:35.915   927  3012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-22 16:23:35.921  3902  5786 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 16:23:35.934  3902  5786 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-22 16:23:35.934  3902  5786 I SystemUpdateService: now status is 0 (complete)
11-22 16:23:35.934  3902  5786 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 16:23:35.934  3902  5786 I SystemUpdateService: file has been verified
11-22 16:23:35.934  3902  5786 I SystemUpdateService: OTA package size = 21989297
,11-22 16:23:35.940  3902  5786 I SystemUpdateService: showing system update notification
,11-22 16:23:35.948   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 16:23:35.950  3902  3902 D SystemUpdateService: onDestroy
,11-22 16:23:36.001   927  3452 D WifiService: setWifiEnabled: false pid=5641, uid=10077
,11-22 16:23:36.001   927  3452 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 16:23:36.002   927  3010 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-22 16:23:36.003   927  3010 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-22 16:23:36.003   927  3010 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 16:23:36.003   927  3010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 16:23:36.004  5047  5791 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 16:23:36.011   927  5775 D DhcpClient: Clearing IP address
,11-22 16:23:36.011   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-22 16:23:36.013   506   921 D CommandListener: Setting iface cfg
11-22 16:23:36.017  3620  5796 V NativeCrypto: Read error: ssl=0x7fa2589e00: I/O error during system call, Connection timed out
11-22 16:23:36.017  3620  5796 V NativeCrypto: SSL shutdown failed: ssl=0x7fa2589e00: I/O error during system call, Broken pipe
,11-22 16:23:36.024   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-22 16:23:36.024   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-22 16:23:36.025   532   532 E Parcel  : Reading a NULL string not supported here.
11-22 16:23:36.029   927   927 D RttService: SCAN_AVAILABLE : 1
11-22 16:23:36.030   927  3120 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-22 16:23:36.030   927  3012 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-22 16:23:36.032   927  3010 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-22 16:23:36.032  3778  3924 W QCNEJ   : |CORE| network lost: 101
11-22 16:23:36.033  3778  3924 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-22 16:23:36.033   927  5776 D DhcpClient: Receive thread stopped
,11-22 16:23:36.035   927  3010 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-22 16:23:36.054   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 16:23:36.074   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 16:23:36.074   506   921 D CommandListener: Clearing all IP addresses on wlan0
11-22 16:23:36.075   927  3012 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-22 16:23:36.075   927  3012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-22 16:23:36.076   927  3010 D DhcpClient: doQuit
11-22 16:23:36.076   927  3010 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-22 16:23:36.076   927  5775 D DhcpClient: onQuitting
11-22 16:23:36.077  5770  5770 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-22 16:23:36.080   927   944 D Tethering: MasterInitialState.processMessage what=3
,11-22 16:23:36.083  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:36.083  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:23:36.083  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:36.083  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:36.083  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 16:23:36.083  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 16:23:36.083  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 16:23:36.083  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 16:23:36.083  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 16:23:36.083  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 16:23:36.083  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:36.084  5641  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 16:23:36.085  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:36.086  5770  5770 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-22 16:23:36.089  4006  4006 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-22 16:23:36.091  5770  5770 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-22 16:23:36.093  3902  3902 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 16:23:36.094  5085  5109 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 16:23:36.094  5085  5109 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 16:23:36.094  5085  5109 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-22 16:23:36.094  5085  5109 E SarControlService: no key has been found,reset the power
11-22 16:23:36.095  5085  5122 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 16:23:36.095  5085  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 16:23:36.095  5085  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 16:23:36.095  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-22 16:23:36.096  5110  5110 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-22 16:23:36.097  5085  5122 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-22 16:23:36.097  5085  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 16:23:36.097  5085  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 16:23:36.098  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 16:23:36.098  5110  5110 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 16:23:36.100  3902  3902 D SystemUpdateService: onCreate
11-22 16:23:36.102  5110  5124 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e0a25c7 HexData = [00000000ee03000000000000ffffffff]
,11-22 16:23:36.102  5110  5124 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-22 16:23:36.102  5110  5124 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-22 16:23:36.102  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 16:23:36.103  5085  5096 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 16:23:36.105  5110  5124 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e0a25c7 HexData = [00000000ef03000000000000ffffffff]
11-22 16:23:36.105  5110  5124 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 16:23:36.105  5110  5124 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-22 16:23:36.106  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 16:23:36.106  5085  5095 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 16:23:36.107  3902  3902 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 16:23:36.111  3902  5806 I SystemUpdateService: active receiver: enabled
,11-22 16:23:36.117  3902  3902 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-22 16:23:36.122  3902  5436 I iu.UploadsManager: num queued entries: 0
,11-22 16:23:36.122  3902  5436 I iu.UploadsManager: num updated entries: 0
,11-22 16:23:36.123  3902  5436 I iu.SyncManager: NEXT; no task
,11-22 16:23:36.125  3902  3902 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-22 16:23:36.126  3902  3902 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-22 16:23:36.128  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-22 16:23:36.132  5738  5738 D SprintDMHelper: simOperator: 
11-22 16:23:36.132  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-22 16:23:36.137   506   921 E Netd    : netlink response contains error (No such file or directory)
,11-22 16:23:36.139  3902  5806 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-22 16:23:36.141  5770  5770 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-22 16:23:36.144  5047  5810 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-22 16:23:36.149  5770  5770 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-22 16:23:36.151  3902  5806 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-22 16:23:36.151  3902  5806 I SystemUpdateService: now status is 0 (complete)
11-22 16:23:36.151  3902  5806 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-22 16:23:36.155  3902  5806 I SystemUpdateService: file has been verified
,11-22 16:23:36.156  3902  5806 I SystemUpdateService: OTA package size = 21989297
,11-22 16:23:36.165  3902  5806 I SystemUpdateService: showing system update notification
,11-22 16:23:36.172   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-22 16:23:36.173  3902  3902 D SystemUpdateService: onDestroy
,11-22 16:23:36.253   927  3010 D wifi    : In wifi stop Hal
11-22 16:23:36.254   927  3010 D wifi    : halHandle = 0x7f8fe19e00, mVM = 0x7fac40d140, mCls = 0x1019be
11-22 16:23:36.254   927  5769 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-22 16:23:36.254   927  5769 D WifiHAL : Got a signal to exit!!!
,11-22 16:23:36.254   927  5769 I WifiHAL : Exit wifi_event_loop
11-22 16:23:36.255  5047  5047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 16:23:36.255   927  3010 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-22 16:23:36.255   927  3010 E WifiHAL : Event processing terminated
11-22 16:23:36.256   927  3010 D wifi    : In wifi cleaned up handler
11-22 16:23:36.256   927  3010 I WifiHAL : Internal cleanup completed
11-22 16:23:36.256  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:36.256  4102  4256 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 16:23:36.278   927  5769 D wifi    : set interface wlan0 flags (DOWN)
,11-22 16:23:36.279   927  3010 D WifiNative-HAL: HAL event thread stopped successfully
,11-22 16:23:36.486   927   944 D Tethering: InitialState.processMessage what=4
,11-22 16:23:36.493   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-22 16:23:36.506   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:36.831   927  3012 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-22 16:23:37.506   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-22 16:23:41.041   927   944 I ActivityManager: Start proc 5812:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 16:23:41.137  5812  5812 D AdapterServiceConfig: Adding HeadsetService
,11-22 16:23:41.137  5812  5812 D AdapterServiceConfig: Adding A2dpService
11-22 16:23:41.138  5812  5812 D AdapterServiceConfig: Adding HidService
11-22 16:23:41.138  5812  5812 D AdapterServiceConfig: Adding HealthService
11-22 16:23:41.138  5812  5812 D AdapterServiceConfig: Adding PanService
11-22 16:23:41.138  5812  5812 D AdapterServiceConfig: Adding GattService
11-22 16:23:41.138  5812  5812 D AdapterServiceConfig: Adding BluetoothMapService
11-22 16:23:41.139  5812  5812 D AdapterServiceConfig: Adding SapService
,11-22 16:23:41.149   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d92c5a:true
,11-22 16:23:41.149  5812  5812 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 16:23:41.153  5812  5812 I bt_bluedroid: init
,11-22 16:23:41.153  5812  5824 I BluetoothAdapterState: Entering OffState
,11-22 16:23:41.155  5812  5825 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-22 16:23:41.155  5812  5825 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 16:23:41.155  5812  5825 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-22 16:23:41.155  5812  5825 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-22 16:23:41.156  5812  5812 I bt_bluedroid: get_profile_interface socket
,11-22 16:23:41.158  5812  5828 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-22 16:23:41.158  5812  5812 I bt_bluedroid: get_profile_interface sdp
11-22 16:23:41.159  5812  5828 D BluetoothAdapterProperties: Name is: Nexus 6P
11-22 16:23:41.163  5812  5823 I bt_bluedroid: config_hci_snoop_log
,11-22 16:23:41.164   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 16:23:41.167  5812  5824 D BluetoothAdapterState: Current state: OFF, message: 0
,11-22 16:23:41.167  5812  5824 D BluetoothAdapterProperties: Setting state to 14
11-22 16:23:41.167  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-22 16:23:41.169  5812  5824 D BluetoothBondStateMachine: make
,11-22 16:23:41.170  5812  5829 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 16:23:41.173  5812  5824 I BluetoothAdapterState: Entering PendingCommandState
,11-22 16:23:41.173  5812  5812 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-22 16:23:41.176  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:41.176  5812  5812 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 16:23:41.177  5812  5812 D BtGatt.GattService: Received start request. Starting profile...
11-22 16:23:41.177  5812  5812 D BtGatt.GattService: start()
,11-22 16:23:41.177  5812  5812 I bt_bluedroid: get_profile_interface gatt
11-22 16:23:41.178  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:41.178  5812  5812 D BtGatt.AdvertiseManager: advertise manager created
,11-22 16:23:41.182  5812  5812 V BluetoothAdapterState: isTurningOff()=false
,11-22 16:23:41.182  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:41.182  5812  5812 V BluetoothAdapterState: isBleTurningOn()=true
11-22 16:23:41.182  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:41.182  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 16:23:41.183  5812  5824 I bt_bluedroid: bt_bluedroid
11-22 16:23:41.183  5812  5825 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-22 16:23:41.184  5812  5825 I bt_hci  : start_up
,11-22 16:23:41.188  5812  5825 I bt_vendor: alloc value 0xf3c2d871
,11-22 16:23:41.188  5812  5825 I bt_vendor: init
11-22 16:23:41.188  5812  5825 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 16:23:41.189  5812  5825 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 16:23:41.297  5812  5825 D bt_hci  : start_up starting async portion
11-22 16:23:41.297  5812  5832 I bt_hci  : event_finish_startup
11-22 16:23:41.297  5812  5832 I bt_hci_h4: hal_open
11-22 16:23:41.297  5812  5832 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 16:23:41.293  5833  5833 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 16:23:41.299  5812  5832 I bt_userial_vendor: device fd = 54 open
,11-22 16:23:41.313  5812  5832 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 16:23:41.315  5812  5832 D bt_hwcfg: Chipset BCM4358A3
11-22 16:23:41.316  5812  5832 D bt_hwcfg: Target name = [BCM4358A3]
,11-22 16:23:41.316  5812  5832 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 16:23:41.688  5812  5832 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 16:23:41.689  5812  5832 D bt_hwcfg: Settlement delay -- 100 ms
11-22 16:23:41.689  5812  5832 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 16:23:41.822  5812  5832 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 16:23:41.823  5812  5832 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-22 16:23:41.824  5812  5832 I bt_hwcfg: vendor lib fwcfg completed
,11-22 16:23:41.824  5812  5832 I bt_vendor: firmware callback
11-22 16:23:41.824  5812  5832 I bt_hci  : firmware_config_callback
,11-22 16:23:41.832  5812  5835 I bt_btu  : btu_task pending for preload complete event
11-22 16:23:41.832  5812  5835 I bt_btu_task: Bluetooth chip preload is complete
11-22 16:23:41.833  5812  5835 I bt_btu  : btu_task received preload complete event
,11-22 16:23:41.839  5812  5835 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 16:23:41.839  5812  5835 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-22 16:23:41.839  5812  5835 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-22 16:23:41.839  5812  5835 I         : BTE_InitTraceLevels -- TRC_AVDT
11-22 16:23:41.839  5812  5835 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 16:23:41.839  5812  5835 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 16:23:41.839  5812  5835 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-22 16:23:41.840  5812  5835 I         : BTE_InitTraceLevels -- TRC_BTM
11-22 16:23:41.840  5812  5835 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 16:23:41.840  5812  5835 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 16:23:41.840  5812  5835 I         : BTE_InitTraceLevels -- TRC_SDP
11-22 16:23:41.840  5812  5835 I         : BTE_InitTraceLevels -- TRC_GATT
,11-22 16:23:41.840  5812  5835 I         : BTE_InitTraceLevels -- TRC_SMP
11-22 16:23:41.840  5812  5835 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 16:23:41.840  5812  5835 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 16:23:41.921  5812  5835 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bab549
,11-22 16:23:41.921  5812  5835 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bab549 
,11-22 16:23:41.943  5812  5828 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 16:23:41.945  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 16:23:41.945  5812  5828 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 16:23:41.947  5812  5828 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 16:23:41.950  5812  5828 D BluetoothAdapterProperties: Scan Mode:20
11-22 16:23:41.950  5812  5828 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-22 16:23:41.950  5812  5828 D bt_hci  : do_postload posting postload work item
11-22 16:23:41.951  5812  5832 I bt_hci  : event_postload
11-22 16:23:41.951  5812  5832 I bt_vendor: sco_config_cb
11-22 16:23:41.951  5812  5832 I bt_hci  : sco_config_callback postload finished.
11-22 16:23:41.953  5812  5828 D bt_bte_conf: Device ID record 1 : primary
11-22 16:23:41.953  5812  5828 D bt_bte_conf:   vendorId            = 000f
11-22 16:23:41.953  5812  5828 D bt_bte_conf:   vendorIdSource      = 0001
11-22 16:23:41.953  5812  5828 D bt_bte_conf:   product             = 1200
11-22 16:23:41.953  5812  5828 D bt_bte_conf:   version             = 1436
11-22 16:23:41.953  5812  5828 D bt_bte_conf:   clientExecutableURL = 
11-22 16:23:41.953  5812  5828 D bt_bte_conf:   serviceDescription  = 
11-22 16:23:41.953  5812  5828 D bt_bte_conf:   documentationURL    = 
11-22 16:23:41.954  5812  5828 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 16:23:41.954  5812  5825 D bt_stack_manager: event_start_up_stack finished
11-22 16:23:41.955  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-22 16:23:41.955  5812  5824 D BluetoothAdapterProperties: Setting state to 15
11-22 16:23:41.956  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 16:23:41.959  5812  5824 I BluetoothAdapterState: Entering BleOnState
11-22 16:23:41.959  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 16:23:41.961  5812  5832 I bt_vendor: low_power_mode_cb
,11-22 16:23:41.961  5812  5824 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-22 16:23:41.962  5812  5824 D BluetoothAdapterProperties: Setting state to 11
11-22 16:23:41.962  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 16:23:41.968  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
,11-22 16:23:41.969  5812  5812 D HeadsetService: Received start request. Starting profile...
11-22 16:23:41.970  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:41.971  5812  5812 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-22 16:23:41.971  5812  5812 D HeadsetStateMachine: make
,11-22 16:23:41.980  5812  5812 D HeadsetStateMachine: max_hf_connections = 1
,11-22 16:23:41.980  5812  5812 I bt_bluedroid: get_profile_interface handsfree
11-22 16:23:41.980  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-22 16:23:41.981  5812  5828 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-22 16:23:41.980  5812  5824 I BluetoothAdapterState: Entering PendingCommandState
,11-22 16:23:41.985  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
,11-22 16:23:41.985  5812  5812 D A2dpService: Received start request. Starting profile...
,11-22 16:23:41.986  5812  5812 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 16:23:41.986  5812  5812 I bt_bluedroid: get_profile_interface avrcp
,11-22 16:23:41.991  5812  5812 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-22 16:23:41.992  5812  5812 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-22 16:23:41.992  5812  5812 D A2dpStateMachine: make
,11-22 16:23:41.993  5812  5812 I bt_bluedroid: get_profile_interface a2dp
11-22 16:23:41.994  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-22 16:23:41.994  5812  5843 D A2dpStateMachine: Enter Disconnected: -2
,11-22 16:23:41.996  5812  5812 I BluetoothHidServiceJni: classInitNative: succeeds
11-22 16:23:41.996  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:41.997  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 16:23:41.997  5700  5700 D BluetoothInputDevice: Proxy object connected
11-22 16:23:41.998  5812  5812 D HidService: Received start request. Starting profile...
11-22 16:23:41.998  5812  5812 I bt_bluedroid: get_profile_interface hidhost
,11-22 16:23:41.998  5812  5812 D HidService: setHidService(): set to: null
11-22 16:23:41.998  5700  5700 D HidProfile: Bluetooth service connected
11-22 16:23:41.998  5812  5828 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b8c56d
,11-22 16:23:41.999  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 16:23:41.999  5812  5812 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 16:23:41.999  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:42.000  5812  5812 D HealthService: Received start request. Starting profile...
,11-22 16:23:42.001  5812  5812 I bt_bluedroid: get_profile_interface health
,11-22 16:23:42.002  5812  5812 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-22 16:23:42.003  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
,11-22 16:23:42.004  5700  5700 D BluetoothPan: BluetoothPAN Proxy object connected
,11-22 16:23:42.004  5812  5812 D PanService: Received start request. Starting profile...
11-22 16:23:42.004  5812  5812 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 16:23:42.004  5812  5812 I bt_bluedroid: get_profile_interface pan
11-22 16:23:42.004  5700  5700 D PanProfile: Bluetooth service connected
11-22 16:23:42.004  5812  5828 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-22 16:23:42.007  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
,11-22 16:23:42.009  5812  5812 D BluetoothMapService: Received start request. Starting profile...
,11-22 16:23:42.009  5812  5812 D BluetoothMapService: start()
11-22 16:23:42.010  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-22 16:23:42.011  5700  5700 D BluetoothMap: Proxy object connected
11-22 16:23:42.011  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-22 16:23:42.011  5812  5812 D BluetoothMapAppObserver: createReceiver()
11-22 16:23:42.012  5700  5700 D MapProfile: Bluetooth service connected
11-22 16:23:42.012  5700  5700 D BluetoothMap: getConnectedDevices()
11-22 16:23:42.012  5812  5812 D BluetoothMapAppObserver: initObservers()
11-22 16:23:42.012  5812  5812 D BluetoothMapAppObserver: getEnabledAccountItems()
11-22 16:23:42.013  5700  5700 D BluetoothMap: Bluetooth is Not enabled
11-22 16:23:42.018  5812  5812 V SapService: SapBinder()
11-22 16:23:42.018  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
,11-22 16:23:42.019  5812  5812 D SapService: Received start request. Starting profile...
11-22 16:23:42.019  5812  5812 V SapService: start()
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:42.020  5812  5841 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:42.020  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:42.021  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:42.022  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:42.022  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:42.022  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 16:23:42.022  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:42.022  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 16:23:42.023  5812  5824 D BluetoothAdapterProperties: ScanMode =  20
11-22 16:23:42.023  5812  5824 D BluetoothAdapterProperties: State =  11
11-22 16:23:42.024  5812  5828 D BluetoothAdapterProperties: Scan Mode:21
11-22 16:23:42.024  5812  5824 D BluetoothAdapterProperties: Setting state to 12
11-22 16:23:42.024  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 16:23:42.024  5812  5828 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 16:23:42.024  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-22 16:23:42.025  5812  5824 I BluetoothAdapterState: Entering OnState
11-22 16:23:42.025  3820  3838 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:42.025  5700  5715 D BluetoothPan: onBluetoothStateChange on: true
11-22 16:23:42.026  3166  3178 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 16:23:42.028   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:42.028   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:42.028   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:42.028  5700  5712 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-22 16:23:42.028  3166  3966 D BluetoothPan: onBluetoothStateChange on: true
,11-22 16:23:42.028  3166  3166 D BluetoothA2dp: Proxy object connected
11-22 16:23:42.030  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:23:42.030  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:42.030  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:42.030  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 16:23:42.030  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 16:23:42.030  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 16:23:42.030  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 16:23:42.030  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 16:23:42.030  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 16:23:42.031   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 16:23:42.031   927   927 D BluetoothA2dp: Proxy object connected
11-22 16:23:42.031  5700  5715 D BluetoothPbap: onBluetoothStateChange: up=true
,11-22 16:23:42.032  3166  3166 D BluetoothPan: BluetoothPAN Proxy object connected
,11-22 16:23:42.032  3166  3166 D PanProfile: Bluetooth service connected
11-22 16:23:42.032  5641  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 16:23:42.033  3166  3179 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-22 16:23:42.035  3166  3166 D BluetoothInputDevice: Proxy object connected
,11-22 16:23:42.036  3166  3966 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 16:23:42.036  3166  3166 D HidProfile: Bluetooth service connected
11-22 16:23:42.037  3166  3179 D BluetoothMap: onBluetoothStateChange: up=true
11-22 16:23:42.037  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 16:23:42.037  5812  5812 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 16:23:42.038  3166  3166 D BluetoothMap: Proxy object connected
11-22 16:23:42.038  3166  3166 D MapProfile: Bluetooth service connected
11-22 16:23:42.038  5700  5712 D BluetoothMap: onBluetoothStateChange: up=true
11-22 16:23:42.039  3166  3166 D BluetoothMap: getConnectedDevices()
11-22 16:23:42.039  3166  3966 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:42.039  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 16:23:42.041  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-22 16:23:42.042   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
11-22 16:23:42.043  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:42.043  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 16:23:42.045  5700  5700 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-22 16:23:42.045  5812  5812 D ObexServerSockets: Succeed to create listening sockets 
11-22 16:23:42.045  5812  5812 D ObexServerSockets0: startAccept()
11-22 16:23:42.046  5812  5812 D ObexServerSockets0: prepareForNewConnect()
11-22 16:23:42.047  5812  5812 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 16:23:42.048  5812  5812 D BluetoothSdpJni: SDP Create record success - handle: 0
11-22 16:23:42.048  5812  5812 D BluetoothMapService: onReceive
11-22 16:23:42.048  5812  5850 D ObexServerSockets0: Accepting socket connection...
11-22 16:23:42.048  5812  5812 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 16:23:42.048  5700  5700 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-22 16:23:42.048  5812  5812 D BluetoothMapService: STATE_ON
,11-22 16:23:42.048  5812  5851 D ObexServerSockets0: Accepting socket connection...
,11-22 16:23:42.051  5812  5852 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 16:23:42.052  5812  5852 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-22 16:23:42.052  5812  5852 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 16:23:42.056  5700  5700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 16:23:42.058  5700  5700 D BluetoothA2dp: Proxy object connected
,11-22 16:23:42.062  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 16:23:42.062  5700  5700 D DockEventReceiver: finishStartingService: stopping service
,11-22 16:23:42.070  3166  3166 D BluetoothPbap: Proxy object connected
,11-22 16:23:42.070  5700  5700 D BluetoothPbap: Proxy object connected
11-22 16:23:42.070  3166  3166 D PbapServerProfile: Bluetooth service connected
11-22 16:23:42.070  5700  5700 D PbapServerProfile: Bluetooth service connected
,11-22 16:23:42.076  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 16:23:42.076  5812  5812 D ObexServerSockets0: prepareForNewConnect()
,11-22 16:23:42.078  5812  5856 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 16:23:42.090  5812  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 16:23:42.091  5812  5860 I BtOppRfcommListener: Accept thread started.
,11-22 16:23:42.126   927   927 D BluetoothHeadset: Proxy object connected
,11-22 16:23:42.127  3166  3178 D BluetoothHeadset: Proxy object connected
11-22 16:23:42.127  3166  3166 D HeadsetProfile: Bluetooth service connected
,11-22 16:23:42.127  3820  4038 D BluetoothHeadset: Proxy object connected
,11-22 16:23:42.128   927   927 D BluetoothHeadset: Proxy object connected
11-22 16:23:42.128   927   927 D BluetoothHeadset: Proxy object connected
11-22 16:23:42.128   927   944 D BluetoothHeadset: Proxy object connected
11-22 16:23:42.128   927   944 D BluetoothHeadset: Proxy object connected
11-22 16:23:42.128   927   944 D BluetoothHeadset: Proxy object connected
,11-22 16:23:42.139  3166  3966 D BluetoothHeadset: Proxy object connected
11-22 16:23:42.139  3166  3166 D HeadsetProfile: Bluetooth service connected
,11-22 16:23:42.153  5700  5712 D BluetoothHeadset: Proxy object connected
,11-22 16:23:42.154  5700  5700 D HeadsetProfile: Bluetooth service connected
,11-22 16:23:43.787   927  3012 D ConnectivityService: handlePromptUnvalidated 101
,11-22 16:23:44.456  3700  3882 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-22 16:23:44.456  3700  3882 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-22 16:23:44.484  3620  3620 I ConfigService: onCreate
,11-22 16:23:46.018  5812  5824 D BluetoothAdapterState: Current state: ON, message: 23
11-22 16:23:46.018  5812  5824 D BluetoothAdapterProperties: Setting state to 13
11-22 16:23:46.019  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-22 16:23:46.020  5812  5824 D BluetoothAdapterProperties: onBluetoothDisable()
11-22 16:23:46.021  5812  5824 I BluetoothAdapterState: Entering PendingCommandState
,11-22 16:23:46.026  5812  5812 D BluetoothMapService: onReceive
,11-22 16:23:46.027  5812  5812 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 16:23:46.027  5812  5812 D BluetoothMapService: STATE_TURNING_OFF
11-22 16:23:46.028  5812  5812 D BluetoothMapService: MAP Service closeService in
,11-22 16:23:46.028  5812  5812 D BluetoothMapMasInstance0: MAP Service shutdown
11-22 16:23:46.030  5812  5812 D ObexServerSockets0: shutdown(block = true)
11-22 16:23:46.031  5812  5850 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-22 16:23:46.034  5812  5812 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 16:23:46.035  5812  5851 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-22 16:23:46.035  5812  5837 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-22 16:23:46.036  5812  5812 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-22 16:23:46.036  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:46.037  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:23:46.037  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:23:46.037  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:23:46.037  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 16:23:46.037  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-22 16:23:46.037  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 16:23:46.037  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 16:23:46.037  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 16:23:46.037  5641  5641 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-22 16:23:46.037  5812  5828 D BluetoothAdapterProperties: Scan Mode:20
11-22 16:23:46.037  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-22 16:23:46.038  5641  5641 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-22 16:23:46.038  5641  5641 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-22 16:23:46.039  5700  5700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 16:23:46.042  5812  5812 I BtOppRfcommListener: stopping Accept Thread
11-22 16:23:46.043  5812  5860 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-22 16:23:46.044  5812  5860 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-22 16:23:46.045  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 16:23:46.049  5812  5812 D HeadsetService: Received stop request...Stopping profile...
,11-22 16:23:46.051   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:46.052  5700  5712 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:46.053  3166  3178 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:46.053  3820  3846 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:46.054   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:46.054   927   927 D BluetoothHeadset: Proxy object disconnected
11-22 16:23:46.054  5812  5812 D A2dpService: Received stop request...Stopping profile...
11-22 16:23:46.054  5812  5843 D A2dpStateMachine: Exit Disconnected: -1
,11-22 16:23:46.057   927   927 D BluetoothA2dp: Proxy object disconnected
,11-22 16:23:46.058  5812  5812 D HidService: Received stop request...Stopping profile...
,11-22 16:23:46.058  5812  5812 D HidService: Stopping Bluetooth HidService
11-22 16:23:46.058  3166  3166 D HeadsetProfile: Bluetooth service disconnected
11-22 16:23:46.059  3166  3166 D BluetoothA2dp: Proxy object disconnected
11-22 16:23:46.060  3166  3166 D BluetoothInputDevice: Proxy object disconnected
,11-22 16:23:46.060  3166  3166 D HidProfile: Bluetooth service disconnected
11-22 16:23:46.061  5812  5812 D HealthService: Received stop request...Stopping profile...
11-22 16:23:46.063  5812  5812 D PanService: Received stop request...Stopping profile...
11-22 16:23:46.064  3166  3166 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-22 16:23:46.064  3166  3166 D PanProfile: Bluetooth service disconnected
11-22 16:23:46.066  5812  5812 D BluetoothMapService: Received stop request...Stopping profile...
11-22 16:23:46.066  5812  5812 D BluetoothMapService: stop()
,11-22 16:23:46.066  5700  5700 D DockEventReceiver: finishStartingService: stopping service
,11-22 16:23:46.067  5812  5812 D BluetoothMapAppObserver: deinitObservers()
11-22 16:23:46.067  5812  5812 D BluetoothMapAppObserver: removeReceiver()
11-22 16:23:46.067  5700  5700 D HeadsetProfile: Bluetooth service disconnected
11-22 16:23:46.068  5700  5700 D BluetoothA2dp: Proxy object disconnected
11-22 16:23:46.068  5700  5700 D BluetoothInputDevice: Proxy object disconnected
11-22 16:23:46.068  5700  5700 D HidProfile: Bluetooth service disconnected
11-22 16:23:46.068  5700  5700 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-22 16:23:46.068  5700  5700 D PanProfile: Bluetooth service disconnected
,11-22 16:23:46.071  5700  5700 D BluetoothMap: Proxy object disconnected
11-22 16:23:46.071  5700  5700 D MapProfile: Bluetooth service disconnected
11-22 16:23:46.072  3166  3166 D BluetoothMap: Proxy object disconnected
11-22 16:23:46.072  5812  5812 D SapService: Received stop request...Stopping profile...
11-22 16:23:46.072  3166  3166 D MapProfile: Bluetooth service disconnected
11-22 16:23:46.072  5812  5812 V SapService: stop()
,11-22 16:23:46.073  5812  5812 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:46.074  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:46.074  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:46.074  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 16:23:46.075  5812  5812 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-22 16:23:46.075  5812  5812 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-22 16:23:46.076  5812  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:46.076  5812  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:46.076  5812  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:46.077  5812  5812 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:46.077  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:46.077  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:46.077  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:46.078  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-22 16:23:46.078  5812  5812 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:46.078  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:46.078  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:46.078  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 16:23:46.078  5812  5812 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-22 16:23:46.079  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-22 16:23:46.079  5812  5828 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-22 16:23:46.079  5812  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:46.078  5812  5812 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-22 16:23:46.079  5812  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-22 16:23:46.079  5812  5812 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:46.079  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:46.079  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:46.079  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:46.079  5812  5835 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 16:23:46.079  5812  5812 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-22 16:23:46.079  5812  5835 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 16:23:46.080  5812  5835 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-22 16:23:46.080  5812  5835 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-22 16:23:46.080  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 16:23:46.080  5812  5828 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-22 16:23:46.080  5812  5812 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-22 16:23:46.080  5812  5828 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-22 16:23:46.080  5812  5812 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:46.080  5812  5812 V BluetoothAdapterState: isTurningOn()=false
,11-22 16:23:46.080  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:46.080  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:46.081  5812  5812 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-22 16:23:46.081  5812  5812 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-22 16:23:46.082  5812  5812 D BluetoothMapService: MAP Service closeService in
,11-22 16:23:46.082  5812  5812 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:46.082  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:46.082  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:46.082  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:46.083  5812  5812 D BluetoothMapService: cleanup()
11-22 16:23:46.083  5812  5812 D BluetoothMapService: MAP Service closeService in
11-22 16:23:46.083  5812  5812 V BluetoothAdapterState: isTurningOff()=true
11-22 16:23:46.083  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:46.083  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:46.083  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:46.083  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-22 16:23:46.083  5812  5824 D BluetoothAdapterProperties: Setting state to 15
11-22 16:23:46.084  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-22 16:23:46.085  3820  3838 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:46.085  5812  5824 I BluetoothAdapterState: Entering BleOnState
11-22 16:23:46.086  3166  3166 D BluetoothPbap: Proxy object disconnected
11-22 16:23:46.086  3166  3166 D PbapServerProfile: Bluetooth service disconnected
11-22 16:23:46.086  5700  5712 D BluetoothPan: onBluetoothStateChange on: false
,11-22 16:23:46.086  3166  3178 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-22 16:23:46.088   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:46.088  5700  5712 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:46.089   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:46.089  5700  5715 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 16:23:46.090   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:46.090  5700  5712 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 16:23:46.091  3166  3179 D BluetoothPan: onBluetoothStateChange on: false
11-22 16:23:46.091   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
11-22 16:23:46.091  5700  5715 D BluetoothPbap: onBluetoothStateChange: up=false
,11-22 16:23:46.093  3166  3966 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-22 16:23:46.093  3166  3178 D BluetoothPbap: onBluetoothStateChange: up=false
11-22 16:23:46.094  3166  3179 D BluetoothMap: onBluetoothStateChange: up=false
11-22 16:23:46.094  5700  5712 D BluetoothMap: onBluetoothStateChange: up=false
,11-22 16:23:46.095  3166  3966 D BluetoothHeadset: onBluetoothStateChange: up=false
11-22 16:23:46.095  5812  5824 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-22 16:23:46.095  5812  5824 D BluetoothAdapterProperties: Setting state to 16
11-22 16:23:46.095  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-22 16:23:46.096  5700  5700 D BluetoothPbap: Proxy object disconnected
11-22 16:23:46.096  5812  5824 D BluetoothAdapterProperties: onBleDisable
11-22 16:23:46.096  5700  5700 D PbapServerProfile: Bluetooth service disconnected
11-22 16:23:46.096  5812  5824 I BluetoothAdapterState: Entering PendingCommandState
11-22 16:23:46.096  5812  5825 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-22 16:23:46.097  5812  5835 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-22 16:23:46.098  5812  5835 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-22 16:23:46.098  5812  5828 D BluetoothAdapterProperties: Scan Mode:20
11-22 16:23:46.099  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:46.100  5700  5700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-22 16:23:46.103  5641  5641 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-22 16:23:46.106  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 16:23:46.111  5700  5700 D DockEventReceiver: finishStartingService: stopping service
,11-22 16:23:46.308  5812  5828 I bt_hci  : shut_down
,11-22 16:23:46.318  5812  5832 D bt_hwcfg: hw_epilog_process
,11-22 16:23:46.318  5812  5832 I bt_vendor: low_power_mode_cb
,11-22 16:23:46.321  5812  5832 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-22 16:23:46.321  5812  5832 I bt_vendor: epilog_cb
11-22 16:23:46.321  5812  5832 I bt_hci  : epilog_finished_callback
,11-22 16:23:46.324  5812  5828 I bt_hci_h4: hal_close
,11-22 16:23:46.325  5812  5828 I bt_userial_vendor: device fd = 54 close
,11-22 16:23:46.436  5812  5825 D bt_stack_manager: event_shut_down_stack finished.
11-22 16:23:46.437  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-22 16:23:46.442  5812  5812 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-22 16:23:46.442  5812  5824 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-22 16:23:46.443  5812  5812 D BtGatt.GattService: Received stop request...Stopping profile...
,11-22 16:23:46.444  5812  5812 D BtGatt.GattService: stop()
11-22 16:23:46.444  5812  5812 D BtGatt.AdvertiseManager: advertise clients cleared
11-22 16:23:46.448  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:46.448  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:46.448  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 16:23:46.448  5812  5812 V BluetoothAdapterState: isBleTurningOff()=true
11-22 16:23:46.449  5812  5824 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-22 16:23:46.449  5812  5824 D BluetoothAdapterProperties: Setting state to 10
11-22 16:23:46.450  5812  5824 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-22 16:23:46.451  5812  5824 I BluetoothAdapterState: Entering OffState
,11-22 16:23:46.452   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-22 16:23:46.461  5812  5812 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-22 16:23:46.461  5812  5812 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-22 16:23:46.462  5812  5812 I BluetoothServiceJni: cleanupNative: return from cleanup
11-22 16:23:46.463  5812  5825 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-22 16:23:46.467  5812  5812 I art     : System.exit called, status: 0
,11-22 16:23:46.467  5812  5812 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-22 16:23:46.494   927  3452 I ActivityManager: Process com.android.bluetooth (pid 5812) has died
,11-22 16:23:47.507   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:48.508   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:49.509   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:49.515  3620  3620 I ConfigService: onDestroy
,11-22 16:23:50.510   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:51.016  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:23:51.016  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 16:23:51.022  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:23:51.022  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@199df19 removed from the list
,11-22 16:23:51.022  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:23:51.024  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 16:23:51.025  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7da408c added. We now have 4 listener(s)
11-22 16:23:51.025  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 16:23:51.028  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:23:51.028  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7da408c removed from the list
,11-22 16:23:51.028  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:23:51.030  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-22 16:23:51.030  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe053d5 added. We now have 4 listener(s)
11-22 16:23:51.030  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 16:23:51.511   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:23:52.512   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-22 16:23:56.041  5641  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 16:23:56.076   927   944 I ActivityManager: Start proc 5869:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-22 16:23:56.160  5869  5869 D AdapterServiceConfig: Adding HeadsetService
,11-22 16:23:56.160  5869  5869 D AdapterServiceConfig: Adding A2dpService
11-22 16:23:56.160  5869  5869 D AdapterServiceConfig: Adding HidService
11-22 16:23:56.160  5869  5869 D AdapterServiceConfig: Adding HealthService
11-22 16:23:56.161  5869  5869 D AdapterServiceConfig: Adding PanService
11-22 16:23:56.161  5869  5869 D AdapterServiceConfig: Adding GattService
11-22 16:23:56.161  5869  5869 D AdapterServiceConfig: Adding BluetoothMapService
11-22 16:23:56.161  5869  5869 D AdapterServiceConfig: Adding SapService
,11-22 16:23:56.171   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@906f6e6:true
,11-22 16:23:56.172  5869  5869 D BluetoothAdapterState: make() - Creating AdapterState
,11-22 16:23:56.174  5869  5869 I bt_bluedroid: init
,11-22 16:23:56.174  5869  5881 I BluetoothAdapterState: Entering OffState
,11-22 16:23:56.177  5869  5882 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-22 16:23:56.177  5869  5882 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-22 16:23:56.177  5869  5882 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-22 16:23:56.177  5869  5882 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-22 16:23:56.178  5869  5869 I bt_bluedroid: get_profile_interface socket
,11-22 16:23:56.180  5869  5885 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-22 16:23:56.180  5869  5869 I bt_bluedroid: get_profile_interface sdp
,11-22 16:23:56.181  5869  5885 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 16:23:56.185  5869  5880 I bt_bluedroid: config_hci_snoop_log
,11-22 16:23:56.187   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-22 16:23:56.191  5869  5881 D BluetoothAdapterState: Current state: OFF, message: 0
11-22 16:23:56.191  5869  5881 D BluetoothAdapterProperties: Setting state to 14
11-22 16:23:56.191  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-22 16:23:56.193  5869  5881 D BluetoothBondStateMachine: make
,11-22 16:23:56.195  5869  5886 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-22 16:23:56.198  5869  5881 I BluetoothAdapterState: Entering PendingCommandState
,11-22 16:23:56.199  5869  5869 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
11-22 16:23:56.201  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:56.201  5869  5869 D BtGatt.DebugUtils: handleDebugAction() action=null
11-22 16:23:56.202  5869  5869 D BtGatt.GattService: Received start request. Starting profile...
11-22 16:23:56.202  5869  5869 D BtGatt.GattService: start()
11-22 16:23:56.202  5869  5869 I bt_bluedroid: get_profile_interface gatt
,11-22 16:23:56.203  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:56.203  5869  5869 D BtGatt.AdvertiseManager: advertise manager created
,11-22 16:23:56.209  5869  5869 V BluetoothAdapterState: isTurningOff()=false
,11-22 16:23:56.209  5869  5869 V BluetoothAdapterState: isTurningOn()=false
11-22 16:23:56.209  5869  5869 V BluetoothAdapterState: isBleTurningOn()=true
11-22 16:23:56.209  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 16:23:56.209  5869  5881 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-22 16:23:56.210  5869  5881 I bt_bluedroid: bt_bluedroid
,11-22 16:23:56.211  5869  5882 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-22 16:23:56.211  5869  5882 I bt_hci  : start_up
,11-22 16:23:56.217  5869  5882 I bt_vendor: alloc value 0xf3c2d871
11-22 16:23:56.217  5869  5882 I bt_vendor: init
,11-22 16:23:56.217  5869  5882 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-22 16:23:56.217  5869  5882 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-22 16:23:56.326  5869  5882 D bt_hci  : start_up starting async portion
11-22 16:23:56.326  5869  5889 I bt_hci  : event_finish_startup
11-22 16:23:56.326  5869  5889 I bt_hci_h4: hal_open
11-22 16:23:56.326  5869  5889 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-22 16:23:56.328  5869  5889 I bt_userial_vendor: device fd = 54 open
,11-22 16:23:56.323  5890  5890 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 16:23:56.343  5869  5889 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 16:23:56.346  5869  5889 D bt_hwcfg: Chipset BCM4358A3
,11-22 16:23:56.346  5869  5889 D bt_hwcfg: Target name = [BCM4358A3]
11-22 16:23:56.347  5869  5889 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-22 16:23:56.857  5869  5889 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-22 16:23:56.858  5869  5889 D bt_hwcfg: Settlement delay -- 100 ms
11-22 16:23:56.858  5869  5889 I bt_hwcfg: Setting fw settlement delay to 100 
,11-22 16:23:56.993  5869  5889 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-22 16:23:56.994  5869  5889 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-22 16:23:56.995  5869  5889 I bt_hwcfg: vendor lib fwcfg completed
,11-22 16:23:56.996  5869  5889 I bt_vendor: firmware callback
,11-22 16:23:56.996  5869  5889 I bt_hci  : firmware_config_callback
,11-22 16:23:57.008  5869  5892 I bt_btu  : btu_task pending for preload complete event
,11-22 16:23:57.009  5869  5892 I bt_btu_task: Bluetooth chip preload is complete
,11-22 16:23:57.009  5869  5892 I bt_btu  : btu_task received preload complete event
,11-22 16:23:57.017  5869  5892 I         : BTE_InitTraceLevels -- TRC_HCI
,11-22 16:23:57.017  5869  5892 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-22 16:23:57.017  5869  5892 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-22 16:23:57.017  5869  5892 I         : BTE_InitTraceLevels -- TRC_AVDT
11-22 16:23:57.017  5869  5892 I         : BTE_InitTraceLevels -- TRC_AVRC
11-22 16:23:57.017  5869  5892 I         : BTE_InitTraceLevels -- TRC_A2D
11-22 16:23:57.018  5869  5892 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-22 16:23:57.018  5869  5892 I         : BTE_InitTraceLevels -- TRC_BTM
11-22 16:23:57.018  5869  5892 I         : BTE_InitTraceLevels -- TRC_GAP
11-22 16:23:57.018  5869  5892 I         : BTE_InitTraceLevels -- TRC_PAN
11-22 16:23:57.018  5869  5892 I         : BTE_InitTraceLevels -- TRC_SDP
,11-22 16:23:57.018  5869  5892 I         : BTE_InitTraceLevels -- TRC_GATT
11-22 16:23:57.018  5869  5892 I         : BTE_InitTraceLevels -- TRC_SMP
,11-22 16:23:57.019  5869  5892 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-22 16:23:57.019  5869  5892 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-22 16:23:57.118  5869  5892 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bab549
,11-22 16:23:57.118  5869  5892 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bab549 
,11-22 16:23:57.157  5869  5885 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-22 16:23:57.160  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-22 16:23:57.160  5869  5885 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-22 16:23:57.163  5869  5885 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-22 16:23:57.165  5869  5885 D BluetoothAdapterProperties: Scan Mode:20
,11-22 16:23:57.166  5869  5885 D BluetoothAdapterProperties: Discoverable Timeout:120
11-22 16:23:57.166  5869  5885 D bt_hci  : do_postload posting postload work item
11-22 16:23:57.166  5869  5889 I bt_hci  : event_postload
11-22 16:23:57.166  5869  5889 I bt_vendor: sco_config_cb
,11-22 16:23:57.166  5869  5889 I bt_hci  : sco_config_callback postload finished.
,11-22 16:23:57.170  5869  5885 D bt_bte_conf: Device ID record 1 : primary
,11-22 16:23:57.170  5869  5885 D bt_bte_conf:   vendorId            = 000f
11-22 16:23:57.170  5869  5885 D bt_bte_conf:   vendorIdSource      = 0001
11-22 16:23:57.170  5869  5885 D bt_bte_conf:   product             = 1200
11-22 16:23:57.170  5869  5885 D bt_bte_conf:   version             = 1436
11-22 16:23:57.170  5869  5885 D bt_bte_conf:   clientExecutableURL = 
,11-22 16:23:57.170  5869  5885 D bt_bte_conf:   serviceDescription  = 
11-22 16:23:57.170  5869  5885 D bt_bte_conf:   documentationURL    = 
11-22 16:23:57.170  5869  5885 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-22 16:23:57.170  5869  5882 D bt_stack_manager: event_start_up_stack finished
11-22 16:23:57.171  5869  5881 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-22 16:23:57.172  5869  5881 D BluetoothAdapterProperties: Setting state to 15
11-22 16:23:57.172  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-22 16:23:57.174  5869  5881 I BluetoothAdapterState: Entering BleOnState
11-22 16:23:57.175  5869  5889 I bt_vendor: low_power_mode_cb
,11-22 16:23:57.177  5869  5881 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-22 16:23:57.177  5869  5881 D BluetoothAdapterProperties: Setting state to 11
11-22 16:23:57.177  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-22 16:23:57.181  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
,11-22 16:23:57.183  5869  5869 D HeadsetService: Received start request. Starting profile...
11-22 16:23:57.186  5869  5869 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-22 16:23:57.187  5869  5869 D HeadsetStateMachine: make
,11-22 16:23:57.195  5869  5881 I BluetoothAdapterState: Entering PendingCommandState
,11-22 16:23:57.197  5869  5869 D HeadsetStateMachine: max_hf_connections = 1
,11-22 16:23:57.197  5869  5869 I bt_bluedroid: get_profile_interface handsfree
11-22 16:23:57.199  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-22 16:23:57.199  5869  5885 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-22 16:23:57.200  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:57.200  5869  5869 D A2dpService: Received start request. Starting profile...
11-22 16:23:57.201  5869  5869 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-22 16:23:57.201  5869  5869 I bt_bluedroid: get_profile_interface avrcp
,11-22 16:23:57.207  5869  5869 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-22 16:23:57.208  5869  5869 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-22 16:23:57.208  5869  5869 D A2dpStateMachine: make
,11-22 16:23:57.211  5869  5869 I bt_bluedroid: get_profile_interface a2dp
,11-22 16:23:57.211  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-22 16:23:57.215  5869  5900 D A2dpStateMachine: Enter Disconnected: -2
,11-22 16:23:57.216  5869  5869 I BluetoothHidServiceJni: classInitNative: succeeds
11-22 16:23:57.217  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:57.217  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 16:23:57.217  5869  5869 D HidService: Received start request. Starting profile...
,11-22 16:23:57.217  5869  5869 I bt_bluedroid: get_profile_interface hidhost
11-22 16:23:57.217  5869  5869 D HidService: setHidService(): set to: null
11-22 16:23:57.218  5869  5869 I BluetoothHealthServiceJni: classInitNative: succeeds
11-22 16:23:57.219  5869  5885 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b8c56d
11-22 16:23:57.219  5869  5885 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-22 16:23:57.219  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:57.220  5869  5869 D HealthService: Received start request. Starting profile...
,11-22 16:23:57.221  5869  5869 I bt_bluedroid: get_profile_interface health
,11-22 16:23:57.221  5869  5869 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-22 16:23:57.222  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
,11-22 16:23:57.222  5869  5869 D PanService: Received start request. Starting profile...
,11-22 16:23:57.223  5869  5869 D BluetoothPanServiceJni: initializeNative(L110): pan
11-22 16:23:57.223  5869  5869 I bt_bluedroid: get_profile_interface pan
11-22 16:23:57.223  5869  5885 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-22 16:23:57.226  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:23:57.226  5869  5869 D BluetoothMapService: Received start request. Starting profile...
11-22 16:23:57.226  5869  5869 D BluetoothMapService: start()
,11-22 16:23:57.228  5869  5869 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-22 16:23:57.229  5869  5869 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-22 16:23:57.229  5869  5869 D BluetoothMapAppObserver: createReceiver()
11-22 16:23:57.231  5869  5869 D BluetoothMapAppObserver: initObservers()
11-22 16:23:57.231  5869  5869 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-22 16:23:57.238  5869  5869 V SapService: SapBinder()
,11-22 16:23:57.238  5869  5869 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
,11-22 16:23:57.239  5869  5869 D SapService: Received start request. Starting profile...
11-22 16:23:57.239  5869  5869 V SapService: start()
,11-22 16:23:57.240  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
,11-22 16:23:57.241  5869  5898 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:57.241  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 16:23:57.242  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:57.242  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:57.242  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:57.243  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:57.243  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:57.243  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:57.243  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:57.243  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:57.243  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:57.243  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:57.244  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:57.244  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
,11-22 16:23:57.244  5869  5869 V BluetoothAdapterState: isTurningOff()=false
11-22 16:23:57.244  5869  5869 V BluetoothAdapterState: isTurningOn()=true
11-22 16:23:57.244  5869  5869 V BluetoothAdapterState: isBleTurningOn()=false
11-22 16:23:57.245  5869  5869 V BluetoothAdapterState: isBleTurningOff()=false
11-22 16:23:57.245  5869  5881 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-22 16:23:57.245  5869  5881 D BluetoothAdapterProperties: ScanMode =  20
,11-22 16:23:57.245  5869  5881 D BluetoothAdapterProperties: State =  11
,11-22 16:23:57.248  5869  5885 D BluetoothAdapterProperties: Scan Mode:21
11-22 16:23:57.248  5869  5881 D BluetoothAdapterProperties: Setting state to 12
11-22 16:23:57.248  5869  5881 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-22 16:23:57.248  5869  5885 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-22 16:23:57.248  5869  5881 I BluetoothAdapterState: Entering OnState
11-22 16:23:57.248  3820  4038 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:57.249  5700  5715 D BluetoothPan: onBluetoothStateChange on: true
,11-22 16:23:57.251  3166  3179 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-22 16:23:57.252  5700  5700 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 16:23:57.252  5700  5700 D PanProfile: Bluetooth service connected
11-22 16:23:57.253   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:57.253  5700  5715 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:57.253   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:57.253  5700  5712 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 16:23:57.254  3166  3166 D BluetoothA2dp: Proxy object connected
11-22 16:23:57.255   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
11-22 16:23:57.255  5700  5715 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-22 16:23:57.257  3166  3178 D BluetoothPan: onBluetoothStateChange on: true
,11-22 16:23:57.257  5869  5869 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-22 16:23:57.258  5869  5869 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-22 16:23:57.259   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
11-22 16:23:57.259  3166  3166 D BluetoothPan: BluetoothPAN Proxy object connected
11-22 16:23:57.259  3166  3166 D PanProfile: Bluetooth service connected
11-22 16:23:57.259  5869  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 16:23:57.259  5700  5712 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 16:23:57.259   927   927 D BluetoothA2dp: Proxy object connected
11-22 16:23:57.259  5700  5700 D BluetoothA2dp: Proxy object connected
11-22 16:23:57.261  5869  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-22 16:23:57.262  5869  5869 D ObexServerSockets: Succeed to create listening sockets 
11-22 16:23:57.262  5869  5869 D ObexServerSockets0: startAccept()
11-22 16:23:57.262  5869  5869 D ObexServerSockets0: prepareForNewConnect()
,11-22 16:23:57.262  3166  3966 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-22 16:23:57.263  3166  3178 D BluetoothPbap: onBluetoothStateChange: up=true
11-22 16:23:57.263  5869  5869 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-22 16:23:57.264  5869  5869 D BluetoothSdpJni: SDP Create record success - handle: 0
11-22 16:23:57.264  5869  5906 D ObexServerSockets0: Accepting socket connection...
11-22 16:23:57.265  3166  3166 D BluetoothInputDevice: Proxy object connected
11-22 16:23:57.265  5700  5700 D BluetoothInputDevice: Proxy object connected
11-22 16:23:57.265  3166  3166 D HidProfile: Bluetooth service connected
11-22 16:23:57.265  5700  5700 D HidProfile: Bluetooth service connected
11-22 16:23:57.264  5869  5907 D ObexServerSockets0: Accepting socket connection...
,11-22 16:23:57.266  3166  3966 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 16:23:57.269  5700  5712 D BluetoothMap: onBluetoothStateChange: up=true
,11-22 16:23:57.273  3166  3166 D BluetoothMap: Proxy object connected
11-22 16:23:57.273  3166  3166 D MapProfile: Bluetooth service connected
11-22 16:23:57.273  3166  3166 D BluetoothMap: getConnectedDevices()
,11-22 16:23:57.274  3166  3178 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-22 16:23:57.276  5700  5700 D BluetoothMap: Proxy object connected
11-22 16:23:57.276  5700  5700 D MapProfile: Bluetooth service connected
11-22 16:23:57.276  5700  5700 D BluetoothMap: getConnectedDevices()
11-22 16:23:57.277  5869  5869 D BluetoothMapService: onReceive
11-22 16:23:57.277  5869  5869 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-22 16:23:57.277  5869  5869 D BluetoothMapService: STATE_ON
11-22 16:23:57.277   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
,11-22 16:23:57.280  5869  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 16:23:57.282  5869  5910 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-22 16:23:57.282  5869  5910 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-22 16:23:57.283  5700  5700 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-22 16:23:57.293  3620  3620 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-22 16:23:57.295  5700  5700 D DockEventReceiver: finishStartingService: stopping service
,11-22 16:23:57.298  5700  5700 D BluetoothPbap: Proxy object connected
11-22 16:23:57.298  3166  3166 D BluetoothPbap: Proxy object connected
11-22 16:23:57.298  5700  5700 D PbapServerProfile: Bluetooth service connected
11-22 16:23:57.298  3166  3166 D PbapServerProfile: Bluetooth service connected
,11-22 16:23:57.304  5869  5869 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-22 16:23:57.304  5869  5869 D ObexServerSockets0: prepareForNewConnect()
11-22 16:23:57.307  5869  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 16:23:57.320  5869  5918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-22 16:23:57.322  5869  5918 I BtOppRfcommListener: Accept thread started.
,11-22 16:23:57.350   927   927 D BluetoothHeadset: Proxy object connected
,11-22 16:23:57.351  5700  5712 D BluetoothHeadset: Proxy object connected
11-22 16:23:57.351  3166  3179 D BluetoothHeadset: Proxy object connected
11-22 16:23:57.351  3166  3166 D HeadsetProfile: Bluetooth service connected
11-22 16:23:57.352  3820  3846 D BluetoothHeadset: Proxy object connected
11-22 16:23:57.352   927   927 D BluetoothHeadset: Proxy object connected
11-22 16:23:57.352   927   927 D BluetoothHeadset: Proxy object connected
11-22 16:23:57.353   927   944 D BluetoothHeadset: Proxy object connected
,11-22 16:23:57.353  5700  5700 D HeadsetProfile: Bluetooth service connected
11-22 16:23:57.354  5700  5905 D BluetoothHeadset: Proxy object connected
11-22 16:23:57.354   927   944 D BluetoothHeadset: Proxy object connected
,11-22 16:23:57.356  5700  5700 D HeadsetProfile: Bluetooth service connected
,11-22 16:23:57.356   927   944 D BluetoothHeadset: Proxy object connected
,11-22 16:23:57.375  3166  3178 D BluetoothHeadset: Proxy object connected
,11-22 16:23:57.375  3166  3166 D HeadsetProfile: Bluetooth service connected
,11-22 16:24:00.643  4102  4512 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-22 16:24:01.058  5641  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:24:01.058  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:24:01.058  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:24:01.058  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-22 16:24:01.058  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 16:24:01.058  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-22 16:24:01.058  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-22 16:24:01.058  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-22 16:24:01.058  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-22 16:24:01.064  5641  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-22 16:24:01.065  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:24:01.065  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe053d5 removed from the list
,11-22 16:24:01.065  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:24:01.067  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:01.068  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7ccc7ea added. We now have 4 listener(s)
11-22 16:24:01.068  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 16:24:01.072   927   938 D WifiService: setWifiEnabled: false pid=5641, uid=10077
,11-22 16:24:01.072   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 16:24:06.084  5641  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-22 16:24:06.086   927   938 D WifiService: setWifiEnabled: true pid=5641, uid=10077
,11-22 16:24:06.086   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-22 16:24:06.096   506   921 D SoftapController: Softap fwReload - Ok
,11-22 16:24:06.103   506   921 D CommandListener: Setting iface cfg
11-22 16:24:06.104   506   921 D CommandListener: Trying to bring down wlan0
11-22 16:24:06.105   506   921 D CommandListener: Clearing all IP addresses on wlan0
,11-22 16:24:06.111   927  3010 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-22 16:24:06.782   927  3010 D wifi    : set interface wlan0 flags (UP)
11-22 16:24:06.787   927  3010 I WifiHAL : Initializing wifi
11-22 16:24:06.787   927  3010 I WifiHAL : Creating socket
,11-22 16:24:06.791   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-22 16:24:06.792   927  3010 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-22 16:24:06.792   927  3010 D wifi    : Did set static halHandle = 0x7f8fe19e00
11-22 16:24:06.793   927  3010 D wifi    : halHandle = 0x7f8fe19e00, mVM = 0x7fac40d140, mCls = 0x1922
,11-22 16:24:06.793   927  3010 D wifi    : array field set
,11-22 16:24:06.793   927  3010 I WifiNative-HAL: interface[0] = wlan0
11-22 16:24:06.796   927  5923 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547874774528
11-22 16:24:06.796   927  5923 D wifi    : waitForHalEvents called, vm = 0x7fac40d140, obj = 0x1922, env = 0x7f9155d880
,11-22 16:24:06.852  5924  5924 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-22 16:24:06.897   927  3010 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-22 16:24:06.922  5924  5924 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 16:24:06.996  5924  5924 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-22 16:24:06.996  5924  5924 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-22 16:24:07.016   927  3010 D WifiConfigStore: Loading config and enabling all networks 
,11-22 16:24:07.040   927  3010 D WifiConfigStore: loaded 0 passpoint configs
11-22 16:24:07.041   927  3010 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-22 16:24:07.042   927  3010 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-22 16:24:07.042   927  3010 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-22 16:24:07.043   927  3010 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-22 16:24:07.043   927  3010 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
11-22 16:24:07.044   927  3010 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-22 16:24:07.044   927  3010 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-22 16:24:07.044   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-22 16:24:07.044   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-22 16:24:07.045   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-22 16:24:07.045   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-22 16:24:07.045   927  3010 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-22 16:24:07.048   927  3010 D WifiNative-HAL: Setting external_sim to 1
,11-22 16:24:07.049  5047  5047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-22 16:24:07.049   927  3010 D wifi    : setting dfs flag to true, 0x7f914f7920
11-22 16:24:07.049   927  3010 D WifiStateMachine: Setting OUI to DA-A1-19
11-22 16:24:07.050   927  3010 D wifi    : setting scan oui 0x7f914f7920
11-22 16:24:07.050   927  3010 D WifiHAL : Sending mac address OUI
,11-22 16:24:07.054   927  3010 E native  : do suspend false
,11-22 16:24:07.066   927  3010 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-22 16:24:07.066   927   927 D RttService: SCAN_AVAILABLE : 3
11-22 16:24:07.066   506   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-22 16:24:07.067   927  3120 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-22 16:24:07.067   506   921 D CommandListener: Setting iface cfg
,11-22 16:24:07.074   927  3009 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,11-22 16:24:07.074   927  3009 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-22 16:24:07.084   927  3009 D WifiNative-HAL: p2pGetDeviceAddress
,11-22 16:24:07.091   927  3009 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
11-22 16:24:07.091   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163069 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,11-22 16:24:07.513   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:08.515   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:09.516   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:10.153  5924  5924 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 16:24:10.158  5924  5924 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 16:24:10.163  5924  5924 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 16:24:10.167  5924  5924 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-22 16:24:10.238   927  3010 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-22 16:24:10.241   927  3010 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-22 16:24:10.241   927  3010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 16:24:10.256   927  3010 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-22 16:24:10.290   927  3010 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-22 16:24:10.296  5924  5924 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-22 16:24:10.517   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:10.721  5924  5924 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-22 16:24:10.755  5924  5924 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-22 16:24:10.757  5924  5924 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-22 16:24:10.766   927  3010 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 16:24:10.766   927  3010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-22 16:24:10.766   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-22 16:24:10.784   927  3010 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-22 16:24:10.796   506   921 D CommandListener: Setting iface cfg
,11-22 16:24:10.802   927  3010 D WifiStateMachine: Start Dhcp Watchdog 3
,11-22 16:24:10.807   927  5929 D DhcpClient: Receive thread started
,11-22 16:24:10.812   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:10.813   927  3010 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-22 16:24:10.813   927  3012 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-22 16:24:10.894   927  3010 E native  : do suspend false
,11-22 16:24:10.909   927  5928 D DhcpClient: Broadcasting DHCPDISCOVER
,11-22 16:24:10.923   927  5929 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-22 16:24:10.924   927  5928 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-22 16:24:10.926   927  5928 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-22 16:24:10.943   927  5929 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-22 16:24:10.944   927  5928 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-22 16:24:10.947   506   921 D CommandListener: Setting iface cfg
,11-22 16:24:10.952   927  3010 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-22 16:24:10.957   927  5928 D DhcpClient: Scheduling renewal in 86399s
,11-22 16:24:10.964   927  3010 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-22 16:24:10.965   927  3010 D WifiConfigStore: No blacklist allowed without epno enabled
11-22 16:24:10.966   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-22 16:24:10.968   927  3012 D ConnectivityService: Adding iface wlan0 to network 102
11-22 16:24:10.971   927  3010 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-22 16:24:11.014   927  3012 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-22 16:24:11.014   927  3012 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-22 16:24:11.017   927  3012 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-22 16:24:11.019   927  3012 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-22 16:24:11.021   927  3012 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-22 16:24:11.029   927  3012 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:11.046   927  3012 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-22 16:24:11.046   927  3012 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-22 16:24:11.046   927  3012 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-22 16:24:11.046   927  3012 D ConnectivityService:    accepting network in place of null
11-22 16:24:11.046   927  3010 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-22 16:24:11.047   927  3010 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-22 16:24:11.047   927  3012 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-22 16:24:11.062   927  5927 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167039, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-22 16:24:11.069   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 16:24:11.093   506   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-22 16:24:11.096   927  3012 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-22 16:24:11.096   927  3012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-22 16:24:11.096  3778  3924 W QCNEJ   : |CORE| network available: 102
,11-22 16:24:11.097   927  3012 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:11.099   927   944 D Tethering: MasterInitialState.processMessage what=3
11-22 16:24:11.100  3778  3924 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-22 16:24:11.102  3778  3924 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-22 16:24:11.102  3778  3924 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-22 16:24:11.103  5641  5689 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-22 16:24:11.103  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-22 16:24:11.103  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-22 16:24:11.103  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-22 16:24:11.103  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-22 16:24:11.103  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-22 16:24:11.103  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-22 16:24:11.103  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-22 16:24:11.103  5641  5689 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-22 16:24:11.107  5641  5689 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-22 16:24:11.107  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:24:11.107  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7ccc7ea removed from the list
11-22 16:24:11.107  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:24:11.111  5641  5689 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-22 16:24:11.111  5085  5109 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-22 16:24:11.112  5085  5109 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-22 16:24:11.112  5641  5689 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-22 16:24:11.112  5085  5109 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-22 16:24:11.112  5085  5109 E SarControlService: no key has been found,reset the power
,11-22 16:24:11.113  4006  4006 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-22 16:24:11.114  5641  5689 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f584fdb Bundle[{}]
11-22 16:24:11.115  5641  5689 I io.jxcore.node.LifeCycleMonitor: start: OK
11-22 16:24:11.115  5641  5689 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-22 16:24:11.115  5641  5689 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-22 16:24:11.116  3902  3902 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-22 16:24:11.116  5641  5689 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-22 16:24:11.116  5641  5689 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-22 16:24:11.117  5641  5689 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-22 16:24:11.119  3902  3902 D SystemUpdateService: onCreate
11-22 16:24:11.120  5085  5122 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-22 16:24:11.120  5085  5122 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-22 16:24:11.120  5085  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-22 16:24:11.121  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 16:24:11.121  5110  5110 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-22 16:24:11.122  5085  5122 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-22 16:24:11.123  5085  5122 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-22 16:24:11.123  5085  5122 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-22 16:24:11.123  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-22 16:24:11.123  5110  5110 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-22 16:24:11.124  5641  5689 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-22 16:24:11.124  5641  5689 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-22 16:24:11.124  5641  5689 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-22 16:24:11.126  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 16:24:11.126  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@169adb added. We now have 3 listener(s)
,11-22 16:24:11.126  3902  3902 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-22 16:24:11.127  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.127  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.127  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 16:24:11.127  5110  5124 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e0a25c7 HexData = [00000000f003000000000000ffffffff]
11-22 16:24:11.128  5110  5124 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 16:24:11.128  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.128  5110  5124 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-22 16:24:11.128  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d30d978 added. We now have 4 listener(s)
11-22 16:24:11.128  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:24:11.128  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 16:24:11.128  5085  5096 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-22 16:24:11.128  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 16:24:11.129  5110  5124 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@e0a25c7 HexData = [00000000f103000000000000ffffffff]
11-22 16:24:11.129  5110  5124 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-22 16:24:11.129  5110  5124 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-22 16:24:11.130  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 16:24:11.130  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adf5851 added. We now have 4 listener(s)
11-22 16:24:11.131  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.131  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.131  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 16:24:11.131  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.131  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da778b6 added. We now have 5 listener(s)
11-22 16:24:11.131  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:24:11.131  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:24:11.132  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:24:11.132  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:24:11.132  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:24:11.132  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:24:11.132  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.132  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@169adb removed from the list
11-22 16:24:11.132  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 ,16:24:11.132  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d30d978 removed from the list
11-22 16:24:11.132  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:24:11.133  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.133  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.133  5110  5110 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-22 16:24:11.133  5085  5095 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-22 16:24:11.134  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.134  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.134  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:24:11.134  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:24:11.134  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:24:11.134  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.134  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d30d978 not in the list
11-22 16:24:11.134  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.134  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.136  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.136  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.136  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.136  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:24:11.136  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-22 16:24:11.136  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.136  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da778b6 removed from the list
11-22 16:24:11.136  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:24:11.136  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:24:11.136  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.136  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adf5851 removed from the list
11-22 16:24:11.136  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 16:24:11.137  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9da09b7 added. We now have 3 listener(s)
11-22 16:24:11.138  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.138  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.138  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 16:24:11.138  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.138  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b561524 added. We now have 4 listener(s)
11-22 16:24:11.138  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:24:11.138  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 16:24:11.140  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 16:24:11.140  3902  5940 I SystemUpdateService: active receiver: enabled
11-22 16:24:11.140  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0288d added. We now have 4 listener(s)
11-22 16:24:11.141  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.141  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.141  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 16:24:11.141  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.142  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@baa6a42 added. We now have 5 listener(s)
11-22 16:24:11.142  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:24:11.142  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 16:24:11.142  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 16:24:11.142  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 16:24:11.142  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:24:11.142  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 16:24:11.144  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-22 16:24:11.147  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-22 16:24:11.147  5641  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 16:24:11.147  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 16:24:11.149  3902  3902 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-22 16:24:11.150  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:24:11.150  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 16:24:11.151  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 16:24:11.151  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 16:24:11.151  3902  5436 I iu.UploadsManager: num queued entries: 0
11-22 16:24:11.151  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 16:24:11.151  3902  5436 I iu.UploadsManager: num updated entries: 0
11-22 16:24:11.153   927  5926 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-22 16:24:11.153  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.153  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-22 16:24:11.154  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 16:24:11.154  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 16:24:11.154  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 16:24:11.154  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.154  5641  5689 D BluetoothAdapter: STATE_ON
,11-22 16:24:11.157  5869  5879 D BtGatt.GattService: registerClient() - UUID=a5d426ef-da2d-4133-b26c-e404e2a1e7bf
11-22 16:24:11.157  5869  5885 D BtGatt.GattService: onClientRegistered() - UUID=a5d426ef-da2d-4133-b26c-e404e2a1e7bf, clientIf=5
,11-22 16:24:11.158  5641  5685 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 16:24:11.159  5869  5909 D BtGatt.GattService: start scan with filters
,11-22 16:24:11.162  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 16:24:11.162  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.162  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-22 16:24:11.162  5869  5888 D BtGatt.ScanManager: handling starting scan
11-22 16:24:11.162  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.162  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 16:24:11.163  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 16:24:11.163  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.163  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 16:24:11.163  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 16:24:11.163  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.163  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.163  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.163  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-22 16:24:11.163  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 16:24:11.164  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.164  5869  5888 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b6b418c
11-22 16:24:11.165  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.166  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:24:11.166  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.166  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.166  5641  5689 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-22 16:24:11.166  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 16:24:11.166  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-22 16:24:11.166  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:24:11.166  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.166  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:24:11.166  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:24:11.166  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-22 16:24:11.170  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-22 16:24:11.170  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-22 16:24:11.170  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.170  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 16:24:11.170  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:24:11.170  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.170  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 16:24:11.170  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 16:24:11.171  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.171  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:24:11.171  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.171  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 16:24:11.171  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.171  5869  5885 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 16:24:11.171  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:24:11.171  5641  5689 D BluetoothAdapter: STATE_ON
,11-22 16:24:11.172  5869  5909 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 16:24:11.172  5869  5888 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 16:24:11.172  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 16:24:11.172  3902  3902 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-22 16:24:11.173  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:24:11.173  5869  5880 D BtGatt.GattService: stopScan() - queue size =1
11-22 16:24:11.174  5869  5908 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 16:24:11.174  3902  3902 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-22 16:24:11.174  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 16:24:11.174  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.174  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-22 16:24:11.174  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.175  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.175  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.175  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.175  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 16:24:11.175  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.175  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.175  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.175  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 16:24:11.175  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-22 16:24:11.176  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 16:24:11.176  5738  5738 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-22 16:24:11.177  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.177  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 16:24:11.177  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.177  5869  5888 D BtGatt.ScanManager: Starting BLE batch scan
11-22 16:24:11.177  5869  5888 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 16:24:11.178  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.178  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:24:11.178  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.178  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.178  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:24:11.178  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:24:11.178  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 16:24:11.178  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.179  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 16:24:11.179  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 16:24:11.179  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.179  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.179  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.179  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:24:11.179  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.179  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.185  5738  5738 D SprintDMHelper: simOperator: 
11-22 16:24:11.185  5738  5738 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-22 16:24:11.186  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:24:11.186  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:24:11.186  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:24:11.186  5641  5689 I org.thaliproject.p2p.btconnectorlib.Connect,ionManager: dispose
11-22 16:24:11.186  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:24:11.186  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.186  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9da09b7 removed from the list
11-22 16:24:11.187  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.187  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b561524 removed from the list
11-22 16:24:11.187  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:24:11.187  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.187  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.188  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.188  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.188  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.188  5869  5885 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 16:24:11.188  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.189  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.189  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.189  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.189  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:24:11.189  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 16:24:11.189  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.189  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b561524 not in the list
11-22 16:24:11.189  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.189  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.191  3902  5940 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-22 16:24:11.192  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.192  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.192  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.192  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-22 16:24:11.192  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:24:11.192  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.193  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@baa6a42 removed from the list
11-22 16:24:11.193  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 16:24:11.193  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 16:24:11.193  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.193  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf0288d removed from the list
,11-22 16:24:11.193  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 16:24:11.193  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@caa78af added. We now have 3 listener(s)
11-22 16:24:11.195  3902  5436 I iu.SyncManager: NEXT; no task
11-22 16:24:11.195  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.195  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.195  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 16:24:11.196  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.196  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb4e4bc added. We now have 4 listener(s)
11-22 16:24:11.196  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:24:11.196  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-22 16:24:11.197  3902  5940 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-22 16:24:11.197  3902  5940 I SystemUpdateService: now status is 0 (complete)
,11-22 16:24:11.197  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 16:24:11.197  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1edc45 added. We now have 4 listener(s)
11-22 16:24:11.197  3902  5940 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-22 16:24:11.197  3902  5940 I SystemUpdateService: file has been verified
11-22 16:24:11.198  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.198  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.199  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 16:24:11.199  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.199  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99eff9a added. We now have 5 listener(s)
11-22 16:24:11.199  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-22 16:24:11.199  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 16:24:11.199  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 16:24:11.199  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.199  3902  5940 I SystemUpdateService: OTA package size = 21989297
11-22 16:24:11.200  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 16:24:11.200  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 16:24:11.200  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 16:24:11.200  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:24:11.200  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 16:24:11.201  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 16:24:11.203  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 16:24:11.206  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 16:24:11.206  5641  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 16:24:11.206  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 16:24:11.208  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 16:24:11.208  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.208  5869  5885 E BtGatt.ContextMap: Context not found for ID 5
,11-22 16:24:11.210  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.210  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 16:24:11.210  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 16:24:11.210  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 16:24:11.210  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-22 16:24:11.214  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 16:24:11.215  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.215  5869  5888 D BtGatt.ScanManager: stopping BLe Batch
,11-22 16:24:11.216  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:24:11.217  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 16:24:11.217  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 16:24:11.217  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 16:24:11.217  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 16:24:11.217  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:24:11.217  5641  5689 D BluetoothAdapter: STATE_ON
,11-22 16:24:11.219  5869  5908 D BtGatt.GattService: registerClient() - UUID=acc70c4e-eedb-4e45-a2ca-c5e4151ff2c1
,11-22 16:24:11.220  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 16:24:11.220  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.220  5869  5885 D BtGatt.GattService: onClientRegistered() - UUID=acc70c4e-eedb-4e45-a2ca-c5e4151ff2c1, clientIf=5
11-22 16:24:11.220  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 16:24:11.220   927  5926 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Nov 2016 15:24:11 GMT], X-Android-Received-Millis=[1479828251220], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479828251182]}
11-22 16:24:11.220  5641  5685 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 16:24:11.221   927  3012 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-22 16:24:11.221   927  3012 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-22 16:24:11.221  5869  5880 D BtGatt.GattService: start scan with filters
11-22 16:24:11.221   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-22 16:24:11.223   927  3012 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-22 16:24:11.225  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 16:24:11.225  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.225  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 16:24:11.225  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.225  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 16:24:11.225  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-22 16:24:11.225  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.225  3902  5940 I SystemUpdateService: showing system update notification
11-22 16:24:11.225  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 16:24:11.225  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 16:24:11.226  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-22 16:24:11.226  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.226  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.226  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.226  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 16:24:11.227  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.229  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 16:24:11.230  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:24:11.231  5869  5888 D BtGatt.ScanManager: handling starting scan
11-22 16:24:11.232  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.233  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:24:11.233  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.233  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.233  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-22 16:24:11.233  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 16:24:11.233  5641  5689 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-22 16:24:11.233  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:24:11.233  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:24:11.233  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-22 16:24:11.233  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-22 16:24:11.233  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:24:11.233  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 16:24:11.233  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:24:11.233  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.233  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@caa78af removed from the list
11-22 16:24:11.233  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.233  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb4e4bc removed from the list
11-22 16:24:11.233  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:24:11.234  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:24:11.234  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:24:11.234  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.234  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 16:24:11.234  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 16:24:11.234  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:24:11.234  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:24:11.234  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.235  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.235  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.235  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.235  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:24:11.236  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.237  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.237  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.237  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:24:11.237  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:24:11.237  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.237  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb4e4bc not in the list
11-22 16:24:11.237  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 16:24:11.237  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.237  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryM,anager: stopForRestart. RUNNING_BLE
11-22 16:24:11.237  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 16:24:11.237  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.237  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.237  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.238  5869  5885 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 16:24:11.238  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 16:24:11.238  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.238  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.238  5869  5888 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 16:24:11.239  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:24:11.239  5869  5880 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 16:24:11.240  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 16:24:11.240  5641  5689 D BluetoothAdapter: STATE_ON
,11-22 16:24:11.241  5869  5908 D BtGatt.GattService: stopScan() - queue size =1
11-22 16:24:11.242  5869  5897 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 16:24:11.242  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.243  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 16:24:11.243  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-22 16:24:11.244   927   927 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-22 16:24:11.244  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 16:24:11.244  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.244  5869  5888 D BtGatt.ScanManager: Starting BLE batch scan
11-22 16:24:11.244  5869  5888 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-22 16:24:11.246  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-22 16:24:11.247  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:24:11.248  3902  3902 D SystemUpdateService: onDestroy
11-22 16:24:11.250  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.250  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:24:11.250  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.250  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.250  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:24:11.250  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:24:11.250  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:24:11.250  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:24:11.250  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99eff9a removed from the list
11-22 16:24:11.250  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:24:11.250  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:24:11.250  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:24:11.250  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.250  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 16:24:11.250  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1edc45 removed from the list
11-22 16:24:11.250  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.250  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 16:24:11.251  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 16:24:11.251  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.251  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.251  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.251  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:24:11.251  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 16:24:11.251  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.251  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4acea7 added. We now have 3 listener(s)
11-22 16:24:11.251  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.252  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.252  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.252  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 16:24:11.252  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.252  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfb0f54 added. We now have 4 listener(s)
11-22, 16:24:11.252  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:24:11.253  5869  5885 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 16:24:11.253  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.253  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.253  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.253  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.255  3620  5951 I VacuumService: Vacuum at: now=1479828251255 tag=VacuumService
11-22 16:24:11.255  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 16:24:11.256  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 16:24:11.256  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4894efd added. We now have 4 listener(s)
11-22 16:24:11.257  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.257  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.257  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 16:24:11.257  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.257  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@935e7f2 added. We now have 5 listener(s)
11-22 16:24:11.257  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:24:11.257  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-22 16:24:11.257  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-22 16:24:11.257  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-22 16:24:11.257  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-22 16:24:11.257  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-22 16:24:11.258  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-22 16:24:11.259  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 16:24:11.259  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.262  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 16:24:11.262  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-22 16:24:11.262  5641  5689 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-22 16:24:11.262  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-22 16:24:11.267  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.267  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-22 16:24:11.268  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-22 16:24:11.268  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-22 16:24:11.268  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-22 16:24:11.270  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 16:24:11.270  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.270  5869  5885 E BtGatt.ContextMap: Context not found for ID 5
,11-22 16:24:11.274  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.274  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-22 16:24:11.274  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-22 16:24:11.274  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-22 16:24:11.274  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-22 16:24:11.274  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.275  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:24:11.277  5869  5897 D BtGatt.GattService: registerClient() - UUID=3d0a271c-7d53-4bd7-aa65-79b1f13defcb
11-22 16:24:11.277  5869  5885 D BtGatt.GattService: onClientRegistered() - UUID=3d0a271c-7d53-4bd7-aa65-79b1f13defcb, clientIf=5
,11-22 16:24:11.278  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-22 16:24:11.278  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.278  5641  5652 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-22 16:24:11.278  5869  5888 D BtGatt.ScanManager: stopping BLe Batch
11-22 16:24:11.278  5869  5880 D BtGatt.GattService: start scan with filters
,11-22 16:24:11.281  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-22 16:24:11.282  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.282  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-22 16:24:11.282  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.282  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-22 16:24:11.282  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-22 16:24:11.282  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.283  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-22 16:24:11.283  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-22 16:24:11.283  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.283  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.283  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.283  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.283  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-22 16:24:11.284  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.284  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 16:24:11.284  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.284  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-22 16:24:11.287  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.287  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:24:11.287  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.287  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.287  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.291  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 16:24:11.291  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:24:11.292  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-22 16:24:11.292  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-22 16:24:11.293  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 16:24:11.293  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.293  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:24:11.293  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:24:11.293  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-22 16:24:11.293  5869  5888 D BtGatt.ScanManager: handling starting scan
11-22 16:24:11.293  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:24:11.293  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.293  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.293  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.293  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e4acea7 removed from the list
11-22 16:24:11.293  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.293  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-22 16:24:11.293  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfb0f54 removed from the list
,11-22 16:24:11.293  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
,11-22 16:24:11.293  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:24:11.293  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:24:11.293  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.293  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-22 16:24:11.293  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-22 16:24:11.293  5641  5689 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-22 16:24:11.293  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-22 16:24:11.293  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.294  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.294  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:24:11.295  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.295  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:24:11.295  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:24:11.295  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.295  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfb0f54 not in the list
11-22 16:24:11.295  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-22 16:24:11.295  3620  5954 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-22 16:24:11.295  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.295  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-22 16:24:11.295  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-22 16:24:11.295  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.295  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.295  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.295  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-22 16:24:11.295  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.296  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:24:11.296  5869  5897 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-22 16:24:11.296  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-22 16:24:11.297  5641  5689 D BluetoothAdapter: STATE_ON
11-22 16:24:11.297  5869  5908 D BtGatt.GattService: stopScan() - queue size =1
11-22 16:24:11.298  5869  5879 D BtGatt.GattService: unregisterClient() - clientIf=5
11-22 16:24:11.298  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-22 16:24:11.298  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-62,5,main], id: 62
,11-22 16:24:11.298  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-22 16:24:11.299  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.299  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.299  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.299  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.299  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-22 16:24:11.299  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.299  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.299  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.299  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-22 16:24:11.299  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-22 16:24:11.299  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-22 16:24:11.300  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.300  5869  5885 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-22 16:24:11.300  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.301  5869  5888 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-22 16:24:11.302  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.302  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:24:11.302  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.302  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.303  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:24:11.303  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:24:11.303  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:24:11.303  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@935e7f2 removed from the list
11-22 16:24:11.303  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:24:11.303  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:24:11.303  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:24:11.303  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.303  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4894efd removed from the list
11-22 16:24:11.303  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-22 16:24:11.303  5641  5641 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-22 16:24:11.303  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.303  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-22 16:24:11.303  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-22 16:24:11.303  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df0eb9f added. We now have 3 listener(s)
,11-22 16:24:11.303  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-22 16:24:11.304  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.304  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.304  5641  5641 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.304  5641  5641 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-22 16:24:11.304  5641  5641 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.304  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.305  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.305  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.305  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-22 16:24:11.305  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.305  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358f4ec added. We now have 4 listener(s)
11-22 16:24:11.305  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:24:11.306  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.306  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.306  5641  5641 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-22 16:24:11.306  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-22 16:24:11.306  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-22 16:24:11.306  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.306  5869  5888 D BtGatt.ScanManager: Starting BLE batch scan
11-22 16:24:11.306  5869  5888 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-22 16:24:11.308  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-22 16:24:11.308  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20860b5 added. We now have 4 listener(s)
11-22 16:24:11.309  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-22 16:24:11.309  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-22 16:24:11.309  5641  5689 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-22 16:24:11.309  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-22 16:24:11.310  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c06834a added. We now have 5 listener(s)
11-22 16:24:11.310  5641  5689 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-22 16:24:11.310  5641  5689 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-22 16:24:11.310  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:24:11.310  5641  5689 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-22 16:24:11.310  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:24:11.310  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-22 16:24:11.310  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.310  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df0eb9f removed from the list
11-22 16:24:11.310  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.310  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358f4ec removed from the list
11-22 16:24:11.310  5641  5689 D io.jxcore.node.ConnectivityMonitor: stop
11-22 16:24:11.311  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.311  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.312  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.312  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.312  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.312  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:24:11.312  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:24:11.312  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-22 16:24:11.312  5641  5689 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358f4ec not in the list
11-22 16:24:11.313  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.313  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.314  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.314  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.314  5641  5689 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-62,5,main], id: 62
11-22 16:24:11.314  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-22 16:24:11.314  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-22 16:24:11.314  5641  5689 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-22 16:24:11.314  5641  5689 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c06834a removed from the list
11-22 16:24:11.314  5641  5689 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-22 16:24:11.314  5641  5689 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-22 16:24:11.314  5641  5689 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-22 16:24:11.314  5641  5689 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20860b5 removed from the list
11-22 16:24:11.315  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-22 16:24:11.315  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-22 16:24:11.315  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-22 16:24:11.315  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 16:24:11.315  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-22 16:24:11.316  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-22 16:24:11.316  5869  5885 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-22 16:24:11.316  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.321  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-22 16:24:11.321  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:24:11.323  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 16:24:11.327  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-22 16:24:11.327  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.328  5869  5885 E BtGatt.ContextMap: Context not found for ID 5
,11-22 16:24:11.333  5869  5885 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-22 16:24:11.333  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:24:11.333  5869  5888 D BtGatt.ScanManager: stopping BLe Batch
,11-22 16:24:11.338  5869  5885 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-22 16:24:11.338  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-22 16:24:11.339  5869  5888 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-22 16:24:11.339  3620  5952 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-22 16:24:11.341  3620  5952 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-22 16:24:11.343  5869  5885 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-22 16:24:11.343  5869  5885 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-22 16:24:11.365  3620  5952 W Uploader:  no longer exists, so no auth token.
,11-22 16:24:11.370  3620  5954 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 16:24:11.433  5047  5946 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-22 16:24:11.518   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:11.666  3620  5956 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 16:24:11.680  5641  5641 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 16:24:11.751  5641  5641 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 16:24:11.805  5641  5641 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-22 16:24:11.812  3620  5952 W Uploader:  no longer exists, so no auth token.
,11-22 16:24:11.818  3620  5954 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 16:24:11.894  3620  5956 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 16:24:11.970  3620  5954 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 16:24:12.055  3620  5956 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-22 16:24:12.518   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-22 16:24:13.446  5641  5963 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 16:24:13.446  5641  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 16:24:13.834   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:14.237  5641  5963 W !!      : call onHalfStreamCopied
,11-22 16:24:14.237  5641  5963 I testCopyDataAndClose: closing input stream
,11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-22 16:24:15.012  5641  5963 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 16:24:16.862   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:19.049   927  3012 D ConnectivityService: handlePromptUnvalidated 102
,11-22 16:24:19.251  5641  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 16:24:19.251  5641  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 16:24:19.887   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:21.251  5641  5689 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-22 16:24:21.251  5641  5689 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 16:24:21.252  5641  5689 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-22 16:24:21.306  5641  5964 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-22 16:24:21.306  5641  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-22 16:24:21.306  5641  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,11-22 16:24:21.379  5641  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 16:24:21.379  5641  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 16:24:22.094   927  3010 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-22 16:24:22.910   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:23.013  5641  5965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 16:24:23.013  5641  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 16:24:23.013  5641  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 16:24:23.013  5641  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 16:24:23.013  5641  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 16:24:23.014  5641  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 16:24:23.014  5641  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 16:24:23.014  5641  5965 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 16:24:23.014  5641  5965 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 16:24:23.014  5641  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-22 16:24:23.014  5641  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-22 16:24:25.942   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:27.157  5641  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 16:24:27.157  5641  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 16:24:27.157  5641  5966 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-22 16:24:27.157  5641  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 16:24:27.157  5641  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-22 16:24:27.157  5641  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-22 16:24:27.157  5641  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-22 16:24:27.158  5641  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-22 16:24:27.158  5641  5966 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-22 16:24:27.158  5641  5966 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-22 16:24:27.158  5641  5966 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-22 16:24:27.158  5641  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-22 16:24:27.158  5641  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-22 16:24:27.160  5641  5689 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-22 16:24:27.163  5641  5967 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 16:24:27.163  5641  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-22 16:24:27.163  5641  5967 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-22 16:24:27.164  5641  5967 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 16:24:27.164  5641  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-22 16:24:27.164  5641  5967 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-22 16:24:27.164  5641  5967 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-22 16:24:27.164  5641  5967 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-22 16:24:27.169  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-22 16:24:27.169  5641  5689 I jxcore-log: 
,11-22 16:24:27.170  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-22 16:24:27.170  5641  5689 I jxcore-log: 
11-22 16:24:27.170  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-22 16:24:27.170  5641  5689 I jxcore-log: 
11-22 16:24:27.170  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-22 16:24:27.170  5641  5689 I jxcore-log: 
11-22 16:24:27.170  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG UnitTest_app: 'Total duration:  91595'
11-22 16:24:27.170  5641  5689 I jxcore-log: 
,11-22 16:24:27.173  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-22 16:24:27.173  5641  5689 I jxcore-log: 
,11-22 16:24:27.178  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 16:24:27.178  5641  5689 I jxcore-log: 
11-22 16:24:27.180  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 16:24:27.180  5641  5689 I jxcore-log: 
,11-22 16:24:27.180  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 16:24:27.180  5641  5689 I jxcore-log: 
11-22 16:24:27.180  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 16:24:27.180  5641  5689 I jxcore-log: 
11-22 16:24:27.181  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 16:24:27.181  5641  5689 I jxcore-log: 
11-22 16:24:27.181  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 16:24:27.181  5641  5689 I jxcore-log: 
11-22 16:24:27.182  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-22 16:24:27.182  5641  5689 I jxcore-log: 
11-22 16:24:27.182  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 16:24:27.182  5641  5689 I jxcore-log: 
11-22 16:24:27.182  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 16:24:27.182  5641  5689 I jxcore-log: 
,11-22 16:24:27.182  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 16:24:27.182  5641  5689 I jxcore-log: 
11-22 16:24:27.183  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 16:24:27.183  5641  5689 I jxcore-log: 
11-22 16:24:27.183  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 16:24:27.183  5641  5689 I jxcore-log: 
11-22 16:24:27.183  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-22 16:24:27.183  5641  5689 I jxcore-log: 
11-22 16:24:27.183  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 16:24:27.183  5641  5689 I jxcore-log: 
,11-22 16:24:27.184  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 16:24:27.184  5641  5689 I jxcore-log: 
11-22 16:24:27.184  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 16:24:27.184  5641  5689 I jxcore-log: 
11-22 16:24:27.184  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-22 16:24:27.184  5641  5689 I jxcore-log: 
11-22 16:24:27.185  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-22 16:24:27.185  5641  5689 I jxcore-log: 
11-22 16:24:27.185  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-22 16:24:27.185  5641  5689 I jxcore-log: 
11-22 16:24:27.185  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-22 16:24:27.185  5641  5689 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-22 16:24:27.185  5641  5689 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-22 16:24:27.185  5641  5689 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-22 16:24:27.186  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 16:24:27.186  5641  5689 I jxcore-log: 
11-22 16:24:27.186  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 16:24:27.186  5641  5689 I jxcore-log: 
11-22 16:24:27.186  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-22 16:24:27.186  5641  5689 I jxcore-log: 
,11-22 16:24:27.191  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-22 16:24:27.191  5641  5689 I jxcore-log: 
,11-22 16:24:27.193  5641  5689 I jxcore-log: 2016-11-22 15:24:27 - WARN testUtils: 'myNameCallback not set!'
11-22 16:24:27.193  5641  5689 I jxcore-log: 
,11-22 16:24:27.202  5641  5641 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-22 16:24:29.264  5641  5689 I jxcore-log: 2016-11-22 15:24:29 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-22 16:24:29.264  5641  5689 I jxcore-log: 
,11-22 16:24:29.266  5641  5689 I jxcore-log: 2016-11-22 15:24:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-22 16:24:29.266  5641  5689 I jxcore-log: 
,11-22 16:24:29.608  5641  5689 I jxcore-log: 2016-11-22 15:24:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-22 16:24:29.608  5641  5689 I jxcore-log: 
,11-22 16:24:29.634  5641  5689 I jxcore-log: 2016-11-22 15:24:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-22 16:24:29.634  5641  5689 I jxcore-log: 
,11-22 16:24:30.735  5641  5689 I jxcore-log: 2016-11-22 15:24:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-22 16:24:30.735  5641  5689 I jxcore-log: 
,11-22 16:24:30.928  5641  5689 I jxcore-log: 2016-11-22 15:24:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-22 16:24:30.928  5641  5689 I jxcore-log: 
,11-22 16:24:30.934  5641  5689 I jxcore-log: 2016-11-22 15:24:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-22 16:24:30.934  5641  5689 I jxcore-log: 
,11-22 16:24:30.938  5641  5689 I jxcore-log: 2016-11-22 15:24:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-22 16:24:30.938  5641  5689 I jxcore-log: 
,11-22 16:24:31.423  5641  5689 I jxcore-log: 2016-11-22 15:24:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-22 16:24:31.423  5641  5689 I jxcore-log: 
,11-22 16:24:31.468  5641  5689 I jxcore-log: 2016-11-22 15:24:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-22 16:24:31.468  5641  5689 I jxcore-log: 
,11-22 16:24:31.481  5641  5689 I jxcore-log: 2016-11-22 15:24:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-22 16:24:31.481  5641  5689 I jxcore-log: 
,11-22 16:24:31.486  5641  5689 I jxcore-log: 2016-11-22 15:24:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-22 16:24:31.486  5641  5689 I jxcore-log: 
,11-22 16:24:31.775  5641  5689 I jxcore-log: 2016-11-22 15:24:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-22 16:24:31.775  5641  5689 I jxcore-log: 
,11-22 16:24:31.904  5641  5689 I jxcore-log: 2016-11-22 15:24:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-22 16:24:31.904  5641  5689 I jxcore-log: 
,11-22 16:24:32.280  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-22 16:24:32.280  5641  5689 I jxcore-log: 
,11-22 16:24:32.289  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-22 16:24:32.289  5641  5689 I jxcore-log: 
,11-22 16:24:32.293  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-22 16:24:32.293  5641  5689 I jxcore-log: 
,11-22 16:24:32.298  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-22 16:24:32.298  5641  5689 I jxcore-log: 
,11-22 16:24:32.303  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-22 16:24:32.303  5641  5689 I jxcore-log: 
,11-22 16:24:32.330  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-22 16:24:32.330  5641  5689 I jxcore-log: 
,11-22 16:24:32.367  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-22 16:24:32.367  5641  5689 I jxcore-log: 
,11-22 16:24:32.374  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-22 16:24:32.374  5641  5689 I jxcore-log: 
,11-22 16:24:32.381  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-22 16:24:32.381  5641  5689 I jxcore-log: 
,11-22 16:24:32.396  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-22 16:24:32.396  5641  5689 I jxcore-log: 
,11-22 16:24:32.401  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-22 16:24:32.401  5641  5689 I jxcore-log: 
,11-22 16:24:32.407  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-22 16:24:32.407  5641  5689 I jxcore-log: 
,11-22 16:24:32.412  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-22 16:24:32.412  5641  5689 I jxcore-log: 
,11-22 16:24:32.425  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-22 16:24:32.425  5641  5689 I jxcore-log: 
,11-22 16:24:32.431  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-22 16:24:32.431  5641  5689 I jxcore-log: 
,11-22 16:24:32.454  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-22 16:24:32.454  5641  5689 I jxcore-log: 
,11-22 16:24:32.464  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-22 16:24:32.464  5641  5689 I jxcore-log: 
,11-22 16:24:32.476  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-22 16:24:32.476  5641  5689 I jxcore-log: 
,11-22 16:24:32.486  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-22 16:24:32.486  5641  5689 I jxcore-log: 
,11-22 16:24:32.499  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-22 16:24:32.499  5641  5689 I jxcore-log: 
,11-22 16:24:32.509  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-22 16:24:32.509  5641  5689 I jxcore-log: 
,11-22 16:24:32.516  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-22 16:24:32.516  5641  5689 I jxcore-log: 
,11-22 16:24:32.519   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:32.538  5641  5689 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-22 16:24:32.538  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - INFO testUtils: 'BLE multiple advertisement supported'
11-22 16:24:32.538  5641  5689 I jxcore-log: 
,11-22 16:24:32.659  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:32.659  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:32.659  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:32.659  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:32.659  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:32.659  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:32.659  5641  5689 I jxcore-log: 
,11-22 16:24:32.837  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:32.837  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:32.837  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:32.837  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:32.837  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:32.837  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:32.837  5641  5689 I jxcore-log: 
,11-22 16:24:32.841  5641  5689 I jxcore-log: 2016-11-22 15:24:32 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:32.841  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:32.841  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:32.841  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:32.841  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:32.841  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:32.841  5641  5689 I jxcore-log: 
,11-22 16:24:33.292  5641  5689 I jxcore-log: 2016-11-22 15:24:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:33.292  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:33.292  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:33.292  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:33.292  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:33.292  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:33.292  5641  5689 I jxcore-log: 
11-22 16:24:33.295  5641  5689 I jxcore-log: 2016-11-22 15:24:33 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:33.295  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:33.295  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:33.295  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:33.295  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:33.295  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:33.295  5641  5689 I jxcore-log: 
,11-22 16:24:33.521   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:34.265  5641  5689 I jxcore-log: 2016-11-22 15:24:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:34.265  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:34.265  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:34.265  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:34.265  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:34.265  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:34.265  5641  5689 I jxcore-log: 
,11-22 16:24:34.269  5641  5689 I jxcore-log: 2016-11-22 15:24:34 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:34.269  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:34.269  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:34.269  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:34.269  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:34.269  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:34.269  5641  5689 I jxcore-log: 
,11-22 16:24:34.522   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:34.843   927  5927 D NetlinkSocketObserver: NeighborEvent{elapsedMs=190820, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-22 16:24:35.009   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:35.304  5641  5689 I jxcore-log: 2016-11-22 15:24:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:35.304  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:35.304  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:35.304  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:35.304  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:35.304  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:35.304  5641  5689 I jxcore-log: 
,11-22 16:24:35.309  5641  5689 I jxcore-log: 2016-11-22 15:24:35 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:35.309  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:35.309  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:35.309  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:35.309  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:35.309  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:35.309  5641  5689 I jxcore-log: 
,11-22 16:24:35.523   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:36.344  5641  5689 I jxcore-log: 2016-11-22 15:24:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:36.344  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:36.344  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:36.344  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:36.344  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:36.344  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:36.344  5641  5689 I jxcore-log: 
,11-22 16:24:36.349  5641  5689 I jxcore-log: 2016-11-22 15:24:36 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:36.349  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:36.349  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:36.349  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:36.349  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:36.349  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:36.349  5641  5689 I jxcore-log: 
,11-22 16:24:36.525   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,11-22 16:24:37.380  5641  5689 I jxcore-log: 2016-11-22 15:24:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:37.380  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:37.380  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:37.380  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:37.380  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:37.380  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:37.380  5641  5689 I jxcore-log: 
,11-22 16:24:37.385  5641  5689 I jxcore-log: 2016-11-22 15:24:37 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:37.385  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:37.385  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:37.385  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:37.385  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:37.385  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:37.385  5641  5689 I jxcore-log: 
,11-22 16:24:37.525   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-22 16:24:38.034   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:38.417  5641  5689 I jxcore-log: 2016-11-22 15:24:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:38.417  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:38.417  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:38.417  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:38.417  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:38.417  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:38.417  5641  5689 I jxcore-log: 
,11-22 16:24:38.422  5641  5689 I jxcore-log: 2016-11-22 15:24:38 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:38.422  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:38.422  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:38.422  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:38.422  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:38.422  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:38.422  5641  5689 I jxcore-log: 
,11-22 16:24:40.040  5641  5689 I jxcore-log: 2016-11-22 15:24:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:40.040  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:40.040  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:40.040  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:40.040  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:40.040  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:40.040  5641  5689 I jxcore-log: 
,11-22 16:24:40.046  5641  5689 I jxcore-log: 2016-11-22 15:24:40 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:40.046  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:40.046  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:40.046  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:40.046  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:40.046  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:40.046  5641  5689 I jxcore-log: 
,11-22 16:24:40.300   927  5927 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,11-22 16:24:41.077  5641  5689 I jxcore-log: 2016-11-22 15:24:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:41.077  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:41.077  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:41.077  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:41.077  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:41.077  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:41.077  5641  5689 I jxcore-log: 
,11-22 16:24:41.081  5641  5689 I jxcore-log: 2016-11-22 15:24:41 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:41.081  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:41.081  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:41.081  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:41.081  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:41.081  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:41.081  5641  5689 I jxcore-log: 
,11-22 16:24:42.153  5641  5689 I jxcore-log: 2016-11-22 15:24:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:42.153  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:42.153  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:42.153  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:42.153  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:42.153  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:42.153  5641  5689 I jxcore-log: 
,11-22 16:24:42.157  5641  5689 I jxcore-log: 2016-11-22 15:24:42 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:42.157  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:42.157  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:42.157  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:42.157  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:42.157  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:42.157  5641  5689 I jxcore-log: 
,11-22 16:24:43.190  5641  5689 I jxcore-log: 2016-11-22 15:24:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:43.190  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:43.190  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:43.190  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:43.190  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:43.190  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:43.190  5641  5689 I jxcore-log: 
,11-22 16:24:43.196  5641  5689 I jxcore-log: 2016-11-22 15:24:43 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:43.196  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:43.196  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:43.196  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:43.196  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:43.196  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:43.196  5641  5689 I jxcore-log: 
,11-22 16:24:44.228  5641  5689 I jxcore-log: 2016-11-22 15:24:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:44.228  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:44.228  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:44.228  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:44.228  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:44.228  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:44.228  5641  5689 I jxcore-log: 
,11-22 16:24:44.233  5641  5689 I jxcore-log: 2016-11-22 15:24:44 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:44.233  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:44.233  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:44.233  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:44.233  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:44.233  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:44.233  5641  5689 I jxcore-log: 
,11-22 16:24:45.271  5641  5689 I jxcore-log: 2016-11-22 15:24:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:45.271  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:45.271  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:45.271  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:45.271  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:45.271  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:45.271  5641  5689 I jxcore-log: 
,11-22 16:24:45.278  5641  5689 I jxcore-log: 2016-11-22 15:24:45 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:45.278  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:45.278  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:45.278  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:45.278  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:45.278  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:45.278  5641  5689 I jxcore-log: 
,11-22 16:24:46.307  5641  5689 I jxcore-log: 2016-11-22 15:24:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:46.307  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:46.307  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:46.307  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:46.307  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:46.307  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:46.307  5641  5689 I jxcore-log: 
,11-22 16:24:46.311  5641  5689 I jxcore-log: 2016-11-22 15:24:46 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:46.311  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:46.311  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:46.311  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:46.311  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:46.311  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:46.311  5641  5689 I jxcore-log: 
,11-22 16:24:47.130   927  3012 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-22 16:24:48.021  5641  5689 I jxcore-log: 2016-11-22 15:24:48 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-22 16:24:48.021  5641  5689 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-22 16:24:48.021  5641  5689 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-22 16:24:48.021  5641  5689 I jxcore-log: emit@events.js:82:1
11-22 16:24:48.021  5641  5689 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-22 16:24:48.021  5641  5689 I jxcore-log: emit@events.js:82:1'
11-22 16:24:48.021  5641  5689 I jxcore-log: 
,11-22 16:24:48.034  5641  5689 E jxcore  : Error!: error is undefined
11-22 16:24:48.034  5641  5689 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"221","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:221:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,11-22 16:24:48.037  5641  5689 I jxcore-log: 2016-11-22 15:24:48 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
11-22 16:24:48.037  5641  5689 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:221:1
11-22 16:24:48.037  5641  5689 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
11-22 16:24:48.037  5641  5689 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
11-22 16:24:48.037  5641  5689 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
11-22 16:24:48.037  5641  5689 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
11-22 16:24:48.037  5641  5689 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
11-22 16:24:48.037  5641  5689 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
,11-22 16:24:48.038  5641  5689 I jxcore-log: 2016-11-22 15:24:48 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-22 16:24:48.038  5641  5689 I jxcore-log: 
,11-22 16:24:48.040  5641  5689 E jxcore-log: TypeError: 
11-22 16:24:48.040  5641  5689 E jxcore-log: error is undefined
11-22 16:24:48.040  5641  5689 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 221:0)
11-22 16:24:48.041  5641  5689 E jxcore-log: 
,11-22 16:24:48.612  5968  5968 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-22 16:24:48.636  5968  5968 D AndroidRuntime: CheckJNI is OFF
,11-22 16:24:48.659  5968  5968 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-22 16:24:48.686  5968  5968 I Radio-JNI: register_android_hardware_Radio DONE
,11-22 16:24:48.701  5968  5968 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-22 16:24:48.710   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-22 16:24:48.711   927   940 I ActivityManager: Killing 5641:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-22 16:24:48.808   927  3889 I WindowState: WIN DEATH: Window{6359bff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-22 16:24:48.808   927  3450 D GraphicsStats: Buffer count: 2
11-22 16:24:48.809   927  3011 D WifiService: Client connection lost with reason: 4
,11-22 16:24:48.820   927   940 W ActivityManager: Force removing ActivityRecord{552b3d4 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-22 16:24:48.857   927   950 I art     : Starting a blocking GC Explicit
,11-22 16:24:48.862   927  3886 W ActivityManager: Spurious death for ProcessRecord{e97878f 0:com.test.thalitest/u0a77}, curProc for 5641: null
,11-22 16:24:48.897   927   937 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5641 uid 10077
,11-22 16:24:48.898  3700  3700 I Keyboard.Facilitator: onFinishInput()
11-22 16:24:48.893   937   937 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[14011]" dev="sockfs" ino=14011 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-22 16:24:48.893   937   937 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[14011]" dev="sockfs" ino=14011 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-22 16:24:48.964   927   950 I art     : Explicit concurrent mark sweep GC freed 63843(3MB) AllocSpace objects, 15(488KB) LOS objects, 33% free, 29MB/43MB, paused 1.926ms total 107.211ms
,11-22 16:24:48.972  4006  5980 I MicroRecognitionRnrImpl: Starting detection.
,11-22 16:24:48.973  4006  5981 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@9cceaad
,11-22 16:24:48.975   511  5983 I AudioFlinger: AudioFlinger's thread 0xf1e80000 ready to run
,11-22 16:24:48.978   511  3032 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,11-22 16:24:48.980  4006  5981 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@9cceaad
,11-22 16:24:48.981   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-22 16:24:48.983  5968  5968 I art     : System.exit called, status: 0
11-22 16:24:48.984  5968  5968 I AndroidRuntime: VM exiting with result code 0.
,11-22 16:24:48.988   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-22 16:24:48.990   511  5983 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-22 16:24:48.990   511  5983 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
,11-22 16:24:48.990   511  5983 I ACDB-LOADER: ACDB AFE returned = -19
11-22 16:24:48.990   511  5983 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-22 16:24:48.990   511  5983 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-22 16:24:48.990   511  5983 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-22 16:24:48.998   511  5983 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-22 16:24:49.019  3700  3700 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-22 16:24:49.019  5869  5869 D BluetoothMapAppObserver: onReceive
11-22 16:24:49.019  5869  5869 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-22 16:24:49.028  4102  4220 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-22 16:24:49.030   927  2976 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-22 16:24:49.031  3700  5986 I Keyboard.Facilitator.DecoderInitializer: run()
,11-22 16:24:49.037  3700  5986 I Decoder : createOrResetDecoder
,11-22 16:24:49.047  3436  5990 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-22 16:24:49.075  3820  3820 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-22 16:24:49.081  4006  4006 I HotwordWorkerImpl: onReady
,11-22 16:24:49.092   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-22 16:24:49.090    17    17 W kworker/2:0: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 16:24:49.103  3620  3620 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-22 16:24:49.103  3620  3620 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-22 16:24:49.100    17    17 W kworker/2:0: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 16:24:49.113    17    17 W kworker/2:0: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-22 16:24:49.127   927  3450 I ActivityManager: Start proc 5993:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-22 16:24:49.128  3855  3976 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-22 16:24:49.128  3855  3976 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3855
11-22 16:24:49.128  3855  3976 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 16:24:49.128  3855  3976 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 16:24:49.132   927  3188 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-22 16:24:49.132  3436  5990 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-22 16:24:49.134  3436  5990 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-22 16:24:49.134  3436  5990 E AndroidRuntime: Process: android.process.acore, PID: 3436
11-22 16:24:49.134  3436  5990 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-22 16:24:49.134  3436  5990 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 16:24:49.135  4006  4019 W SearchService: Abort, client detached.
11-22 16:24:49.136   927  5999 E DropBoxManagerService: Can't write: system_app_crash
11-22 16:24:49.136   927  5999 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 16:24:49.136   927  5999 E DropBoxManagerService: 	... 5 more
,11-22 16:24:49.137  4006  4006 I HotwordDetector: Closing mic
11-22 16:24:49.137  4006  4221 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9cceaad
11-22 16:24:49.137  4006  5981 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-22 16:24:49.143  3436  3465 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
11-22 16:24:49.143  3436  3465 I Process : Sending signal. PID: 3436 SIG: 9
11-22 16:24:49.150   403   403 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[14232]" dev="sockfs" ino=14232 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 16:24:49.153   403   403 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[14232]" dev="sockfs" ino=14232 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 16:24:49.153  2974  2974 W Binder_4: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[33614]" dev="sockfs" ino=33614 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 16:24:49.153  2974  2974 W Binder_4: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[33614]" dev="sockfs" ino=33614 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-22 16:24:49.157   927  6006 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-22 16:24:49.167  3620  3620 I ConfigService: onCreate
,11-22 16:24:49.167   927  6007 E DropBoxManagerService: Can't write: system_app_crash
11-22 16:24:49.167   927  6007 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-22 16:24:49.167   927  6007 E DropBoxManagerService: 	... 5 more
11-22 16:24:49.168  3902  6008 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-22 16:24:49.168  3902  6008 D AccountUtils: Clearing selected account for com.test.thalitest
,11-22 16:24:49.170  3620  6009 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-22 16:24:49.170  3620  6009 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-22 16:24:49.171  3620  6009 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-22 16:24:49.173  3620  6009 W SQLiteOpenHelper: Opened config.db in read-only mode
,11-22 16:24:49.178   927  3451 I ActivityManager: Process android.process.acore (pid 3436) has died
,11-22 16:24:49.179   927  3451 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-22 16:24:49.200   511  5983 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-22 16:24:49.202   511  5983 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-22 16:24:49.206  3902  6008 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-22 16:24:49.212   511  5983 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-22 16:24:49.212   511  5983 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-22 16:24:49.213   511  3032 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-22 16:24:49.215  4006  4235 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-22 16:24:49.217  4006  5980 I MicroRecognitionRnrImpl: Detection finished
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-22 16:24:49.217  3902  6008 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at, android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-22 16:24:49.218  3902  6008 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-22 16:24:49.219  3902  6008 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-22 16:24:49.222  3700  5986 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-22 16:24:49.249  3902  6015 I GMPM-SVC: App measurement is starting up
11-22 16:24:49.251  3902  6015 E GMPM-SVC: AppMeasurementService not registered/enabled
11-22 16:24:49.252  3902  6015 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-22 16:24:49.509   384   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
