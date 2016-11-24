#### Test 95190072894c132_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 16:19:47.154  3846  4235 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-24 16:19:47.238  3846  4235 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-24 16:19:47.606  5594  5594 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 16:19:47.611  5594  5594 D AndroidRuntime: CheckJNI is OFF
11-24 16:19:47.638  5594  5594 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 16:19:47.671  5594  5594 I Radio-JNI: register_android_hardware_Radio DONE
11-24 16:19:47.686  5594  5594 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 16:19:47.689   928  3842 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 16:19:47.725  5594  5594 D AndroidRuntime: Shutting down VM
11-24 16:19:47.735  3975  3992 W SearchService: Abort, client detached.
11-24 16:19:47.742  3975  3975 I HotwordDetector: Closing mic
11-24 16:19:47.743  3975  4208 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@75bbfc6
11-24 16:19:47.744  3975  4227 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-24 16:19:47.760   928  3872 I ActivityManager: Start proc 5603:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 16:19:47.817   515  4229 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-24 16:19:47.818   515  4229 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-24 16:19:47.823   515  4229 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 16:19:47.823   515  4229 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-24 16:19:47.824   515  2999 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 16:19:47.825  3975  4211 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 16:19:47.827  3975  4222 I MicroRecognitionRnrImpl: Detection finished
11-24 16:19:47.851  5603  5603 I CordovaLog: Changing log level to DEBUG(3)
11-24 16:19:47.852  5603  5603 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 16:19:47.852  5603  5603 D CordovaActivity: CordovaActivity.onCreate()
11-24 16:19:47.858  5603  5603 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-24 16:19:47.883  5603  5603 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-24 16:19:47.944  5603  5603 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 9706-9762)
11-24 16:19:47.944  5603  5603 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 16:19:47.973  5603  5603 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c19416d}
11-24 16:19:47.973  5603  5603 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-24 16:19:47.973  5603  5603 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 16:19:47.976  5603  5603 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 16:19:47.977  5603  5603 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 16:19:48.035  5603  5603 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 16:19:48.043  5603  5603 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 16:19:48.044  5603  5603 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 16:19:48.044  5603  5603 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 16:19:48.044  5603  5603 I Adreno  : Build Date                       : 12/06/15
11-24 16:19:48.044  5603  5603 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 16:19:48.044  5603  5603 I Adreno  : Local Branch                     : mybranch17112971
11-24 16:19:48.044  5603  5603 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 16:19:48.044  5603  5603 I Adreno  : Remote Branch                    : NONE
11-24 16:19:48.044  5603  5603 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 16:19:48.081   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c46637e:true
,11-24 16:19:48.114   409   409 W Binder_2: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[14908]" dev="sockfs" ino=14908 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 16:19:48.114   409   409 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[14908]" dev="sockfs" ino=14908 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:19:48.128  5603  5603 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 16:19:48.138  5603  5603 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 16:19:48.141  5603  5603 D PluginManager: init()
,11-24 16:19:48.143  5603  5603 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 16:19:48.159  5603  5603 D CordovaActivity: Started the activity.
,11-24 16:19:48.159  5603  5603 D CordovaActivity: Resumed the activity.
,11-24 16:19:48.157   409   409 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33152]" dev="sockfs" ino=33152 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:19:48.157   409   409 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33152]" dev="sockfs" ino=33152 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 16:19:48.163  5603  5640 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 16:19:48.161  3828  3828 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[26140]" dev="sockfs" ino=26140 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 16:19:48.161  3828  3828 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[26140]" dev="sockfs" ino=26140 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:19:48.167  5603  5627 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 16:19:48.193  5603  5640 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 16:19:48.261  3883  3883 W Binder_E: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31385]" dev="sockfs" ino=31385 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:19:48.261  3883  3883 W Binder_E: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31385]" dev="sockfs" ino=31385 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 16:19:48.268   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +527ms
,11-24 16:19:48.264  3847  3847 W Binder_A: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31384]" dev="sockfs" ino=31384 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:19:48.264  3847  3847 W Binder_A: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31384]" dev="sockfs" ino=31384 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 16:19:48.270  3659  3659 I Keyboard.Facilitator: onFinishInput()
,11-24 16:19:48.284  5603  5603 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 16:19:48.303  5603  5603 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5603
,11-24 16:19:48.424  5603  5603 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 16:19:48.695  5603  5642 D jxcore_app_log: JniHelper::setJavaVM(0xf52fc000), pthread_self() = -581174992
,11-24 16:19:48.701  5603  5642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 16:19:48.701  5603  5642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 16:19:48.701  5603  5642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 16:19:48.701  5603  5642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 16:19:48.701  5603  5642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-24 16:19:48.701  5603  5642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4c506b added. We now have 1 listener(s)
,11-24 16:19:48.704  5603  5642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
11-24 16:19:48.704  5603  5642 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:19:48.705  5603  5642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:19:48.705  5603  5642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 16:19:48.711  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-24 16:19:48.712  5603  5642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3469786 added. We now have 1 listener(s)
11-24 16:19:48.712  5603  5642 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:19:48.721   928  2976 D WifiService: New client listening to asynchronous messages
,11-24 16:19:48.721  5603  5642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 16:19:48.721  5603  5642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-24 16:19:48.722  5603  5642 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 16:19:48.722  5603  5642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 16:19:48.722  5603  5642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-24 16:19:48.722  5603  5642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 16:19:48.722  5603  5642 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 16:19:48.723  5603  5642 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 16:19:48.882  5603  5603 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
11-24 16:19:48.884  5603  5603 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-24 16:19:48.885  5603  5603 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 16:19:49.126   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:19:49.210  5603  5612 I art     : Background sticky concurrent mark sweep GC freed 74446(7MB) AllocSpace objects, 15(760KB) LOS objects, 22% free, 25MB/32MB, paused 2.295ms total 218.564ms
,11-24 16:19:50.296  5603  5612 I art     : Background partial concurrent mark sweep GC freed 64844(7MB) AllocSpace objects, 3(1492KB) LOS objects, 36% free, 27MB/43MB, paused 2.292ms total 168.417ms
,11-24 16:19:50.382  5603  5650 W jxcore-log: Initializing JXcore engine
,11-24 16:19:50.382  5603  5650 W jxcore-log: JXcore engine is ready
,11-24 16:19:50.401  5650  5650 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12532 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
11-24 16:19:50.401  5650  5650 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[13532]" dev="sockfs" ino=13532 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,11-24 16:19:50.401  5650  5650 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 16:19:50.401  5650  5650 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33124]" dev="sockfs" ino=33124 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 16:19:50.414  5603  5650 W jxcore-log: Starting JXcore engine
,11-24 16:19:50.463  5603  5650 W jxcore-log: Platform android
11-24 16:19:50.463  5603  5650 W jxcore-log: 
,11-24 16:19:50.464  5603  5650 W jxcore-log: Process ARCH arm
11-24 16:19:50.464  5603  5650 W jxcore-log: 
,11-24 16:19:50.646  5603  5650 I jxcore-log: JXcore Cordova bridge is ready!
11-24 16:19:50.646  5603  5650 I jxcore-log: 
,11-24 16:19:50.646  5603  5650 W jxcore-log: JXcore engine is started
,11-24 16:19:50.660  5603  5642 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 16:19:50.667  5603  5603 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 16:19:50.667  5603  5603 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 16:19:51.324  3587  3587 I ConfigService: onDestroy
,11-24 16:19:52.098   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:19:52.751   928  3150 I ActivityManager: Killing 5396:com.android.chrome/u0a39 (adj 15): empty #17
,11-24 16:19:52.794   928  3150 I ActivityManager: Killing 5381:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,11-24 16:19:53.099   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:19:54.100   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:19:55.101   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:19:56.102   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:19:57.102   619   619 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 16:19:57.921   928  2976 D WifiService: New client listening to asynchronous messages
,11-24 16:19:57.925  3975  5651 W CronetSyncConnectionRcs: Upload content type not set.
,11-24 16:20:00.256   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 16:20:00.325  5603  5650 I jxcore-log: 2016-11-24 15:20:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 16:20:00.325  5603  5650 I jxcore-log: 
,11-24 16:20:00.326  5603  5650 I jxcore-log: 2016-11-24 15:20:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 16:20:00.326  5603  5650 I jxcore-log: 
,11-24 16:20:00.330  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-24 16:20:00.330  5603  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:20:00.330  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:00.330  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:00.330  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:00.330  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:20:00.330  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:20:00.330  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:20:00.330  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:20:00.330  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 16:20:00.331  5603  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:20:00.332  5603  5650 I jxcore-log: 2016-11-24 15:20:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 16:20:00.332  5603  5650 I jxcore-log: 
11-24 16:20:00.333  5603  5650 I jxcore-log: 2016-11-24 15:20:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 16:20:00.333  5603  5650 I jxcore-log: 
,11-24 16:20:00.582  5603  5650 I jxcore-log: 2016-11-24 15:20:00 - DEBUG UnitTest_app: 'Running unit tests'
11-24 16:20:00.582  5603  5650 I jxcore-log: 
,11-24 16:20:00.583  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:20:00.583  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804be90 added. We now have 2 listener(s)
11-24 16:20:00.584  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:20:00.584  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:20:00.584  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:20:00.584  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 16:20:00.584  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f753389 added. We now have 2 listener(s)
11-24 16:20:00.584  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:20:00.585  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 16:20:00.586  5603  5650 D executeNativeTests: Running unit tests
,11-24 16:20:00.628  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 16:20:00.628  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e added. We now have 3 listener(s)
11-24 16:20:00.629  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:20:00.629  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:20:00.629  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:20:00.629  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 16:20:00.629  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f added. We now have 3 listener(s)
11-24 16:20:00.629  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:20:00.630  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 16:20:00.632  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-24 16:20:00.632  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 16:20:00.632  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 16:20:00.632  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 16:20:00.633  5603  5650 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 16:20:00.634  5603  5650 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 16:20:00.634  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 16:20:00.634  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:20:00.634  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:20:00.634  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:20:00.634  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:00.635  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 16:20:00.635  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:00.635  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:00.636  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:00.636  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:20:00.636  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e removed from the list
11-24 16:20:00.636  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:00.636  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f removed from the list
,11-24 16:20:00.636  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:00.636  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.636  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.637  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.637  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:00.637  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.637  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:00.637  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:00.637  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:00.637  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:00.638  5603  5650 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-24 16:20:00.639  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:00.639  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:00.639  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:00.639  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:20:00.639  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:00.639  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:00.639  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:00.639  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:00.639  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:00.639  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.639  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.640  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.640  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:00.640  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.640  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:00.640  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:00.640  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:00.640  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 16:20:00.643  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 16:20:00.644  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 16:20:00.644  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 16:20:00.644  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 16:20:00.644  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-24 16:20:00.644  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 16:20:00.644  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:00.644  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:00.644  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:00.644  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:00.644  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:00.644  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:00.644  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:00.644  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:00.644  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:00.644  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.644  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.645  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.645  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.645  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.645  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:00.645  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:00.645  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:00.645  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:00.646  5603  5650 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 16:20:00.647  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:20:00.647  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 16:20:00.655  5603  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:20:00.655  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:00.655  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:00.655  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:00.655  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:20:00.655  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:20:00.655  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:20:00.655  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:20:00.655  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 16:20:00.656  5603  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:20:00.656  5603  5650 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 16:20:00.656  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:20:00.656  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:20:00.656  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:20:00.656  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:20:00.656  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 16:20:00.658  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 16:20:00.658  5603  5650 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:20:00.658  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 16:20:00.661  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:20:00.662  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.662  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:20:00.663  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:20:00.663  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:20:00.663  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 16:20:00.664  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-24 16:20:00.665  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:20:00.666  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 16:20:00.666  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.666  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:20:00.667  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:20:00.667  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:20:00.667  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:20:00.667  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.667  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:20:00.669  4654  4865 D BtGatt.GattService: registerClient() - UUID=d51df0ae-6a6c-48bd-a1ac-dc81b1ce4773
11-24 16:20:00.670  4654  4719 D BtGatt.GattService: onClientRegistered() - UUID=d51df0ae-6a6c-48bd-a1ac-dc81b1ce4773, clientIf=5
11-24 16:20:00.671  5603  5614 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 16:20:00.672  4654  4669 D BtGatt.GattService: start scan with filters
11-24 16:20:00.678  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 16:20:00.678  4654  4731 D BtGatt.ScanManager: handling starting scan
11-24 16:20:00.678  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.678  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:20:00.678  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.679  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:20:00.679  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:20:00.679  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:20:00.679  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:20:00.679  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 16:20:00.679  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:20:00.679  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.679  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:20:00.679  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:20:00.680  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.680  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:20:00.680  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.680  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:00.680  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:20:00.680  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:20:00.680  5603  5650 I io.jxcore.node.ConnectionHelper: start: OK
11-24 16:20:00.680  4654  4731 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
11-24 16:20:00.684  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:20:00.684  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:20:00.685  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:20:00.685  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:20:00.685  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:20:00.689  4654  4719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:20:00.689  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:00.689  4654  4731 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 16:20:00.696  4654  4719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:20:00.696  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:20:00.697  4654  4731 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:20:00.697  4654  4731 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 16:20:00.709  4654  4719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:20:00.709  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:00.715  4654  4719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 16:20:00.715  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:20:01.187  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 16:20:01.188  5603  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 16:20:01.188  5603  5603 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 16:20:03.280   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 16:20:05.685  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:05.685  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:05.685  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-24 16:20:05.685  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:20:05.685  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 16:20:05.685  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:05.685  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 16:20:05.686  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 16:20:05.686  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.686  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 16:20:05.686  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:20:05.687  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:05.687  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.687  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.687  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 16:20:05.687  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.688  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:20:05.688  4654  4669 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:20:05.689  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:20:05.690  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:20:05.690  4654  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 16:20:05.690  4654  4865 D BtGatt.GattService: stopScan() - queue size =1
11-24 16:20:05.691  4654  4873 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:20:05.692  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:20:05.692  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:05.692  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:20:05.692  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.692  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.692  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.692  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.693  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:20:05.693  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:05.693  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.693  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.693  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:20:05.694  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 16:20:05.694  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:20:05.695  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.698  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.698  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:20:05.698  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.698  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:05.698  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:05.698  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:20:05.698  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:20:05.699  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:05.699  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:05.699  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:05.699  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:05.699  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:05.699  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...,
11-24 16:20:05.699  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:20:05.699  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:20:05.700  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:20:05.700  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 16:20:05.700  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 16:20:05.700  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-24 16:20:05.700  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 16:20:05.701  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:20:05.701  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 16:20:05.701  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:20:05.701  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:20:05.702  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 16:20:05.704  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:20:05.705  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:20:05.705  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 16:20:05.710  4654  4654 D BtGatt.ScanManager: awakened up at time 97529
,11-24 16:20:05.744  4654  4719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,11-24 16:20:05.744  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:20:05.744  4654  4719 D BtGatt.GattService: current time is 97563627769
,11-24 16:20:05.744  4654  4719 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -90, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -93, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -78, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -89, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 16:20:05.746  4654  4719 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
11-24 16:20:05.747  4654  4719 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 16:20:05.747  4654  4719 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 16:20:05.747  4654  4719 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 16:20:05.753  4654  4719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 16:20:05.753  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:05.753  4654  4731 D BtGatt.ScanManager: stopping BLe Batch
11-24 16:20:05.758  4654  4719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 16:20:05.758  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:05.758  4654  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:20:05.764  4654  4719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:20:05.764  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:20:05.812  4851  4897 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-24 16:20:05.813  4851  4851 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-24 16:20:06.202  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:20:10.343   928   941 I ActivityManager: Killing 4483:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-24 16:20:10.496  3587  5666 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-24 16:20:10.537  3587  5664 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-24 16:20:10.540  3587  5664 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-24 16:20:10.570  3587  5664 W Uploader:  no longer exists, so no auth token.
,11-24 16:20:10.578  3587  5666 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:20:10.715  5603  5650 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 16:20:10.719  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 16:20:10.719  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 16:20:10.728  5603  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:20:10.728  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:10.728  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:10.728  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:10.728  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:20:10.728  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:20:10.728  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:20:10.728  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:20:10.728  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 16:20:10.731  5603  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 16:20:10.732  5603  5650 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 16:20:10.732  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:20:10.732  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:20:10.732  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:20:10.732  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:20:10.732  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 16:20:10.738  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:10.741  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 16:20:10.741  5603  5650 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:20:10.741  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 16:20:10.742  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:10.745  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:10.745  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:20:10.745  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:20:10.746  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:20:10.746  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 16:20:10.748  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.748  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:20:10.748  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-24 16:20:10.748  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:20:10.748  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:20:10.748  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.749  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:20:10.751  4654  4865 D BtGatt.GattService: registerClient() - UUID=5a286400-ec26-4b10-915f-478ed32d393b
11-24 16:20:10.752  4654  4719 D BtGatt.GattService: onClientRegistered() - UUID=5a286400-ec26-4b10-915f-478ed32d393b, clientIf=5
11-24 16:20:10.752  5603  5614 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 16:20:10.752  4654  4873 D BtGatt.GattService: start scan with filters
,11-24 16:20:10.755  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 16:20:10.755  4654  4731 D BtGatt.ScanManager: handling starting scan
11-24 16:20:10.755  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.755  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:20:10.755  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.756  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:20:10.756  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:20:10.756  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.756  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:20:10.756  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-24 16:20:10.756  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.756  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.756  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.756  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.757  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:20:10.757  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:10.762  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.762  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:20:10.762  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.762  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.762  5603  5650 I io.jxcore.node.ConnectionHelper: start: OK
11-24 16:20:10.763  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.763  4654  4719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:20:10.763  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.763  4654  4731 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 16:20:10.766  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.766  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-24 16:20:10.766  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.766  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:20:10.767  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:10.767  5603  5650 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 16:20:10.767  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:10.767  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 16:20:10.768  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:20:10.768  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 16:20:10.768  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:10.768  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 16:20:10.768  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:20:10.768  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.768  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:20:10.768  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:20:10.768  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.768  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.768  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.768  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 16:20:10.768  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:10.770  5603  5650 D BluetoothAdapter: STATE_ON
,11-24 16:20:10.770  4654  4669 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:20:10.770  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:20:10.770  4654  4719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:20:10.771  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.771  4654  4731 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:20:10.771  4654  4731 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 16:20:10.771  5603  5650 D BluetoothAdapter: STATE_ON
,11-24 16:20:10.772  4654  4873 D BtGatt.GattService: stopScan() - queue size =1
11-24 16:20:10.773  4654  4865 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:20:10.773  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:20:10.773  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.773  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:20:10.773  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.773  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.774  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.774  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.774  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 16:20:10.774  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.774  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.774  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.774  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:20:10.774  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 16:20:10.775  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:20:10.775  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:10.778  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:10.778  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:20:10.778  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.778  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.778  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:10.778  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:20:10.779  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:20:10.779  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:20:10.779  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:10.779  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:20:10.779  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:10.779  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:20:10.779  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:10.779  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.779  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:10.779  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:20:10.779  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:10.779  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:20:10.779  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:20:10.779  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.779  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.779  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.779  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 16:20:10.779  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.779  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.781  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.781  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.781  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.781  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.781  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.782  4654  4719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:20:10.782  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.783  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:10.783  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.783  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.783  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:10.783  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:10.783  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:10.783  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:10.784  5603  5650 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 16:20:10.786  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 16:20:10.786  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 16:20:10.788  4654  4719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 16:20:10.788  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:20:10.789  4654  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:20:10.792  5603  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:20:10.792  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:10.792  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:10.792  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:10.792  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:20:10.792  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:20:10.792  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:20:10.792  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:20:10.792  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 16:20:10.794  5603  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:20:10.794  5603  5650 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 16:20:10.794  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:20:10.794  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:20:10.794  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:20:10.794  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:20:10.794  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 16:20:10.795  4654  4719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:20:10.795  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.795  4654  4719 E BtGatt.ContextMap: Context not found for ID 5
,11-24 16:20:10.798  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:20:10.800  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:10.801  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 16:20:10.801  5603  5650 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:20:10.801  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 16:20:10.802  4654  4719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 16:20:10.803  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.803  4654  4731 D BtGatt.ScanManager: stopping BLe Batch
,11-24 16:20:10.804  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:10.804  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:20:10.805  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:20:10.805  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:20:10.805  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 16:20:10.808  4654  4719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 16:20:10.808  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.808  4654  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:20:10.809  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.809  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 16:20:10.809  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:20:10.809  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:20:10.809  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:20:10.809  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.809  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:20:10.812  4654  4667 D BtGatt.GattService: registerClient() - UUID=2f00482c-700f-463b-a461-3f410b7e9611
,11-24 16:20:10.813  4654  4719 D BtGatt.GattService: onClientRegistered() - UUID=2f00482c-700f-463b-a461-3f410b7e9611, clientIf=5
11-24 16:20:10.814  5603  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 16:20:10.814  4654  4873 D BtGatt.GattService: start scan with filters
,11-24 16:20:10.815  4654  4719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 16:20:10.815  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.816  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 16:20:10.816  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.816  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:20:10.816  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.816  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:20:10.816  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-24 16:20:10.817  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.817  4654  4731 D BtGatt.ScanManager: handling starting scan
11-24 16:20:10.817  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:20:10.817  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 16:20:10.817  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.817  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.817  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.817  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.818  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:20:10.818  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.820  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.821  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:20:10.821  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.821  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:10.821  5603  5650 I io.jxcore.node.ConnectionHelper: start: OK
11-24 16:20:10.821  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.823  4654  4719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:20:10.823  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.823  4654  4731 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 16:20:10.823  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.823  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.823  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:20:10.823  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:20:10.827  4654  4719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:20:10.827  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.828  4654  4731 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:20:10.828  4654  4731 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 16:20:10.837  4654  4719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:20:10.837  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:10.841  4654  4719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 16:20:10.842  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:20:11.030  3587  5668 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:20:11.182  3587  5666 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:20:11.245  3587  5664 W Uploader:  no longer exists, so no auth token.
,11-24 16:20:11.259  3587  5668 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:20:11.325  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 16:20:11.325  5603  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 16:20:11.325  5603  5603 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 16:20:11.343  3587  5666 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:20:11.417  3587  5668 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 16:20:11.685  4654  4654 D BtGatt.ScanManager: awakened up at time 103504
11-24 16:20:11.686  4654  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:20:11.702  4654  4719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,11-24 16:20:11.702  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:11.702  4654  4719 D BtGatt.GattService: current time is 103521744159
11-24 16:20:11.702  4654  4719 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -88, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -93, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 16:20:11.703  4654  4719 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 16:20:11.703  4654  4719 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 16:20:11.709  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 2. Current thread: Thread[main,5,main], id: 1
,11-24 16:20:11.709  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-93, mTimestampNanos=103272001190}
11-24 16:20:11.710  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-93, mTimestampNanos=103272001190}
11-24 16:20:11.710  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = 22:61:70:F2:FB:B6, provideBluetoothMacAddressRequestId = nullextra info = 81]
11-24 16:20:11.711  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-24 16:20:11.711  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults. scan = ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-88, mTimestampNanos=103222001190}
11-24 16:20:11.711  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-88, mTimestampNanos=103222001190}
11-24 16:20:11.711  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement: [UUID = null, bluetoothMacAddress = D1:0E:8F:74:D2:B6, provideBluetoothMacAddressRequestId = nullextra info = 37]
11-24 16:20:11.711  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: parsedAdvertisement uuid mismatch
,11-24 16:20:15.821  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:20:15.822  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:15.822  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 16:20:15.822  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:20:15.822  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 16:20:15.823  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 16:20:15.823  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 16:20:15.823  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 16:20:15.823  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.823  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:20:15.823  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:20:15.824  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:15.824  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.824  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:15.824  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 16:20:15.825  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.828  5603  5650 D BluetoothAdapter: STATE_ON
,11-24 16:20:15.829  4654  4669 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:20:15.829  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:20:15.830  4654  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:20:15.831  5603  5650 D BluetoothAdapter: STATE_ON
,11-24 16:20:15.832  4654  4667 D BtGatt.GattService: stopScan() - queue size =1
11-24 16:20:15.834  4654  4873 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-24 16:20:15.836  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:20:15.836  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.837  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:20:15.837  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.837  4654  4654 D BtGatt.ScanManager: awakened up at time 107656
11-24 16:20:15.837  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.840  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.840  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.840  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:20:15.841  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.841  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:15.841  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.841  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:20:15.841  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 16:20:15.842  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:20:15.843  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.844  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.844  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:20:15.845  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.845  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:15.845  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:20:15.845  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 16:20:15.845  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:20:15.845  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:20:15.845  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:20:15.845  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:20:15.845  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:20:15.846  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:20:15.846  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:20:15.846  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:20:15.846  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:20:15.846  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:20:15.848  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:20:15.848  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:20:15.848  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 16:20:15.851  4654  4719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
11-24 16:20:15.851  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:20:15.851  4654  4719 D BtGatt.GattService: current time is 107670787399
11-24 16:20:15.851  4654  4719 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -88, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -92, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 16:20:15.852  4654  4719 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 16:20:15.852  4654  4719 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 16:20:15.852  4654  4719 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-24 16:20:15.852  4654  4719 E BtGatt.ContextMap: Context not found for ID 5
,11-24 16:20:15.860  4654  4719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 16:20:15.860  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:15.860  4654  4731 D BtGatt.ScanManager: stopping BLe Batch
,11-24 16:20:15.866  4654  4719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 16:20:15.866  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:20:15.866  4654  4731 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:20:15.871  4654  4719 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:20:15.872  4654  4719 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:20:16.347  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:20:16.348  5603  5603 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:16.348  5603  5603 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 16:20:20.847  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:20:20.847  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.847  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:20:20.848  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:20.848  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:20:20.848  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 16:20:20.848  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:20.848  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.849  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.849  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.849  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:20:20.849  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:20:20.852  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.852  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.856  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.856  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.856  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.856  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:20.856  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 16:20:20.857  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:20.857  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:20.859  5603  5650 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-24 16:20:20.860  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:20.861  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.861  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:20:20.861  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:20.861  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 16:20:20.861  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.862  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.862  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:20.862  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:20.862  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.862  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.865  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.865  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.866  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.866  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:20.866  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 16:20:20.866  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.866  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:20.869  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 16:20:20.870  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:20:20.870  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.870  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:20.870  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:20:20.870  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:20.870  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
,11-24 16:20:20.871  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:20.871  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.871  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:20:20.872  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.872  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.874  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.874  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.875  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.875  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:20.875  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:20.875  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:20.875  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.876  5603  5650 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 16:20:20.877  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:20:20.877  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.877  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:20.877  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:20:20.878  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:20.878  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.878  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.878  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:20.878  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:20.878  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.878  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.881  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.882  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.882  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.882  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:20.882  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 16:20:20.882  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.882  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.884  5603  5650 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 16:20:20.884  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:20.884  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.884  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:20:20.885  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:20.885  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:20.885  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.885  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.885  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.885  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:20.885  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.886  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.888  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.888  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.888  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.888  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:20.888  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:20.888  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.888  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.890  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 16:20:20.890  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 16:20:20.890  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 16:20:20.890  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 16:20:20.890  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:20:20.890  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:20:20.891  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 16:20:20.891  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 16:20:20.891  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 16:20:20.891  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:20:20.891  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.891  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:20.891  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:20.892  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:20.892  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.892  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.892  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.892  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:20.892  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.893  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.895  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.895  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.895  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.895  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 16:20:20.895  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:20.895  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.895  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:20.896  5603  5650 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 16:20:20.897  5603  5650 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 16:20:20.897  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-24 16:20:20.902  5603  5650 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 16:20:20.903  5603  5650 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 16:20:20.903  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 16:20:20.903  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 16:20:20.903  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-24 16:20:20.903  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 16:20:20.903  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 16:20:20.903  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 16:20:20.903  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 16:20:20.903  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 16:20:20.904  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 16:20:20.905  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-24 16:20:20.905  5603  5650 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,11-24 16:20:20.906  5603  5650 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-24 16:20:20.906  5603  5650 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 16:20:20.906  5603  5650 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 16:20:20.906  5603  5650 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 16:20:20.906  5603  5650 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 16:20:20.907  5603  5650 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 16:20:20.907  5603  5650 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 16:20:20.907  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-24 16:20:20.910  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-24 16:20:20.911  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 16:20:20.911  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-24 16:20:20.912  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 16:20:20.912  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 16:20:20.912  5603  5650 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 16:20:20.912  5603  5650 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 16:20:20.912  5603  5650 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 16:20:20.913  5603  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-24 16:20:20.913  5603  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,11-24 16:20:20.913  5603  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 16:20:20.913  5603  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-24 16:20:20.914  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:20.914  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.914  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:20.914  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:20.914  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 16:20:20.917  4669  4669 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33243]" dev="sockfs" ino=33243 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 16:20:20.917  4669  4669 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33243]" dev="sockfs" ino=33243 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 16:20:20.914  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 16:20:20.915  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.915  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.915  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.915  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:20.915  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.916  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.916  5603  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-24 16:20:20.916  5603  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-24 16:20:20.917  5603  5673 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 16:20:20.917  5603  5673 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:20:20.918  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.918  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.918  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.918  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:20.918  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:20.918  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:20.918  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.919  5603  5650 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 16:20:20.920  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:20.921  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.921  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:20.921  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:20.921  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:20.921  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.921  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:20.921  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.921  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:20.921  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.921  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.926  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.926  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.926  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.926  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:20.926  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:20.926  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.926  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.927  5603  5650 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 16:20:20.928  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:20.928  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.928  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:20.928  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:20:20.928  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:20.928  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.928  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.928  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.928  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:20.928  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.928  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.930  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.930  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.930  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.930  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:20.930  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:20.930  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.930  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.931  5603  5650 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 16:20:20.931  5603  5650 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,11-24 16:20:20.931  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 16:20:20.931  5603  5650 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-24 16:20:20.931  5603  5650 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 16:20:20.931  5603  5650 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 16:20:20.931  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 16:20:20.932  5603  5650 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 16:20:20.932  5603  5650 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 16:20:20.932  5603  5650 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 16:20:20.932  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-24 16:20:20.932  5603  5650 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 16:20:20.932  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:20.932  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:20.932  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:20.932  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:20.932  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:20.932  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.932  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:20.932  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.932  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:20.932  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.933  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.934  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.934  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:20.934  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:20.934  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:20.934  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:20.934  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:20.934  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.935  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:20.935  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:20.935  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:20.935  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:20.935  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:20.935  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:20:22.104   619   619 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-24 16:20:22.104   619   619 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 16:20:25.936  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.937  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:25.937  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:20:25.937  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:25.937  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:25.938  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:25.938  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:25.938  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:20:25.938  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:25.938  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:25.939  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:25.939  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:25.939  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:25.939  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:25.939  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.940  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:25.945  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:25.945  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.945  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.945  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:25.945  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 16:20:25.946  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.946  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:25.949  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 16:20:25.951  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:20:25.951  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 16:20:25.958  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 16:20:25.961  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-24 16:20:25.961  5603  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-24 16:20:25.961  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 16:20:25.961  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-24 16:20:25.962  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 16:20:25.962  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 16:20:25.962  5603  5603 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 16:20:25.962  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:25.962  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-24 16:20:25.962  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 16:20:25.962  5603  5675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:20:25.962  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 16:20:25.962  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:20:25.963  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 16:20:25.963  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 16:20:25.964  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
,11-24 16:20:25.964  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.964  5603  5603 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 16:20:25.964  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:20:25.964  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.964  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 16:20:25.964  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 16:20:25.964  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:25.961  4873  4873 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33248]" dev="sockfs" ino=33248 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 16:20:25.966  5603  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 16:20:25.966  5603  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 16:20:25.966  5603  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-24 16:20:25.967  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.961  4873  4873 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33248]" dev="sockfs" ino=33248 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 16:20:25.967  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:20:25.967  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.967  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.967  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:25.967  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:20:25.967  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 16:20:25.967  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:25.968  5603  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 16:20:25.968  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:25.968  5603  5603 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:25.968  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:25.968  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:20:25.968  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:20:25.968  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:25.968  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:25.968  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.968  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:25.968  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:25.968  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:25.969  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:25.971  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.971  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.971  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.971  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:25.971  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:25.971  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.971  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:25.973  5603  5650 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 16:20:25.973  5603  5650 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 16:20:25.973  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 16:20:25.974  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:20:25.974  5603  5650 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 16:20:25.974  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:25.974  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:25.974  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:25.974  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:20:25.974  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:25.974  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:25.974  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.974  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:25.974  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:25.975  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.975  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:25.977  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.978  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.978  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.978  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:25.978  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:25.978  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.978  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:25.985  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:20:25.986  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:25.986  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:25.986  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:25.986  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:25.986  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:25.986  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.986  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:25.986  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:20:25.986  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:20:25.986  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.987  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.988  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.988  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.988  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:25.988  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:20:25.988  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.988  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:25.989  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:20:25.989  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:20:25.989  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:20:25.989  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:20:25.989  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:20:25.989  5603  5650 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ba483e not in the list
11-24 16:20:25.989  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.989  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
,11-24 16:20:25.989  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:25.989  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.989  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.990  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.990  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.990  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:20:25.991  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:20:25.991  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 16:20:25.991  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:25.991  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@747d69f not in the list
11-24 16:20:25.992  5603  5650 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-24 16:20:25.992  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 16:20:25.992  5603  5650 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 16:20:25.992  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 16:20:25.992  5603  5650 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 16:20:25.992  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-24 16:20:25.994  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 16:20:25.994  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-24 16:20:25.994  5603  5650 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 16:20:25.994  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 16:20:25.994  5603  5650 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 16:20:25.994  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 16:20:25.994  5603  5650 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 16:20:25.994  5603  5650 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 16:20:25.995  5603  5650 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 16:20:25.995  5603  5650 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,11-24 16:20:25.996  5603  5650 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 16:20:25.996  5603  5650 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 16:20:25.996  5603  5650 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 16:20:25.996  5603  5650 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 16:20:25.997  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:20:25.997  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@437401c added. We now have 3 listener(s)
11-24 16:20:25.998  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:20:26.000  5603  5650 D BluetoothAdapter: enable(): BT is already enabled..!
,11-24 16:20:26.000   928   939 D WifiService: setWifiEnabled: true pid=5603, uid=10077
11-24 16:20:26.000   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:20:26.049  4654  4849 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 16:20:26.049  4654  4863 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-24 16:20:26.050  5603  5673 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-24 16:20:26.050  5603  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 16:20:26.050  5603  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-24 16:20:26.469  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:20:27.105   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:28.106   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:29.107   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:29.128   928  2975 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 16:20:30.108   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:31.005   928  5356 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:20:31.006  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 16:20:31.006  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b70425 added. We now have 4 listener(s)
,11-24 16:20:31.006  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:20:31.019  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:31.020  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b70425 removed from the list
11-24 16:20:31.020  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:31.022  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 16:20:31.022  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4ce39fa added. We now have 4 listener(s)
11-24 16:20:31.023  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:20:31.027  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:31.027  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4ce39fa removed from the list
11-24 16:20:31.027  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:31.029  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:20:31.029  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d50bab added. We now have 4 listener(s)
,11-24 16:20:31.029  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:20:31.035   928  3847 D WifiService: setWifiEnabled: false pid=5603, uid=10077
,11-24 16:20:31.035   928  3847 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:20:31.043   928  2975 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 16:20:31.043   928  2975 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 16:20:31.043   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 16:20:31.043   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 16:20:31.051  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 16:20:31.052  4654  4712 D BluetoothAdapterState: Current state: ON, message: 23,
,11-24 16:20:31.053  4654  4712 D BluetoothAdapterProperties: Setting state to 13
11-24 16:20:31.053  4654  4712 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 16:20:31.053  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-24 16:20:31.054  4654  4712 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 16:20:31.055  4654  4712 I BluetoothAdapterState: Entering PendingCommandState
11-24 16:20:31.060  4654  4654 D BluetoothMapService: onReceive
11-24 16:20:31.060  4654  4654 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 16:20:31.060  4654  4654 D BluetoothMapService: STATE_TURNING_OFF
,11-24 16:20:31.065  4654  4654 D BluetoothMapService: MAP Service closeService in
11-24 16:20:31.066  4654  4654 D BluetoothMapMasInstance0: MAP Service shutdown
,11-24 16:20:31.066  4654  4654 D ObexServerSockets0: shutdown(block = true)
11-24 16:20:31.067  4654  4654 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 16:20:31.067  4654  4875 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-24 16:20:31.068  4654  4654 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 16:20:31.068  4654  4863 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,11-24 16:20:31.068  4654  4876 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 16:20:31.069  4654  4654 I BtOppRfcommListener: stopping Accept Thread
11-24 16:20:31.070  4654  5287 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 16:20:31.070   928  5357 D DhcpClient: Clearing IP address
11-24 16:20:31.070   510   922 D CommandListener: Clearing all IP addresses on wlan0
11-24 16:20:31.070  4654  5287 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 16:20:31.078   510   922 D CommandListener: Setting iface cfg
,11-24 16:20:31.079  3587  5410 V NativeCrypto: Read error: ssl=0x7f6f149380: I/O error during system call, Connection timed out
11-24 16:20:31.081  3587  5410 V NativeCrypto: SSL shutdown failed: ssl=0x7f6f149380: I/O error during system call, Broken pipe
11-24 16:20:31.083   928  5358 D DhcpClient: Receive thread stopped
11-24 16:20:31.084   928  3150 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-24 16:20:31.085   928  5355 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-24 16:20:31.086   928   941 I ActivityManager: Start proc 5679:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-24 16:20:31.086  4654  4719 D BluetoothAdapterProperties: Scan Mode:20
11-24 16:20:31.086  4654  4712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 16:20:31.090   928  5355 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-24 16:20:31.092  4654  4654 D HeadsetService: Received stop request...Stopping profile...
11-24 16:20:31.092   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-24 16:20:31.093   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 16:20:31.094   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 16:20:31.096   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 16:20:31.100  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:20:31.100  5603  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 16:20:31.100  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:31.100  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:31.100  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:31.100  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:20:31.100  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:20:31.100  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:20:31.100  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:20:31.100  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 16:20:31.100   617   617 E Parcel  : Reading a NULL string not supported here.
11-24 16:20:31.101   928   928 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:31.101  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:31.101  3144  3157 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:31.101  5603  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:20:31.101  5603  5650 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 16:20:31.101   928   928 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:31.102   928   928 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:31.100   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 16:20:31.102  3144  3144 D HeadsetProfile: Bluetooth service disconnected
11-24 16:20:31.104  3815  3829 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:31.104   928   928 D RttService: SCAN_AVAILABLE : 1
11-24 16:20:31.104   928  3085 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 16:20:31.105  4654  4654 D A2dpService: Received stop request...Stopping profile...
11-24 16:20:31.106  4654  4868 D A2dpStateMachine: Exit Disconnected: -1
11-24 16:20:31.106  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:31.106  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:20:31.106  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:31.106  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:31.106  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:31.106  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:20:31.106  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:20:31.106  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:20:31.106  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:20:31.106  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 16:20:31.107   928   928 D BluetoothA2dp: Proxy object disconnected
,11-24 16:20:31.108  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:20:31.108  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:20:31.109   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:31.110   928  2977 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-24 16:20:31.114  4654  4654 D HidService: Received stop request...Stopping profile...
,11-24 16:20:31.114  4654  4654 D HidService: Stopping Bluetooth HidService
11-24 16:20:31.115  4654  4654 D HealthService: Received stop request...Stopping profile...
11-24 16:20:31.116  3770  3891 W QCNEJ   : |CORE| network lost: 100
11-24 16:20:31.117  3770  3891 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 16:20:31.117  3144  3144 D BluetoothA2dp: Proxy object disconnected
,11-24 16:20:31.117  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:20:31.117  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:31.118  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:31.118  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:31.118  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:31.119  3144  3144 D BluetoothInputDevice: Proxy object disconnected
11-24 16:20:31.119  3144  3144 D HidProfile: Bluetooth service disconnected
11-24 16:20:31.120  4654  4654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 16:20:31.120  4654  4654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 16:20:31.120  4654  4849 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:31.120  4654  4849 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:31.120  4654  4849 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:31.121  4654  4719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 16:20:31.121  4654  4719 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 16:20:31.121  4654  4654 D PanService: Received stop request...Stopping profile...
11-24 16:20:31.123  4654  4654 D BluetoothMapService: Received stop request...Stopping profile...
11-24 16:20:31.123  4654  4654 D BluetoothMapService: stop()
11-24 16:20:31.123  4654  4654 D BluetoothMapAppObserver: deinitObservers()
,11-24 16:20:31.123  4654  4654 D BluetoothMapAppObserver: removeReceiver()
,11-24 16:20:31.127  4654  4654 D SapService: Received stop request...Stopping profile...
11-24 16:20:31.127  4654  4654 V SapService: stop()
11-24 16:20:31.128  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:31.128  4654  4654 V BluetoothAdapterState: isTurningOn()=false
,11-24 16:20:31.129  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 16:20:31.129  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:31.130  4654  4849 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:31.130  4654  4654 V BluetoothAdapterState: isTurningOff()=true
,11-24 16:20:31.130  4654  4654 V BluetoothAdapterState: isTurningOn()=false
,11-24 16:20:31.130  4654  4849 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 16:20:31.130  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 16:20:31.130  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:31.130  4654  4654 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 16:20:31.130  4654  4654 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-24 16:20:31.130  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:31.131  4654  4654 V BluetoothAdapterState: isTurningOn()=false
,11-24 16:20:31.131  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 16:20:31.131  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:31.131  4654  4654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 16:20:31.131  3144  3144 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 16:20:31.131  3144  3144 D PanProfile: Bluetooth service disconnected
11-24 16:20:31.131  3144  3144 D BluetoothMap: Proxy object disconnected
11-24 16:20:31.131  3144  3144 D MapProfile: Bluetooth service disconnected
11-24 16:20:31.131  4654  4654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 16:20:31.131  4654  4719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 16:20:31.131  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:31.131  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:31.131  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:31.131  4654  4719 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 16:20:31.131  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:20:31.132  4654  4849 W bt_l2cap: btif_in_execute_service_requestor deregistration
11-24 16:20:31.132  4654  4719 E bt_btif : L2CAP - PSM: 0x0017 not found for deregistration
11-24 16:20:31.132  4654  4849 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-24 16:20:31.132  4654  4849 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 16:20:31.132  4654  4849 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 16:20:31.132  4654  4654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 16:20:31.132  4654  4654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 16:20:31.132  4654  4654 D BluetoothMapService: MAP Service closeService in
11-24 16:20:31.133  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:31.133  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:31.133  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:31.133  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:31.133  4654  4654 D BluetoothMapService: cleanup()
11-24 16:20:31.133  4654  4654 D BluetoothMapService: MAP Service closeService in
11-24 16:20:31.133  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:31.133  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:31.133  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:31.133  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:31.134  4654  4712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 16:20:31.134  4654  4712 D BluetoothAdapterProperties: Setting state to 15
11-24 16:20:31.134  4654  4712 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 16:20:31.134  4654  4712 I BluetoothAdapterState: Entering BleOnState
11-24 16:20:31.134  3144  3996 D BluetoothMap: onBluetoothStateChange: up=false
11-24 16:20:31.135  3144  3158 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 16:20:31.136   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:20:31.136   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 16:20:31.136  3815  3827 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:20:31.136   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:20:31.136   928  2975 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 16:20:31.137  3144  3157 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 16:20:31.137  3144  3996 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 16:20:31.138  3144  3158 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:20:31.139   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:20:31.139  3144  3157 D BluetoothPan: onBluetoothStateChange on: false
11-24 16:20:31.140  4654  4712 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 16:20:31.140  4654  4712 D BluetoothAdapterProperties: Setting state to 16
11-24 16:20:31.140  4654  4712 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 16:20:31.141  4654  4712 D BluetoothAdapterProperties: onBleDisable
11-24 16:20:31.141  4654  4712 I BluetoothAdapterState: Entering PendingCommandState
11-24 16:20:31.141  4654  4713 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 16:20:31.142  4654  4719 D BluetoothAdapterProperties: Scan Mode:20
11-24 16:20:31.143   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 16:20:31.144  4654  4849 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 16:20:31.144  4654  4849 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:31.144  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:31.144  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:20:31.144  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:31.144  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:31.144  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:31.144  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:20:31.144  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:20:31.144  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:20:31.144  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:20:31.144  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:20:31.148  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:20:31.148   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 16:20:31.158  5679  5679 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-24 16:20:31.174   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 16:20:31.174   510   922 D CommandListener: Clearing all IP addresses on wlan0
11-24 16:20:31.175   510   922 D TetherController: Setting IP forward enable = 0
11-24 16:20:31.176   928  2977 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 16:20:31.176   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 16:20:31.176  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 16:20:31.177   928   945 D Tethering: MasterInitialState.processMessage what=3
11-24 16:20:31.181  5245  5245 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dd54529 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-24 16:20:31.182  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:20:31.186  3975  3975 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-24 16:20:31.187  5031  5055 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 16:20:31.187  5031  5055 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 16:20:31.187  5031  5055 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 16:20:31.187  5031  5055 E SarControlService: no key has been found,reset the power
11-24 16:20:31.188  5031  5065 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 16:20:31.188  5031  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 16:20:31.188  5031  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 16:20:31.188  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:20:31.188  5056  5056 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 16:20:31.190  5031  5065 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 16:20:31.190  5031  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 16:20:31.190  5031  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 16:20:31.191  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:20:31.192  5056  5056 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 16:20:31.194  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6aa7f97 HexData = [00000000ea03000000000000ffffffff]
11-24 16:20:31.194  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:20:31.194  5056  5070 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 16:20:31.195  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 16:20:31.195  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 16:20:31.200   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee08808:true
11-24 16:20:31.200  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:20:31.203  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6aa7f97 HexData = [00000000eb03000000000000ffffffff]
,11-24 16:20:31.203  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:20:31.203  5056  5070 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 16:20:31.204  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 16:20:31.204  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 16:20:31.215   928  3883 I ActivityManager: Start proc 5705:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 16:20:31.224  5679  5679 D LocalBluetoothProfileManager: Adding local MAP profile
11-24 16:20:31.226  5679  5679 D BluetoothMap: Create BluetoothMap proxy object
,11-24 16:20:31.230   510   922 E Netd    : netlink response contains error (No such file or directory)
,11-24 16:20:31.232   928  2977 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 16:20:31.232   928  2975 D DhcpClient: doQuit
,11-24 16:20:31.233   928  2975 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 16:20:31.233   928  5357 D DhcpClient: onQuitting
11-24 16:20:31.234  3449  3449 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 16:20:31.239  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:20:31.239  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:20:31.239  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:31.239  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:31.239  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:20:31.239  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:20:31.239  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:20:31.239  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:20:31.239  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:20:31.239  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:20:31.240  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:31.240  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:20:31.245  5679  5679 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 16:20:31.250  3449  3449 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 16:20:31.254  3449  3449 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 16:20:31.257  5705  5705 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-24 16:20:31.269  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,11-24 16:20:31.272   928   939 I ActivityManager: Killing 5104:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-24 16:20:31.288  3449  3449 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 16:20:31.290  3449  3449 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 16:20:31.349  4654  4719 I bt_hci  : shut_down
,11-24 16:20:31.353  4654  4733 D bt_hwcfg: hw_epilog_process
,11-24 16:20:31.353  4654  4733 I bt_vendor: low_power_mode_cb
,11-24 16:20:31.355  4654  4733 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 16:20:31.355  4654  4733 I bt_vendor: epilog_cb
,11-24 16:20:31.355  4654  4733 I bt_hci  : epilog_finished_callback
11-24 16:20:31.357  4654  4719 I bt_hci_h4: hal_close
11-24 16:20:31.358  4654  4719 I bt_userial_vendor: device fd = 54 close
,11-24 16:20:31.393  5006  5006 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 16:20:31.393   928  2975 D wifi    : In wifi stop Hal
11-24 16:20:31.393   928  2975 D wifi    : halHandle = 0x7f5c96fb80, mVM = 0x7f78fcd140, mCls = 0x100a02
11-24 16:20:31.393   928  3448 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 16:20:31.393   928  3448 D WifiHAL : Got a signal to exit!!!
11-24 16:20:31.393   928  3448 I WifiHAL : Exit wifi_event_loop
11-24 16:20:31.394   928  2975 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 16:20:31.394   928  2975 E WifiHAL : Event processing terminated
11-24 16:20:31.394   928  2975 D wifi    : In wifi cleaned up handler
,11-24 16:20:31.394   928  2975 I WifiHAL : Internal cleanup completed
11-24 16:20:31.395  4048  4218 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 16:20:31.396  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:31.416   928  3448 D wifi    : set interface wlan0 flags (DOWN)
,11-24 16:20:31.416   928  2975 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 16:20:31.464  4654  4713 D bt_stack_manager: event_shut_down_stack finished.
,11-24 16:20:31.465  4654  4712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 16:20:31.466  4654  4712 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 16:20:31.466  4654  4654 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 16:20:31.467  4654  4654 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 16:20:31.467  4654  4654 D BtGatt.GattService: stop()
11-24 16:20:31.467  4654  4654 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 16:20:31.469  4654  4654 V BluetoothAdapterState: isTurningOff()=false
11-24 16:20:31.469  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:31.469  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:31.469  4654  4654 V BluetoothAdapterState: isBleTurningOff()=true
11-24 16:20:31.469  4654  4712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 16:20:31.469  4654  4712 D BluetoothAdapterProperties: Setting state to 10
11-24 16:20:31.469  4654  4712 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 16:20:31.470  4654  4712 I BluetoothAdapterState: Entering OffState
,11-24 16:20:31.470   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-24 16:20:31.476  4654  4654 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 16:20:31.476  4654  4654 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 16:20:31.476  4654  4654 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 16:20:31.478  4654  4713 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 16:20:31.485  4654  4654 I art     : System.exit called, status: 0
,11-24 16:20:31.485  4654  4654 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 16:20:31.539  5705  5705 D StrictMode: StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 16:20:31.539  5705  5705 D StrictMode: StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:20:31.539  5705  5705 D StrictMode: StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:20:31.539  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:20:31.540  5705  5705 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:20:31.540  5705  5705 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:20:31.540  5705  5705 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:20:31.540  5705  5705 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:20:31.540  5705  5705 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 16:20:31.540  5705  5705 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 16:20:31.547   928   939 I ActivityManager: Process com.android.bluetooth (pid 4654) has died
11-24 16:20:31.553  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 16:20:31.567   928  3826 I ActivityManager: Start proc 5739:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
11-24 16:20:31.568  5679  5679 D DockEventReceiver: finishStartingService: stopping service
11-24 16:20:31.570   928  3847 I ActivityManager: Killing 5430:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-24 16:20:31.618   928   945 D Tethering: InitialState.processMessage what=4
11-24 16:20:31.621   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 16:20:31.648  5739  5739 D AdapterServiceConfig: Adding HeadsetService
,11-24 16:20:31.649  5739  5739 D AdapterServiceConfig: Adding A2dpService
11-24 16:20:31.649  5739  5739 D AdapterServiceConfig: Adding HidService
11-24 16:20:31.649  5739  5739 D AdapterServiceConfig: Adding HealthService
11-24 16:20:31.649  5739  5739 D AdapterServiceConfig: Adding PanService
11-24 16:20:31.649  5739  5739 D AdapterServiceConfig: Adding GattService
,11-24 16:20:31.649  5739  5739 D AdapterServiceConfig: Adding BluetoothMapService
11-24 16:20:31.650  5739  5739 D AdapterServiceConfig: Adding SapService
11-24 16:20:31.651   928  3828 I ActivityManager: Killing 5414:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-24 16:20:31.674  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:20:31.685  3846  3846 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 16:20:31.689  3846  3846 D SystemUpdateService: onCreate
,11-24 16:20:31.696  3846  3846 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 16:20:31.705  3846  3846 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 16:20:31.709  3846  5379 I iu.UploadsManager: num queued entries: 0
,11-24 16:20:31.709  3846  5379 I iu.UploadsManager: num updated entries: 0
11-24 16:20:31.710  3846  5379 I iu.SyncManager: NEXT; no task
,11-24 16:20:31.712  3846  3846 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 16:20:31.714  3846  3846 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 16:20:31.715  3846  5751 I SystemUpdateService: active receiver: enabled
,11-24 16:20:31.722  3846  5751 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 16:20:31.726   928  3842 I ActivityManager: Start proc 5753:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-24 16:20:31.739  3846  5751 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 16:20:31.740  3846  5751 I SystemUpdateService: now status is 0 (complete)
,11-24 16:20:31.740  3846  5751 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-24 16:20:31.744  3846  5751 I SystemUpdateService: file has been verified
11-24 16:20:31.744  3846  5751 I SystemUpdateService: OTA package size = 21989297
,11-24 16:20:31.758  5753  5753 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 16:20:31.767  5753  5753 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 16:20:31.776  5753  5753 D SprintDMHelper: simOperator: 
11-24 16:20:31.776  5753  5753 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 16:20:31.781  3846  5751 I SystemUpdateService: showing system update notification
,11-24 16:20:31.789   928  3150 I ActivityManager: Start proc 5765:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-24 16:20:31.809   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 16:20:31.813  3846  3846 D SystemUpdateService: onDestroy
,11-24 16:20:31.815   928  3872 I ActivityManager: Killing 5245:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 16:20:31.895  5006  5779 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 16:20:31.903   928   938 I ActivityManager: Start proc 5780:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-24 16:20:31.906   928  3842 I ActivityManager: Killing 3908:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 16:20:31.957  5780  5780 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-24 16:20:32.043  5705  5729 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 16:20:32.109   619   619 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 16:20:32.137   928  3601 I ActivityManager: Killing 5474:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-24 16:20:32.137   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@730598b:true
,11-24 16:20:32.185   928  3564 I ActivityManager: Start proc 5794:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 16:20:32.217  5794  5794 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 16:20:32.224   510   922 D TetherController: Setting IP forward enable = 0
11-24 16:20:32.224   928  3826 I ActivityManager: Killing 3406:android.process.acore/u0a2 (adj 15): empty #17
,11-24 16:20:36.104   928  3872 D WifiService: setWifiEnabled: true pid=5603, uid=10077
,11-24 16:20:36.104   928  3872 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:20:36.114   510   922 D SoftapController: Softap fwReload - Ok
,11-24 16:20:36.118   510   922 D CommandListener: Setting iface cfg
,11-24 16:20:36.119   510   922 D CommandListener: Trying to bring down wlan0
11-24 16:20:36.120   510   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 16:20:36.124   928  2975 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 16:20:36.693   928  2975 D wifi    : set interface wlan0 flags (UP)
,11-24 16:20:36.696   928  2975 I WifiHAL : Initializing wifi
11-24 16:20:36.696   928  2975 I WifiHAL : Creating socket
11-24 16:20:36.697   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-24 16:20:36.700   928  2975 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-24 16:20:36.700   928  2975 D wifi    : Did set static halHandle = 0x7f5c96fb80
11-24 16:20:36.700   928  2975 D wifi    : halHandle = 0x7f5c96fb80, mVM = 0x7f78fcd140, mCls = 0x199e
11-24 16:20:36.702   928  2975 D wifi    : array field set
11-24 16:20:36.702   928  2975 I WifiNative-HAL: interface[0] = wlan0
11-24 16:20:36.705   928  5819 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547014245248
11-24 16:20:36.705   928  5819 D wifi    : waitForHalEvents called, vm = 0x7f78fcd140, obj = 0x199e, env = 0x7f60a8a100
,11-24 16:20:36.763  5820  5820 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 16:20:36.806   928  2975 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-24 16:20:36.809  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:36.815  5820  5820 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 16:20:36.863  5820  5820 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 16:20:36.863  5820  5820 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 16:20:36.883   928  2975 D WifiConfigStore: Loading config and enabling all networks 
,11-24 16:20:36.883  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:36.884  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:20:36.884  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:36.884  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:36.884  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:36.884  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:20:36.884  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:20:36.884  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:20:36.884  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:20:36.884  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:20:36.884  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:20:36.884  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:20:36.913   928  2975 D WifiConfigStore: loaded 0 passpoint configs
,11-24 16:20:36.913   928  2975 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 16:20:36.914   928  2975 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-24 16:20:36.914   928  2975 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 16:20:36.914   928  2975 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
11-24 16:20:36.915   928  2975 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 16:20:36.915   928  2975 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 16:20:36.916   928  2975 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 16:20:36.916   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 16:20:36.916   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-24 16:20:36.916   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 16:20:36.916   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 16:20:36.916   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 16:20:36.918   928  2975 D WifiNative-HAL: Setting external_sim to 1
,11-24 16:20:36.918   928  2975 D wifi    : setting dfs flag to true, 0x7f61a797e0
11-24 16:20:36.919   928  2975 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 16:20:36.919  5006  5006 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 16:20:36.919   928  2975 D wifi    : setting scan oui 0x7f61a797e0
11-24 16:20:36.919   928  2975 D WifiHAL : Sending mac address OUI
,11-24 16:20:36.922   928  2975 E native  : do suspend false
,11-24 16:20:36.928   928  2975 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 16:20:36.928   928   928 D RttService: SCAN_AVAILABLE : 3
11-24 16:20:36.929   928  3085 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 16:20:36.934   510   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 16:20:36.935   510   922 D CommandListener: Setting iface cfg
,11-24 16:20:36.937   928  2967 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-24 16:20:36.937   928  2967 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 16:20:36.944   928  2967 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 16:20:36.944   928  2967 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 16:20:36.949   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128768 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,11-24 16:20:37.110   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:38.111   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:39.112   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:40.021  5820  5820 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 16:20:40.035  5820  5820 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 16:20:40.078   928  2975 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 16:20:40.079   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 16:20:40.079   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 16:20:40.091   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 16:20:40.112   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:40.127   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 16:20:40.132  5820  5820 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 16:20:40.558  5820  5820 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 16:20:40.595  5820  5820 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 16:20:40.596  5820  5820 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 16:20:40.605   928  2975 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 16:20:40.605   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 16:20:40.605   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 16:20:40.623   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 16:20:40.635   510   922 D CommandListener: Setting iface cfg
,11-24 16:20:40.640   928  2975 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 16:20:40.645   928  5826 D DhcpClient: Receive thread started
,11-24 16:20:40.653   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 16:20:40.653   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 16:20:40.653   928  2977 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 16:20:40.734   928  2975 E native  : do suspend false
,11-24 16:20:40.744   928  5825 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 16:20:40.756   928  5826 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
,11-24 16:20:40.757   928  5825 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
,11-24 16:20:40.759   928  5825 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 16:20:40.778   928  5826 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 16:20:40.779   928  5825 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-24 16:20:40.782   510   922 D CommandListener: Setting iface cfg
11-24 16:20:40.787   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 16:20:40.791   928  5825 D DhcpClient: Scheduling renewal in 86399s
,11-24 16:20:40.801   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 16:20:40.802   928  2975 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 16:20:40.803   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 16:20:40.808   928  2977 D ConnectivityService: Adding iface wlan0 to network 101
,11-24 16:20:40.816   928  2975 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 16:20:40.858   928  2977 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-24 16:20:40.858   928  2977 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 16:20:40.860   928  2977 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 16:20:40.866   928  2977 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 16:20:40.868   928  2977 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 16:20:40.875   928  2977 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 16:20:40.880   928  2977 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 16:20:40.880   928  2977 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 16:20:40.880   928  2977 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 16:20:40.880   928  2977 D ConnectivityService:    accepting network in place of null
11-24 16:20:40.880   928  2975 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-24 16:20:40.880   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 16:20:40.881   928  2977 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 16:20:40.898   928  5824 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:20:40.905   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 16:20:40.926   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 16:20:40.929   928  2977 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 16:20:40.929   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 16:20:40.929  3770  3891 W QCNEJ   : |CORE| network available: 101
11-24 16:20:40.930   928  2977 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 16:20:40.931   928   945 D Tethering: MasterInitialState.processMessage what=3
11-24 16:20:40.932  3770  3891 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 16:20:40.935  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:40.935  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:20:40.935  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:40.935  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:40.935  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:40.935  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:20:40.935  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:20:40.935  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:20:40.935  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:20:40.935  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 16:20:40.935  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:20:40.935  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 16:20:40.938  3770  3891 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 16:20:40.938  3770  3891 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 16:20:40.945  5031  5055 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 16:20:40.945  5031  5055 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 16:20:40.946  5031  5055 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 16:20:40.946  5031  5055 E SarControlService: no key has been found,reset the power
11-24 16:20:40.946  5031  5065 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 16:20:40.946  5031  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 16:20:40.946  5031  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 16:20:40.946  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:20:40.946  5056  5056 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 16:20:40.947  5031  5065 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-24 16:20:40.948  5031  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 16:20:40.948  5031  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 16:20:40.949  3975  3975 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 16:20:40.949  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:20:40.950  5056  5056 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 16:20:40.956  3846  3846 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 16:20:40.957  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6aa7f97 HexData = [00000000ec03000000000000ffffffff]
11-24 16:20:40.957  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:20:40.957  5056  5070 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 16:20:40.959  3846  3846 D SystemUpdateService: onCreate
11-24 16:20:40.960  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 16:20:40.960  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 16:20:40.966  3846  3846 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 16:20:40.967  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6aa7f97 HexData = [00000000ed03000000000000ffffffff]
11-24 16:20:40.968  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:20:40.968  5056  5070 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-24 16:20:40.968  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 16:20:40.969  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 16:20:40.972   928  5823 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 16:20:40.980  3846  3846 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 16:20:40.989  3846  5379 I iu.UploadsManager: num queued entries: 0
,11-24 16:20:40.989  3846  5379 I iu.UploadsManager: num updated entries: 0
11-24 16:20:40.990  3846  5379 I iu.SyncManager: NEXT; no task
,11-24 16:20:40.991  3846  5836 I SystemUpdateService: active receiver: enabled
,11-24 16:20:40.993  3846  3846 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 16:20:40.994  3846  3846 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 16:20:40.996  5753  5753 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 16:20:40.999  5753  5753 D SprintDMHelper: simOperator: 
11-24 16:20:41.000  5753  5753 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 16:20:41.025   928  5823 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 15:20:40 GMT], X-Android-Received-Millis=[1480000841024], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480000840999]}
,11-24 16:20:41.026   928  2977 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 16:20:41.026   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-24 16:20:41.026   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 16:20:41.027   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 16:20:41.036  3846  5836 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 16:20:41.045  3846  5836 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 16:20:41.045  3846  5836 I SystemUpdateService: now status is 0 (complete)
11-24 16:20:41.045  3846  5836 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 16:20:41.045  3846  5836 I SystemUpdateService: file has been verified
11-24 16:20:41.046  3846  5836 I SystemUpdateService: OTA package size = 21989297
,11-24 16:20:41.051  3846  5836 I SystemUpdateService: showing system update notification
,11-24 16:20:41.064   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 16:20:41.065  3846  3846 D SystemUpdateService: onDestroy
,11-24 16:20:41.108  5006  5840 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 16:20:41.112   928  3847 D WifiService: setWifiEnabled: false pid=5603, uid=10077
,11-24 16:20:41.112   928  3847 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-24 16:20:41.113   928  2975 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 16:20:41.113   928  2975 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 16:20:41.113   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 16:20:41.113   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 16:20:41.114   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:41.121   928  5825 D DhcpClient: Clearing IP address
11-24 16:20:41.122   510   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 16:20:41.123   510   922 D CommandListener: Setting iface cfg
,11-24 16:20:41.129  3587  5846 V NativeCrypto: Read error: ssl=0x7f5d7f8300: I/O error during system call, Connection timed out
,11-24 16:20:41.130  3587  5846 V NativeCrypto: SSL shutdown failed: ssl=0x7f5d7f8300: I/O error during system call, Broken pipe
,11-24 16:20:41.134   928  5826 D DhcpClient: Receive thread stopped
,11-24 16:20:41.136   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 16:20:41.136   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-24 16:20:41.137   617   617 E Parcel  : Reading a NULL string not supported here.
,11-24 16:20:41.143   928  2977 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-24 16:20:41.148  3770  3891 W QCNEJ   : |CORE| network lost: 101
,11-24 16:20:41.149  3770  3891 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 16:20:41.149   928   928 D RttService: SCAN_AVAILABLE : 1
,11-24 16:20:41.150   928  3085 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 16:20:41.152   928  2975 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 16:20:41.155   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 16:20:41.166   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 16:20:41.184   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 16:20:41.184   928  2977 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 16:20:41.185   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 16:20:41.185   510   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 16:20:41.188  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:20:41.188  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:20:41.188  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:41.188  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:41.188  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:20:41.188  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:20:41.188  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:20:41.188  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:20:41.188  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:20:41.188  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:20:41.188   928   945 D Tethering: MasterInitialState.processMessage what=3
11-24 16:20:41.188  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:41.188  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:20:41.193  3975  3975 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 16:20:41.196  3846  3846 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 16:20:41.198  5031  5055 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 16:20:41.198  5031  5055 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 16:20:41.198  5031  5055 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-24 16:20:41.198  5031  5055 E SarControlService: no key has been found,reset the power
11-24 16:20:41.199  5031  5065 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 16:20:41.199  5031  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 16:20:41.199  5031  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 16:20:41.199  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:20:41.199  5056  5056 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 16:20:41.201  5031  5065 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 16:20:41.201  5031  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 16:20:41.201  5031  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 16:20:41.201  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:20:41.201  5056  5056 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 16:20:41.205  3846  3846 D SystemUpdateService: onCreate
,11-24 16:20:41.206  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6aa7f97 HexData = [00000000ee03000000000000ffffffff]
11-24 16:20:41.206  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:20:41.207  5056  5070 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-24 16:20:41.207  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 16:20:41.207  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 16:20:41.207  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6aa7f97 HexData = [00000000ef03000000000000ffffffff]
11-24 16:20:41.207  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:20:41.208  5056  5070 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
,11-24 16:20:41.208  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 16:20:41.208  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 16:20:41.211  3846  3846 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 16:20:41.214  3846  5856 I SystemUpdateService: active receiver: enabled
,11-24 16:20:41.218  3846  3846 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 16:20:41.223  3846  5379 I iu.UploadsManager: num queued entries: 0
,11-24 16:20:41.223  3846  5379 I iu.UploadsManager: num updated entries: 0
11-24 16:20:41.224  3846  5379 I iu.SyncManager: NEXT; no task
,11-24 16:20:41.226  3846  3846 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 16:20:41.227  3846  3846 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 16:20:41.229  5753  5753 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 16:20:41.233  5753  5753 D SprintDMHelper: simOperator: 
11-24 16:20:41.233  5753  5753 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 16:20:41.237   510   922 E Netd    : netlink response contains error (No such file or directory)
,11-24 16:20:41.238   928  2977 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-24 16:20:41.239  3846  5856 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-24 16:20:41.240   928  2975 D DhcpClient: doQuit
11-24 16:20:41.240   928  2975 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 16:20:41.240   928  5825 D DhcpClient: onQuitting
11-24 16:20:41.241  5820  5820 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 16:20:41.245  5006  5860 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 16:20:41.247  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 16:20:41.247  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:20:41.247  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:41.247  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:41.247  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:20:41.247  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:20:41.247  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:20:41.247  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:20:41.247  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:20:41.247  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:20:41.247  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:41.248  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:20:41.248  3846  5856 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-24 16:20:41.248  3846  5856 I SystemUpdateService: now status is 0 (complete)
11-24 16:20:41.248  3846  5856 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-24 16:20:41.248  3846  5856 I SystemUpdateService: file has been verified
11-24 16:20:41.249  3846  5856 I SystemUpdateService: OTA package size = 21989297
,11-24 16:20:41.252  5820  5820 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 16:20:41.255  5820  5820 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 16:20:41.263  3846  5856 I SystemUpdateService: showing system update notification
,11-24 16:20:41.274   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 16:20:41.275  3846  3846 D SystemUpdateService: onDestroy
,11-24 16:20:41.281  5820  5820 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 16:20:41.292  5820  5820 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 16:20:41.394   928  2975 D wifi    : In wifi stop Hal
,11-24 16:20:41.394   928  2975 D wifi    : halHandle = 0x7f5c96fb80, mVM = 0x7f78fcd140, mCls = 0x199e
,11-24 16:20:41.394   928  5819 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-24 16:20:41.395   928  5819 D WifiHAL : Got a signal to exit!!!
11-24 16:20:41.395   928  5819 I WifiHAL : Exit wifi_event_loop
11-24 16:20:41.397   928  2975 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 16:20:41.397   928  2975 E WifiHAL : Event processing terminated
11-24 16:20:41.397   928  2975 D wifi    : In wifi cleaned up handler
,11-24 16:20:41.397   928  2975 I WifiHAL : Internal cleanup completed
11-24 16:20:41.398  5006  5006 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 16:20:41.401  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:41.404  4048  4218 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 16:20:41.423   928  5819 D wifi    : set interface wlan0 flags (DOWN)
,11-24 16:20:41.424   928  2975 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 16:20:41.631   928   945 D Tethering: InitialState.processMessage what=4
,11-24 16:20:41.640   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 16:20:41.931   928  2977 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 16:20:42.114   619   619 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 16:20:46.144   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a7d9c1f:true
,11-24 16:20:46.145  5739  5739 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 16:20:46.149  5739  5739 I bt_bluedroid: init
,11-24 16:20:46.149  5739  5862 I BluetoothAdapterState: Entering OffState
,11-24 16:20:46.151  5739  5863 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 16:20:46.152  5739  5863 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 16:20:46.152  5739  5863 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-24 16:20:46.152  5739  5863 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-24 16:20:46.153  5739  5739 I bt_bluedroid: get_profile_interface socket
11-24 16:20:46.155  5739  5739 I bt_bluedroid: get_profile_interface sdp
,11-24 16:20:46.155  5739  5866 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 16:20:46.157  5739  5866 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 16:20:46.160  5739  5750 I bt_bluedroid: config_hci_snoop_log
11-24 16:20:46.162   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 16:20:46.166  5739  5862 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 16:20:46.167  5739  5862 D BluetoothAdapterProperties: Setting state to 14
11-24 16:20:46.167  5739  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-24 16:20:46.168  5739  5862 D BluetoothBondStateMachine: make
,11-24 16:20:46.171  5739  5867 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 16:20:46.174  5739  5862 I BluetoothAdapterState: Entering PendingCommandState
,11-24 16:20:46.175  5739  5739 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 16:20:46.177  5739  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
11-24 16:20:46.178  5739  5739 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 16:20:46.178  5739  5739 D BtGatt.GattService: Received start request. Starting profile...
11-24 16:20:46.178  5739  5739 D BtGatt.GattService: start()
11-24 16:20:46.178  5739  5739 I bt_bluedroid: get_profile_interface gatt
,11-24 16:20:46.179  5739  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:20:46.180  5739  5739 D BtGatt.AdvertiseManager: advertise manager created
,11-24 16:20:46.185  5739  5739 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:20:46.185  5739  5739 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:46.185  5739  5739 V BluetoothAdapterState: isBleTurningOn()=true
11-24 16:20:46.185  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:46.185  5739  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 16:20:46.187  5739  5862 I bt_bluedroid: bt_bluedroid
,11-24 16:20:46.187  5739  5863 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 16:20:46.187  5739  5863 I bt_hci  : start_up
,11-24 16:20:46.193  5739  5863 I bt_vendor: alloc value 0xf3f38871
,11-24 16:20:46.194  5739  5863 I bt_vendor: init
11-24 16:20:46.194  5739  5863 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 16:20:46.194  5739  5863 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 16:20:46.302  5739  5863 D bt_hci  : start_up starting async portion
,11-24 16:20:46.303  5739  5870 I bt_hci  : event_finish_startup
,11-24 16:20:46.303  5739  5870 I bt_hci_h4: hal_open
11-24 16:20:46.303  5739  5870 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-24 16:20:46.301  5871  5871 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-24 16:20:46.306  5739  5870 I bt_userial_vendor: device fd = 54 open
,11-24 16:20:46.320  5739  5870 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 16:20:46.322  5739  5870 D bt_hwcfg: Chipset BCM4358A3
11-24 16:20:46.322  5739  5870 D bt_hwcfg: Target name = [BCM4358A3]
,11-24 16:20:46.322  5739  5870 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 16:20:46.703  5739  5870 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-24 16:20:46.703  5739  5870 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 16:20:46.703  5739  5870 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 16:20:46.837  5739  5870 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 16:20:46.838  5739  5870 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 16:20:46.839  5739  5870 I bt_hwcfg: vendor lib fwcfg completed
11-24 16:20:46.839  5739  5870 I bt_vendor: firmware callback
11-24 16:20:46.839  5739  5870 I bt_hci  : firmware_config_callback
,11-24 16:20:46.848  5739  5873 I bt_btu  : btu_task pending for preload complete event
,11-24 16:20:46.849  5739  5873 I bt_btu_task: Bluetooth chip preload is complete
,11-24 16:20:46.849  5739  5873 I bt_btu  : btu_task received preload complete event
,11-24 16:20:46.855  5739  5873 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 16:20:46.856  5739  5873 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-24 16:20:46.856  5739  5873 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 16:20:46.856  5739  5873 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-24 16:20:46.856  5739  5873 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-24 16:20:46.856  5739  5873 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 16:20:46.856  5739  5873 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 16:20:46.856  5739  5873 I         : BTE_InitTraceLevels -- TRC_BTM
,11-24 16:20:46.856  5739  5873 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 16:20:46.857  5739  5873 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 16:20:46.857  5739  5873 I         : BTE_InitTraceLevels -- TRC_SDP
,11-24 16:20:46.857  5739  5873 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 16:20:46.857  5739  5873 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 16:20:46.857  5739  5873 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 16:20:46.857  5739  5873 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 16:20:46.943  5739  5873 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3eb6549
,11-24 16:20:46.943  5739  5873 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3eb6549 
,11-24 16:20:46.961  5739  5866 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 16:20:46.962  5739  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 16:20:46.963  5739  5866 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 16:20:46.966  5739  5866 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 16:20:46.970  5739  5866 D BluetoothAdapterProperties: Scan Mode:20
11-24 16:20:46.971  5739  5866 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 16:20:46.972  5739  5866 D bt_hci  : do_postload posting postload work item
11-24 16:20:46.972  5739  5870 I bt_hci  : event_postload
11-24 16:20:46.972  5739  5870 I bt_vendor: sco_config_cb
11-24 16:20:46.972  5739  5870 I bt_hci  : sco_config_callback postload finished.
11-24 16:20:46.977  5739  5866 D bt_bte_conf: Device ID record 1 : primary
11-24 16:20:46.977  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:46.977  5739  5866 D bt_bte_conf:   vendorId            = 000f
11-24 16:20:46.977  5739  5866 D bt_bte_conf:   vendorIdSource      = 0001
11-24 16:20:46.978  5739  5866 D bt_bte_conf:   product             = 1200
11-24 16:20:46.978  5739  5866 D bt_bte_conf:   version             = 1436
11-24 16:20:46.978  5739  5866 D bt_bte_conf:   clientExecutableURL = 
11-24 16:20:46.978  5739  5866 D bt_bte_conf:   serviceDescription  = 
,11-24 16:20:46.978  5739  5866 D bt_bte_conf:   documentationURL    = 
11-24 16:20:46.978  5739  5866 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 16:20:46.978  5739  5863 D bt_stack_manager: event_start_up_stack finished
11-24 16:20:46.980  5739  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 16:20:46.980  5739  5862 D BluetoothAdapterProperties: Setting state to 15
,11-24 16:20:46.980  5739  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 16:20:46.980  5739  5870 I bt_vendor: low_power_mode_cb
,11-24 16:20:46.984  5739  5862 I BluetoothAdapterState: Entering BleOnState
,11-24 16:20:46.987  5739  5862 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 16:20:46.987  5739  5862 D BluetoothAdapterProperties: Setting state to 11
11-24 16:20:46.987  5739  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 16:20:46.993  5739  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:20:46.994  5739  5739 D HeadsetService: Received start request. Starting profile...
,11-24 16:20:46.996  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:46.998  5739  5739 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 16:20:46.999  5739  5739 D HeadsetStateMachine: make
,11-24 16:20:47.007  5739  5862 I BluetoothAdapterState: Entering PendingCommandState
,11-24 16:20:47.010  5739  5739 D HeadsetStateMachine: max_hf_connections = 1
,11-24 16:20:47.010  5739  5739 I bt_bluedroid: get_profile_interface handsfree
11-24 16:20:47.010  5739  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 16:20:47.010  5739  5866 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,11-24 16:20:47.014  5739  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
11-24 16:20:47.015  5739  5739 D A2dpService: Received start request. Starting profile...
11-24 16:20:47.015  5739  5739 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 16:20:47.016  5739  5739 I bt_bluedroid: get_profile_interface avrcp
,11-24 16:20:47.022  5739  5739 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-24 16:20:47.022  5739  5739 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 16:20:47.022  5739  5739 D A2dpStateMachine: make
,11-24 16:20:47.023  5739  5739 I bt_bluedroid: get_profile_interface a2dp
,11-24 16:20:47.024  5739  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 16:20:47.025  5739  5881 D A2dpStateMachine: Enter Disconnected: -2
,11-24 16:20:47.026  5739  5739 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 16:20:47.027  5739  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:20:47.029  5679  5679 D BluetoothInputDevice: Proxy object connected
,11-24 16:20:47.029  5739  5739 D HidService: Received start request. Starting profile...
11-24 16:20:47.030  5739  5739 I bt_bluedroid: get_profile_interface hidhost
11-24 16:20:47.030  5739  5866 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e9756d
11-24 16:20:47.031  5739  5739 D HidService: setHidService(): set to: null
11-24 16:20:47.031  5739  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 16:20:47.031  5739  5739 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 16:20:47.032  5739  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
11-24 16:20:47.032  5739  5739 D HealthService: Received start request. Starting profile...
11-24 16:20:47.033  5679  5679 D HidProfile: Bluetooth service connected
11-24 16:20:47.034  5739  5739 I bt_bluedroid: get_profile_interface health
11-24 16:20:47.034  5739  5739 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 16:20:47.035  5739  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
11-24 16:20:47.035  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:20:47.039  5679  5679 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 16:20:47.039  5679  5679 D PanProfile: Bluetooth service connected
11-24 16:20:47.039  5739  5739 D PanService: Received start request. Starting profile...
11-24 16:20:47.039  5739  5739 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 16:20:47.039  5739  5739 I bt_bluedroid: get_profile_interface pan
11-24 16:20:47.040  5739  5866 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-24 16:20:47.042  5739  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:20:47.043  5679  5679 D BluetoothMap: Proxy object connected
,11-24 16:20:47.044  5739  5739 D BluetoothMapService: Received start request. Starting profile...
11-24 16:20:47.044  5739  5739 D BluetoothMapService: start()
,11-24 16:20:47.044  5679  5679 D MapProfile: Bluetooth service connected
11-24 16:20:47.044  5679  5679 D BluetoothMap: getConnectedDevices()
11-24 16:20:47.045  5679  5679 D BluetoothMap: Bluetooth is Not enabled
,11-24 16:20:47.047  5739  5739 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 16:20:47.047  5739  5739 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 16:20:47.047  5739  5739 D BluetoothMapAppObserver: createReceiver()
11-24 16:20:47.049  5739  5739 D BluetoothMapAppObserver: initObservers()
11-24 16:20:47.049  5739  5739 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 16:20:47.054  5739  5739 V SapService: SapBinder()
,11-24 16:20:47.054  5739  5739 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:20:47.055  5739  5739 D SapService: Received start request. Starting profile...
11-24 16:20:47.055  5739  5739 V SapService: start()
,11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isTurningOn()=true
11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:47.058  5739  5879 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isTurningOn()=true
,11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isTurningOff()=false
11-24 16:20:47.058  5739  5739 V BluetoothAdapterState: isTurningOn()=true
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isTurningOff()=false
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isTurningOn()=true
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isTurningOn()=true
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isTurningOn()=true
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:47.059  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:47.060  5739  5739 V BluetoothAdapterState: isTurningOff()=false
11-24 16:20:47.060  5739  5739 V BluetoothAdapterState: isTurningOn()=true
11-24 16:20:47.060  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:47.061  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:47.061  5739  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 16:20:47.061  5739  5862 D BluetoothAdapterProperties: ScanMode =  20
11-24 16:20:47.061  5739  5862 D BluetoothAdapterProperties: State =  11
11-24 16:20:47.061  5739  5862 D BluetoothAdapterProperties: Setting state to 12
11-24 16:20:47.061  5739  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 16:20:47.062  5739  5862 I BluetoothAdapterState: Entering OnState
11-24 16:20:47.062  3144  3157 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 16:20:47.064  3144  3144 D BluetoothMap: Proxy object connected
11-24 16:20:47.064  5679  5690 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 16:20:47.064  3144  3144 D MapProfile: Bluetooth service connected
11-24 16:20:47.064  3144  3144 D BluetoothMap: getConnectedDevices()
,11-24 16:20:47.066  5739  5866 D BluetoothAdapterProperties: Scan Mode:21
11-24 16:20:47.066  5739  5866 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 16:20:47.067  3144  3157 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 16:20:47.067  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 16:20:47.068   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:20:47.068  3144  3144 D BluetoothInputDevice: Proxy object connected
11-24 16:20:47.069  3144  3144 D HidProfile: Bluetooth service connected
11-24 16:20:47.069  5679  5694 D BluetoothPan: onBluetoothStateChange on: true
11-24 16:20:47.069  5679  5690 D BluetoothMap: onBluetoothStateChange: up=true
11-24 16:20:47.069  5679  5694 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 16:20:47.069   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 16:20:47.070  3815  3829 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:20:47.071   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:20:47.071  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:20:47.071  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:47.071  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:47.071  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:20:47.071  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:20:47.071  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:20:47.071  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:20:47.071  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:20:47.071  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 16:20:47.071  3144  3158 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 16:20:47.071   928   928 D BluetoothA2dp: Proxy object connected
11-24 16:20:47.073  3144  3996 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 16:20:47.073  3144  3144 D BluetoothA2dp: Proxy object connected
11-24 16:20:47.074  5739  5739 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 16:20:47.075  3144  3158 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:20:47.075  5739  5739 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 16:20:47.075  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 16:20:47.075   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:20:47.075  3144  3157 D BluetoothPan: onBluetoothStateChange on: true
11-24 16:20:47.077  3144  3144 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 16:20:47.077  3144  3144 D PanProfile: Bluetooth service connected
11-24 16:20:47.078  5739  5739 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:20:47.078   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 16:20:47.079  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 16:20:47.081  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:20:47.081  5739  5739 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:20:47.081  5679  5679 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-24 16:20:47.082  5739  5739 D ObexServerSockets: Succeed to create listening sockets 
11-24 16:20:47.083  5739  5739 D ObexServerSockets0: startAccept()
11-24 16:20:47.083  5739  5739 D ObexServerSockets0: prepareForNewConnect()
11-24 16:20:47.085  5739  5739 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 16:20:47.085  5739  5739 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 16:20:47.085  5739  5739 D BluetoothMapService: onReceive
11-24 16:20:47.085  5739  5739 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 16:20:47.085  5679  5679 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-24 16:20:47.085  5739  5888 D ObexServerSockets0: Accepting socket connection...
11-24 16:20:47.085  5739  5739 D BluetoothMapService: STATE_ON
,11-24 16:20:47.086  5739  5889 D ObexServerSockets0: Accepting socket connection...
11-24 16:20:47.088  5739  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:20:47.090  5739  5890 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-24 16:20:47.090  5739  5890 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 16:20:47.094  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 16:20:47.096  5679  5679 D BluetoothA2dp: Proxy object connected
,11-24 16:20:47.100  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:20:47.107  3144  3144 D BluetoothPbap: Proxy object connected
,11-24 16:20:47.108  3144  3144 D PbapServerProfile: Bluetooth service connected
11-24 16:20:47.108  5679  5679 D DockEventReceiver: finishStartingService: stopping service
11-24 16:20:47.109  5679  5679 D BluetoothPbap: Proxy object connected
11-24 16:20:47.110  5679  5679 D PbapServerProfile: Bluetooth service connected
,11-24 16:20:47.114  5739  5739 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 16:20:47.114  5739  5739 D ObexServerSockets0: prepareForNewConnect()
,11-24 16:20:47.116  5739  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:20:47.129  5739  5898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:20:47.130  5739  5898 I BtOppRfcommListener: Accept thread started.
,11-24 16:20:47.171   928   928 D BluetoothHeadset: Proxy object connected
,11-24 16:20:47.171  3144  3157 D BluetoothHeadset: Proxy object connected
11-24 16:20:47.171  3815  4031 D BluetoothHeadset: Proxy object connected
11-24 16:20:47.171  3144  3144 D HeadsetProfile: Bluetooth service connected
11-24 16:20:47.171   928   928 D BluetoothHeadset: Proxy object connected
11-24 16:20:47.171   928   945 D BluetoothHeadset: Proxy object connected
11-24 16:20:47.171   928   928 D BluetoothHeadset: Proxy object connected
11-24 16:20:47.171  3815  4003 D BluetoothHeadset: Proxy object connected
,11-24 16:20:47.176  3144  3996 D BluetoothHeadset: Proxy object connected
,11-24 16:20:47.176  3144  3144 D HeadsetProfile: Bluetooth service connected
11-24 16:20:47.176   928   945 D BluetoothHeadset: Proxy object connected
,11-24 16:20:47.188  5679  5690 D BluetoothHeadset: Proxy object connected
,11-24 16:20:47.190  5679  5679 D HeadsetProfile: Bluetooth service connected
,11-24 16:20:48.272  3659  3863 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-24 16:20:48.272  3659  3863 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-24 16:20:48.304  3587  3587 I ConfigService: onCreate
,11-24 16:20:48.887   928  2977 D ConnectivityService: handlePromptUnvalidated 101
,11-24 16:20:51.130  5739  5862 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 16:20:51.130  5739  5862 D BluetoothAdapterProperties: Setting state to 13
,11-24 16:20:51.130  5739  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 16:20:51.132  5739  5862 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 16:20:51.135  5739  5862 I BluetoothAdapterState: Entering PendingCommandState
,11-24 16:20:51.143  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:51.143  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:20:51.143  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:20:51.143  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:20:51.143  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:20:51.143  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 16:20:51.143  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:20:51.143  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:20:51.143  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:20:51.143  5603  5603 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 16:20:51.145  5739  5739 D BluetoothMapService: onReceive
11-24 16:20:51.146  5739  5739 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 16:20:51.146  5739  5739 D BluetoothMapService: STATE_TURNING_OFF
11-24 16:20:51.146  5739  5739 D BluetoothMapService: MAP Service closeService in
11-24 16:20:51.146  5739  5739 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 16:20:51.146  5603  5603 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 16:20:51.146  5739  5739 D ObexServerSockets0: shutdown(block = true)
,11-24 16:20:51.146  5603  5603 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 16:20:51.147  5739  5739 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 16:20:51.147  5739  5888 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 16:20:51.148  5739  5739 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 16:20:51.148  5739  5875 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 16:20:51.148  5739  5889 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,11-24 16:20:51.150  5739  5866 D BluetoothAdapterProperties: Scan Mode:20
,11-24 16:20:51.151  5739  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 16:20:51.152  5739  5739 I BtOppRfcommListener: stopping Accept Thread
11-24 16:20:51.152  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:51.153  5739  5898 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-24 16:20:51.153  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 16:20:51.153  5739  5898 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 16:20:51.157  5739  5739 D HeadsetService: Received stop request...Stopping profile...
,11-24 16:20:51.158  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,11-24 16:20:51.164   928   928 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:51.165  3144  3158 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:51.165   928   928 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:51.165   928   928 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:51.165  3815  3827 D BluetoothHeadset: Proxy object disconnected
11-24 16:20:51.166  5679  5694 D BluetoothHeadset: Proxy object disconnected
,11-24 16:20:51.167  5739  5739 D A2dpService: Received stop request...Stopping profile...
,11-24 16:20:51.167  5739  5881 D A2dpStateMachine: Exit Disconnected: -1
11-24 16:20:51.168   928   928 D BluetoothA2dp: Proxy object disconnected
11-24 16:20:51.168  5679  5679 D HeadsetProfile: Bluetooth service disconnected
,11-24 16:20:51.171  5739  5739 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:51.171  5739  5739 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:51.171  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 16:20:51.171  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:51.171  5739  5739 D HidService: Received stop request...Stopping profile...
11-24 16:20:51.172  5739  5739 D HidService: Stopping Bluetooth HidService
11-24 16:20:51.172  5679  5679 D BluetoothA2dp: Proxy object disconnected
11-24 16:20:51.173  3144  3144 D HeadsetProfile: Bluetooth service disconnected
11-24 16:20:51.173  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 16:20:51.173  3144  3144 D BluetoothA2dp: Proxy object disconnected
11-24 16:20:51.173  3144  3144 D BluetoothInputDevice: Proxy object disconnected
11-24 16:20:51.173  3144  3144 D HidProfile: Bluetooth service disconnected
,11-24 16:20:51.174  5739  5739 D HealthService: Received stop request...Stopping profile...
11-24 16:20:51.175  5739  5739 D PanService: Received stop request...Stopping profile...
11-24 16:20:51.176  3144  3144 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 16:20:51.176  3144  3144 D PanProfile: Bluetooth service disconnected
11-24 16:20:51.177  5739  5739 D BluetoothMapService: Received stop request...Stopping profile...
11-24 16:20:51.177  5739  5739 D BluetoothMapService: stop()
,11-24 16:20:51.177  5739  5739 D BluetoothMapAppObserver: deinitObservers()
11-24 16:20:51.177  5739  5739 D BluetoothMapAppObserver: removeReceiver()
11-24 16:20:51.179  3144  3144 D BluetoothMap: Proxy object disconnected
11-24 16:20:51.179  3144  3144 D MapProfile: Bluetooth service disconnected
11-24 16:20:51.179  5679  5679 D BluetoothInputDevice: Proxy object disconnected
11-24 16:20:51.179  5679  5679 D HidProfile: Bluetooth service disconnected
11-24 16:20:51.179  5739  5739 D SapService: Received stop request...Stopping profile...
11-24 16:20:51.179  5739  5739 V SapService: stop()
11-24 16:20:51.180  5679  5679 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-24 16:20:51.180  5679  5679 D PanProfile: Bluetooth service disconnected
11-24 16:20:51.180  5679  5679 D BluetoothMap: Proxy object disconnected
11-24 16:20:51.180  5679  5679 D MapProfile: Bluetooth service disconnected
,11-24 16:20:51.182  5739  5739 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 16:20:51.182  5739  5739 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 16:20:51.182  5739  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:51.182  5739  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 16:20:51.182  5739  5739 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:51.182  5739  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:51.182  5739  5739 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:51.182  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:51.182  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:20:51.184  5739  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 16:20:51.184  5739  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 16:20:51.184  5739  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:51.184  5739  5866 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 16:20:51.184  5739  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:51.185  5739  5873 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 16:20:51.185  5739  5873 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 16:20:51.185  5739  5873 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 16:20:51.185  5739  5873 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 16:20:51.185  3144  3144 D BluetoothPbap: Proxy object disconnected
11-24 16:20:51.185  5739  5739 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:51.185  3144  3144 D PbapServerProfile: Bluetooth service disconnected
11-24 16:20:51.185  5739  5739 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:51.185  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:51.185  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:20:51.185  5739  5739 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 16:20:51.185  5739  5739 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 16:20:51.186  5739  5866 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 16:20:51.186  5739  5739 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:51.186  5739  5739 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:51.186  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:51.186  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:20:51.186  5679  5679 D BluetoothPbap: Proxy object disconnected
11-24 16:20:51.186  5679  5679 D PbapServerProfile: Bluetooth service disconnected
11-24 16:20:51.186  5739  5739 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 16:20:51.187  5739  5866 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 16:20:51.187  5739  5739 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 16:20:51.187  5739  5739 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:51.187  5739  5739 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:51.187  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:51.187  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:20:51.188  5739  5739 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 16:20:51.188  5739  5739 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 16:20:51.189  5739  5739 D BluetoothMapService: MAP Service closeService in
11-24 16:20:51.189  5739  5739 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:51.189  5739  5739 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:51.189  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:51.189  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:20:51.189  5739  5739 D BluetoothMapService: cleanup()
11-24 16:20:51.189  5739  5739 D BluetoothMapService: MAP Service closeService in
11-24 16:20:51.189  5739  5739 V BluetoothAdapterState: isTurningOff()=true
11-24 16:20:51.189  5739  5739 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:51.189  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:51.189  5739  5739 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:20:51.190  5739  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 16:20:51.190  5739  5862 D BluetoothAdapterProperties: Setting state to 15
11-24 16:20:51.190  5739  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 16:20:51.190  5739  5862 I BluetoothAdapterState: Entering BleOnState
11-24 16:20:51.191  3144  3157 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 16:20:51.192  5679  5690 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 16:20:51.192  5679  5694 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 16:20:51.193  3144  3158 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 16:20:51.193   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:20:51.193  5679  5690 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 16:20:51.194  5679  5694 D BluetoothPan: onBluetoothStateChange on: false
11-24 16:20:51.194  5679  5690 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 16:20:51.195  5679  5694 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 16:20:51.195   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 16:20:51.195  3815  3829 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 16:20:51.195   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:20:51.195  3144  3996 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 16:20:51.196  3144  3157 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 16:20:51.196  3144  3158 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:20:51.197   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 16:20:51.197  3144  3158 D BluetoothPan: onBluetoothStateChange on: false
11-24 16:20:51.198  5739  5862 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 16:20:51.198  5739  5862 D BluetoothAdapterProperties: Setting state to 16
11-24 16:20:51.198  5739  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 16:20:51.198  5739  5862 D BluetoothAdapterProperties: onBleDisable
11-24 16:20:51.198  5739  5862 I BluetoothAdapterState: Entering PendingCommandState
11-24 16:20:51.198  5739  5863 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 16:20:51.200  5739  5873 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 16:20:51.200  5739  5873 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 16:20:51.201  5739  5866 D BluetoothAdapterProperties: Scan Mode:20
11-24 16:20:51.201  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 16:20:51.202  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:20:51.203  5603  5603 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:20:51.207  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:20:51.212  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,11-24 16:20:51.411  5739  5866 I bt_hci  : shut_down
,11-24 16:20:51.414  5739  5870 D bt_hwcfg: hw_epilog_process
,11-24 16:20:51.414  5739  5870 I bt_vendor: low_power_mode_cb
,11-24 16:20:51.417  5739  5870 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 16:20:51.417  5739  5870 I bt_vendor: epilog_cb
11-24 16:20:51.417  5739  5870 I bt_hci  : epilog_finished_callback
,11-24 16:20:51.419  5739  5866 I bt_hci_h4: hal_close
,11-24 16:20:51.419  5739  5866 I bt_userial_vendor: device fd = 54 close
,11-24 16:20:51.532  5739  5863 D bt_stack_manager: event_shut_down_stack finished.
,11-24 16:20:51.533  5739  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 16:20:51.536  5739  5739 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 16:20:51.536  5739  5862 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 16:20:51.536  5739  5739 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 16:20:51.537  5739  5739 D BtGatt.GattService: stop()
,11-24 16:20:51.537  5739  5739 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 16:20:51.539  5739  5739 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:20:51.539  5739  5739 V BluetoothAdapterState: isTurningOn()=false
11-24 16:20:51.539  5739  5739 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:20:51.539  5739  5739 V BluetoothAdapterState: isBleTurningOff()=true
11-24 16:20:51.539  5739  5862 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-24 16:20:51.539  5739  5862 D BluetoothAdapterProperties: Setting state to 10
11-24 16:20:51.540  5739  5862 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 16:20:51.540  5739  5862 I BluetoothAdapterState: Entering OffState
11-24 16:20:51.541   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 16:20:51.550  5739  5739 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 16:20:51.550  5739  5739 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 16:20:51.550  5739  5739 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 16:20:51.552  5739  5863 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 16:20:51.558  5739  5739 I art     : System.exit called, status: 0
,11-24 16:20:51.558  5739  5739 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 16:20:51.584   928  3828 I ActivityManager: Process com.android.bluetooth (pid 5739) has died
,11-24 16:20:52.115   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:53.116   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:53.336  3587  3587 I ConfigService: onDestroy
,11-24 16:20:54.117   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:55.118   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:56.119   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:20:56.128  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:20:56.128  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:20:56.133  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:20:56.133  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d50bab removed from the list
,11-24 16:20:56.133  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:56.136  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:20:56.136  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb5fbc6 added. We now have 4 listener(s)
,11-24 16:20:56.136  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:20:56.138  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:20:56.138  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@eb5fbc6 removed from the list
11-24 16:20:56.138  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:20:56.140  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 16:20:56.140  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@756b787 added. We now have 4 listener(s)
11-24 16:20:56.141  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:20:57.120   619   619 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 16:21:01.152  5603  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 16:21:01.184   928   945 I ActivityManager: Start proc 5907:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 16:21:01.273  5907  5907 D AdapterServiceConfig: Adding HeadsetService
,11-24 16:21:01.274  5907  5907 D AdapterServiceConfig: Adding A2dpService
11-24 16:21:01.274  5907  5907 D AdapterServiceConfig: Adding HidService
,11-24 16:21:01.274  5907  5907 D AdapterServiceConfig: Adding HealthService
,11-24 16:21:01.274  5907  5907 D AdapterServiceConfig: Adding PanService
,11-24 16:21:01.274  5907  5907 D AdapterServiceConfig: Adding GattService
11-24 16:21:01.275  5907  5907 D AdapterServiceConfig: Adding BluetoothMapService
11-24 16:21:01.275  5907  5907 D AdapterServiceConfig: Adding SapService
,11-24 16:21:01.286   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a0abafb:true
,11-24 16:21:01.286  5907  5907 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 16:21:01.289  5907  5907 I bt_bluedroid: init
,11-24 16:21:01.290  5907  5919 I BluetoothAdapterState: Entering OffState
,11-24 16:21:01.292  5907  5920 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 16:21:01.292  5907  5920 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 16:21:01.292  5907  5920 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,11-24 16:21:01.293  5907  5920 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 16:21:01.293  5907  5907 I bt_bluedroid: get_profile_interface socket
,11-24 16:21:01.295  5907  5923 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-24 16:21:01.295  5907  5907 I bt_bluedroid: get_profile_interface sdp
11-24 16:21:01.297  5907  5923 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 16:21:01.307  5907  5918 I bt_bluedroid: config_hci_snoop_log
,11-24 16:21:01.308   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 16:21:01.312  5907  5919 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 16:21:01.313  5907  5919 D BluetoothAdapterProperties: Setting state to 14
11-24 16:21:01.313  5907  5919 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 16:21:01.315  5907  5919 D BluetoothBondStateMachine: make
,11-24 16:21:01.316  5907  5924 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 16:21:01.319  5907  5919 I BluetoothAdapterState: Entering PendingCommandState
,11-24 16:21:01.321  5907  5907 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 16:21:01.323  5907  5907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
11-24 16:21:01.324  5907  5907 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 16:21:01.325  5907  5907 D BtGatt.GattService: Received start request. Starting profile...
11-24 16:21:01.325  5907  5907 D BtGatt.GattService: start()
11-24 16:21:01.325  5907  5907 I bt_bluedroid: get_profile_interface gatt
,11-24 16:21:01.326  5907  5907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
11-24 16:21:01.327  5907  5907 D BtGatt.AdvertiseManager: advertise manager created
,11-24 16:21:01.333  5907  5907 V BluetoothAdapterState: isTurningOff()=false
11-24 16:21:01.333  5907  5907 V BluetoothAdapterState: isTurningOn()=false
11-24 16:21:01.333  5907  5907 V BluetoothAdapterState: isBleTurningOn()=true
,11-24 16:21:01.333  5907  5907 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:21:01.333  5907  5919 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 16:21:01.335  5907  5919 I bt_bluedroid: bt_bluedroid
,11-24 16:21:01.335  5907  5920 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 16:21:01.336  5907  5920 I bt_hci  : start_up
,11-24 16:21:01.341  5907  5920 I bt_vendor: alloc value 0xf3fa5871
,11-24 16:21:01.341  5907  5920 I bt_vendor: init
11-24 16:21:01.341  5907  5920 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 16:21:01.341  5907  5920 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 16:21:01.448  5907  5920 D bt_hci  : start_up starting async portion
,11-24 16:21:01.449  5907  5927 I bt_hci  : event_finish_startup
11-24 16:21:01.449  5907  5927 I bt_hci_h4: hal_open
,11-24 16:21:01.449  5907  5927 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-24 16:21:01.444  5928  5928 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-24 16:21:01.451  5907  5927 I bt_userial_vendor: device fd = 54 open
,11-24 16:21:01.464  5907  5927 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 16:21:01.467  5907  5927 D bt_hwcfg: Chipset BCM4358A3
,11-24 16:21:01.467  5907  5927 D bt_hwcfg: Target name = [BCM4358A3]
,11-24 16:21:01.467  5907  5927 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 16:21:01.841  5907  5927 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-24 16:21:01.841  5907  5927 D bt_hwcfg: Settlement delay -- 100 ms
11-24 16:21:01.841  5907  5927 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 16:21:01.975  5907  5927 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 16:21:01.975  5907  5927 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-24 16:21:01.977  5907  5927 I bt_hwcfg: vendor lib fwcfg completed
11-24 16:21:01.977  5907  5927 I bt_vendor: firmware callback
11-24 16:21:01.977  5907  5927 I bt_hci  : firmware_config_callback
,11-24 16:21:01.987  5907  5930 I bt_btu  : btu_task pending for preload complete event
11-24 16:21:01.988  5907  5930 I bt_btu_task: Bluetooth chip preload is complete
11-24 16:21:01.988  5907  5930 I bt_btu  : btu_task received preload complete event
,11-24 16:21:01.996  5907  5930 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 16:21:01.996  5907  5930 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-24 16:21:01.996  5907  5930 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 16:21:01.996  5907  5930 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 16:21:01.996  5907  5930 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 16:21:01.996  5907  5930 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 16:21:01.997  5907  5930 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 16:21:01.997  5907  5930 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 16:21:01.997  5907  5930 I         : BTE_InitTraceLevels -- TRC_GAP
,11-24 16:21:01.997  5907  5930 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 16:21:01.997  5907  5930 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 16:21:01.998  5907  5930 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 16:21:01.998  5907  5930 I         : BTE_InitTraceLevels -- TRC_SMP
,11-24 16:21:01.998  5907  5930 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 16:21:01.998  5907  5930 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 16:21:02.082  5907  5930 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f23549
,11-24 16:21:02.082  5907  5930 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f23549 
,11-24 16:21:02.104  5907  5923 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 16:21:02.105  5907  5923 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 16:21:02.105  5907  5923 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-24 16:21:02.108  5907  5923 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 16:21:02.111  5907  5923 D BluetoothAdapterProperties: Scan Mode:20
11-24 16:21:02.113  5907  5923 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 16:21:02.113  5907  5923 D bt_hci  : do_postload posting postload work item
,11-24 16:21:02.113  5907  5927 I bt_hci  : event_postload
,11-24 16:21:02.113  5907  5927 I bt_vendor: sco_config_cb
11-24 16:21:02.113  5907  5927 I bt_hci  : sco_config_callback postload finished.
11-24 16:21:02.115  5907  5923 D bt_bte_conf: Device ID record 1 : primary
11-24 16:21:02.116  5907  5923 D bt_bte_conf:   vendorId            = 000f
11-24 16:21:02.116  5907  5923 D bt_bte_conf:   vendorIdSource      = 0001
11-24 16:21:02.116  5907  5923 D bt_bte_conf:   product             = 1200
11-24 16:21:02.116  5907  5923 D bt_bte_conf:   version             = 1436
11-24 16:21:02.116  5907  5923 D bt_bte_conf:   clientExecutableURL = 
11-24 16:21:02.116  5907  5923 D bt_bte_conf:   serviceDescription  = 
11-24 16:21:02.116  5907  5923 D bt_bte_conf:   documentationURL    = 
11-24 16:21:02.116  5907  5923 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 16:21:02.117  5907  5920 D bt_stack_manager: event_start_up_stack finished
11-24 16:21:02.118  5907  5919 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 16:21:02.118  5907  5919 D BluetoothAdapterProperties: Setting state to 15
11-24 16:21:02.118  5907  5919 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 16:21:02.119  5907  5927 I bt_vendor: low_power_mode_cb
11-24 16:21:02.120  5907  5919 I BluetoothAdapterState: Entering BleOnState
,11-24 16:21:02.125  5907  5919 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-24 16:21:02.125  5907  5919 D BluetoothAdapterProperties: Setting state to 11
11-24 16:21:02.125  5907  5919 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 16:21:02.130  5907  5907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:21:02.131  5907  5907 D HeadsetService: Received start request. Starting profile...
,11-24 16:21:02.133  5907  5907 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 16:21:02.133  5907  5907 D HeadsetStateMachine: make
,11-24 16:21:02.148  5907  5919 I BluetoothAdapterState: Entering PendingCommandState
,11-24 16:21:02.148  5907  5907 D HeadsetStateMachine: max_hf_connections = 1
11-24 16:21:02.148  5907  5907 I bt_bluedroid: get_profile_interface handsfree
,11-24 16:21:02.148  5907  5923 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-24 16:21:02.148  5907  5923 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-24 16:21:02.151  5907  5907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:21:02.151  5907  5907 D A2dpService: Received start request. Starting profile...
11-24 16:21:02.152  5907  5907 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-24 16:21:02.152  5907  5907 I bt_bluedroid: get_profile_interface avrcp
,11-24 16:21:02.157  5907  5907 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-24 16:21:02.157  5907  5907 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 16:21:02.157  5907  5907 D A2dpStateMachine: make
,11-24 16:21:02.159  5907  5907 I bt_bluedroid: get_profile_interface a2dp
,11-24 16:21:02.159  5907  5923 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-24 16:21:02.161  5907  5937 D A2dpStateMachine: Enter Disconnected: -2
11-24 16:21:02.161  5907  5907 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 16:21:02.162  5907  5907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:21:02.162  5907  5907 D HidService: Received start request. Starting profile...
,11-24 16:21:02.162  5907  5907 I bt_bluedroid: get_profile_interface hidhost
11-24 16:21:02.162  5907  5907 D HidService: setHidService(): set to: null
11-24 16:21:02.162  5907  5923 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f0456d
11-24 16:21:02.162  5907  5923 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 16:21:02.165  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:21:02.165  5907  5907 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 16:21:02.166  5907  5907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:21:02.166  5907  5907 D HealthService: Received start request. Starting profile...
,11-24 16:21:02.168  5907  5907 I bt_bluedroid: get_profile_interface health
,11-24 16:21:02.169  5907  5907 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-24 16:21:02.169  5907  5907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:21:02.170  5907  5907 D PanService: Received start request. Starting profile...
11-24 16:21:02.170  5907  5907 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 16:21:02.170  5907  5907 I bt_bluedroid: get_profile_interface pan
11-24 16:21:02.170  5907  5923 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 16:21:02.172  5907  5907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:21:02.173  5907  5907 D BluetoothMapService: Received start request. Starting profile...
11-24 16:21:02.173  5907  5907 D BluetoothMapService: start()
,11-24 16:21:02.175  5907  5907 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-24 16:21:02.176  5907  5907 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 16:21:02.176  5907  5907 D BluetoothMapAppObserver: createReceiver()
11-24 16:21:02.177  5907  5907 D BluetoothMapAppObserver: initObservers()
11-24 16:21:02.177  5907  5907 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 16:21:02.183  5907  5907 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:21:02.183  5907  5907 V BluetoothAdapterState: isTurningOn()=true
11-24 16:21:02.183  5907  5907 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:21:02.183  5907  5907 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:21:02.185  5907  5907 V SapService: SapBinder()
,11-24 16:21:02.185  5907  5907 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
,11-24 16:21:02.185  5907  5907 D SapService: Received start request. Starting profile...
11-24 16:21:02.185  5907  5907 V SapService: start()
,11-24 16:21:02.187  5907  5907 V BluetoothAdapterState: isTurningOff()=false
,11-24 16:21:02.187  5907  5907 V BluetoothAdapterState: isTurningOn()=true
11-24 16:21:02.187  5907  5935 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 16:21:02.187  5907  5907 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:21:02.187  5907  5907 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:21:02.187  5907  5907 V BluetoothAdapterState: isTurningOff()=false
11-24 16:21:02.187  5907  5907 V BluetoothAdapterState: isTurningOn()=true
11-24 16:21:02.187  5907  5907 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:21:02.187  5907  5907 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 16:21:02.188  5907  5907 V BluetoothAdapterState: isTurningOff()=false
11-24 16:21:02.189  5907  5907 V BluetoothAdapterState: isTurningOn()=true
11-24 16:21:02.189  5907  5907 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:21:02.189  5907  5907 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:21:02.189  5907  5907 V BluetoothAdapterState: isTurningOff()=false
11-24 16:21:02.189  5907  5907 V BluetoothAdapterState: isTurningOn()=true
11-24 16:21:02.189  5907  5907 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:21:02.189  5907  5907 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:21:02.189  5907  5907 V BluetoothAdapterState: isTurningOff()=false
11-24 16:21:02.189  5907  5907 V BluetoothAdapterState: isTurningOn()=true
11-24 16:21:02.190  5907  5907 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:21:02.190  5907  5907 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:21:02.190  5907  5907 V BluetoothAdapterState: isTurningOff()=false
11-24 16:21:02.190  5907  5907 V BluetoothAdapterState: isTurningOn()=true
11-24 16:21:02.191  5907  5907 V BluetoothAdapterState: isBleTurningOn()=false
11-24 16:21:02.191  5907  5907 V BluetoothAdapterState: isBleTurningOff()=false
11-24 16:21:02.191  5907  5919 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-24 16:21:02.191  5907  5919 D BluetoothAdapterProperties: ScanMode =  20
11-24 16:21:02.191  5907  5919 D BluetoothAdapterProperties: State =  11
11-24 16:21:02.191  5907  5919 D BluetoothAdapterProperties: Setting state to 12
11-24 16:21:02.191  5907  5919 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-24 16:21:02.192  3144  3158 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 16:21:02.192  5907  5923 D BluetoothAdapterProperties: Scan Mode:21
11-24 16:21:02.192  5907  5923 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 16:21:02.192  5907  5919 I BluetoothAdapterState: Entering OnState
,11-24 16:21:02.194  5679  5694 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:21:02.195  5679  5690 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 16:21:02.195  3144  3144 D BluetoothMap: Proxy object connected
11-24 16:21:02.195  3144  3144 D MapProfile: Bluetooth service connected
11-24 16:21:02.195  3144  3144 D BluetoothMap: getConnectedDevices()
11-24 16:21:02.196  3144  3157 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 16:21:02.197   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:21:02.198  5679  5694 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 16:21:02.198  3144  3144 D BluetoothInputDevice: Proxy object connected
,11-24 16:21:02.198  3144  3144 D HidProfile: Bluetooth service connected
11-24 16:21:02.199  5679  5690 D BluetoothPan: onBluetoothStateChange on: true
,11-24 16:21:02.201  5679  5679 D BluetoothA2dp: Proxy object connected
,11-24 16:21:02.201  5679  5694 D BluetoothMap: onBluetoothStateChange: up=true
11-24 16:21:02.203  5679  5690 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 16:21:02.203  5907  5907 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 16:21:02.204  5907  5907 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 16:21:02.204   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 16:21:02.205   928   928 D BluetoothA2dp: Proxy object connected
,11-24 16:21:02.205  3815  3829 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:21:02.205  5907  5907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:21:02.206   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:21:02.206  3144  3996 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 16:21:02.207  5907  5907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:21:02.208  3144  3158 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 16:21:02.208  3144  3144 D BluetoothA2dp: Proxy object connected
11-24 16:21:02.208  5679  5679 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 16:21:02.208  5679  5679 D PanProfile: Bluetooth service connected
,11-24 16:21:02.209  5679  5679 D BluetoothMap: Proxy object connected
11-24 16:21:02.209  5679  5679 D MapProfile: Bluetooth service connected
,11-24 16:21:02.209  5679  5679 D BluetoothMap: getConnectedDevices()
11-24 16:21:02.209  5907  5907 D ObexServerSockets: Succeed to create listening sockets 
11-24 16:21:02.209  5907  5907 D ObexServerSockets0: startAccept()
11-24 16:21:02.209  5907  5907 D ObexServerSockets0: prepareForNewConnect()
11-24 16:21:02.209  3144  3996 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 16:21:02.210   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 16:21:02.210  3144  3157 D BluetoothPan: onBluetoothStateChange on: true
11-24 16:21:02.210  5679  5679 D BluetoothInputDevice: Proxy object connected
11-24 16:21:02.210  5679  5679 D HidProfile: Bluetooth service connected
11-24 16:21:02.211  5907  5907 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 16:21:02.211  5907  5907 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-24 16:21:02.211  5907  5944 D ObexServerSockets0: Accepting socket connection...
11-24 16:21:02.212  3144  3144 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 16:21:02.212  3144  3144 D PanProfile: Bluetooth service connected
11-24 16:21:02.212  5907  5945 D ObexServerSockets0: Accepting socket connection...
11-24 16:21:02.213   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 16:21:02.214  5907  5907 D BluetoothMapService: onReceive
11-24 16:21:02.214  5907  5907 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 16:21:02.214  5907  5907 D BluetoothMapService: STATE_ON
11-24 16:21:02.217  5907  5947 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 16:21:02.218  5679  5679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 16:21:02.219  5907  5947 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 16:21:02.219  5907  5947 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 16:21:02.225  3587  3587 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 16:21:02.229  5679  5679 D DockEventReceiver: finishStartingService: stopping service
,11-24 16:21:02.235  5679  5679 D BluetoothPbap: Proxy object connected
,11-24 16:21:02.235  5679  5679 D PbapServerProfile: Bluetooth service connected
11-24 16:21:02.240  5907  5951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:21:02.240  5907  5907 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 16:21:02.240  5907  5907 D ObexServerSockets0: prepareForNewConnect()
11-24 16:21:02.241  3144  3144 D BluetoothPbap: Proxy object connected
11-24 16:21:02.241  3144  3144 D PbapServerProfile: Bluetooth service connected
,11-24 16:21:02.257  5907  5955 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 16:21:02.258  5907  5955 I BtOppRfcommListener: Accept thread started.
,11-24 16:21:02.296   928   928 D BluetoothHeadset: Proxy object connected
,11-24 16:21:02.296  3144  3157 D BluetoothHeadset: Proxy object connected
11-24 16:21:02.296  3144  3144 D HeadsetProfile: Bluetooth service connected
11-24 16:21:02.296   928   928 D BluetoothHeadset: Proxy object connected
11-24 16:21:02.297   928   928 D BluetoothHeadset: Proxy object connected
11-24 16:21:02.297  3815  4031 D BluetoothHeadset: Proxy object connected
,11-24 16:21:02.297  5679  5690 D BluetoothHeadset: Proxy object connected
,11-24 16:21:02.299  5679  5679 D HeadsetProfile: Bluetooth service connected
,11-24 16:21:02.298   928   945 D BluetoothHeadset: Proxy object connected
,11-24 16:21:02.311  3815  4003 D BluetoothHeadset: Proxy object connected
,11-24 16:21:02.311   928   945 D BluetoothHeadset: Proxy object connected
,11-24 16:21:02.312  3144  3158 D BluetoothHeadset: Proxy object connected
11-24 16:21:02.312  3144  3144 D HeadsetProfile: Bluetooth service connected
11-24 16:21:02.312   928   945 D BluetoothHeadset: Proxy object connected
,11-24 16:21:05.458  4048  4477 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-24 16:21:06.169  5603  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:21:06.169  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:21:06.169  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:21:06.169  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 16:21:06.169  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:21:06.169  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 16:21:06.169  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 16:21:06.169  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 16:21:06.169  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 16:21:06.176  5603  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 16:21:06.177  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:21:06.177  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@756b787 removed from the list
,11-24 16:21:06.177  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:21:06.180  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:06.180  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@54176b4 added. We now have 4 listener(s)
,11-24 16:21:06.180  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:21:06.186   928   938 D WifiService: setWifiEnabled: false pid=5603, uid=10077
,11-24 16:21:06.186   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:21:11.196  5603  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 16:21:11.196   928  3826 D WifiService: setWifiEnabled: true pid=5603, uid=10077
11-24 16:21:11.197   928  3826 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 16:21:11.203   510   922 D SoftapController: Softap fwReload - Ok
,11-24 16:21:11.209   510   922 D CommandListener: Setting iface cfg
,11-24 16:21:11.209   510   922 D CommandListener: Trying to bring down wlan0
11-24 16:21:11.212   510   922 D CommandListener: Clearing all IP addresses on wlan0
11-24 16:21:11.217   928  2975 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 16:21:11.897   928  2975 D wifi    : set interface wlan0 flags (UP)
,11-24 16:21:11.898   928  2975 I WifiHAL : Initializing wifi
,11-24 16:21:11.898   928  2975 I WifiHAL : Creating socket
,11-24 16:21:11.905   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 16:21:11.905   928  2975 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 16:21:11.906   928  2975 D wifi    : Did set static halHandle = 0x7f5c96fb80
11-24 16:21:11.906   928  2975 D wifi    : halHandle = 0x7f5c96fb80, mVM = 0x7f78fcd140, mCls = 0x14ca
11-24 16:21:11.908   928  2975 D wifi    : array field set
11-24 16:21:11.908   928  2975 I WifiNative-HAL: interface[0] = wlan0
11-24 16:21:11.910   928  5960 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547014245248
11-24 16:21:11.911   928  5960 D wifi    : waitForHalEvents called, vm = 0x7f78fcd140, obj = 0x14ca, env = 0x7f6391c380
,11-24 16:21:11.960  5961  5961 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 16:21:12.013   928  2975 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 16:21:12.027  5961  5961 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 16:21:12.101  5961  5961 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 16:21:12.101  5961  5961 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 16:21:12.120   928  2975 D WifiConfigStore: Loading config and enabling all networks 
11-24 16:21:12.121   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:21:12.159   928  2975 D WifiConfigStore: loaded 0 passpoint configs
,11-24 16:21:12.160   928  2975 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-24 16:21:12.161   928  2975 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 16:21:12.162   928  2975 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 16:21:12.162   928  2975 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-24 16:21:12.163   928  2975 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-24 16:21:12.164   928  2975 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 16:21:12.165   928  2975 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-24 16:21:12.165   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-24 16:21:12.165   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-24 16:21:12.165   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-24 16:21:12.165   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-24 16:21:12.165   928  2975 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-24 16:21:12.169   928  2975 D WifiNative-HAL: Setting external_sim to 1
11-24 16:21:12.170   928  2975 D wifi    : setting dfs flag to true, 0x7f601f1920
11-24 16:21:12.170  5006  5006 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 16:21:12.171   928  2975 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 16:21:12.171   928  2975 D wifi    : setting scan oui 0x7f601f1920
11-24 16:21:12.171   928  2975 D WifiHAL : Sending mac address OUI
,11-24 16:21:12.176   928  2975 E native  : do suspend false
,11-24 16:21:12.187   928  2975 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 16:21:12.188   928   928 D RttService: SCAN_AVAILABLE : 3
,11-24 16:21:12.188   928  3085 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 16:21:12.193   510   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 16:21:12.196   510   922 D CommandListener: Setting iface cfg
,11-24 16:21:12.200   928  2967 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
11-24 16:21:12.200   928  2967 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 16:21:12.206   928  2967 D WifiNative-HAL: p2pGetDeviceAddress
11-24 16:21:12.206   928  2967 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-24 16:21:12.213   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=164032 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=19 mControllerEnergyUsed=72 }
,11-24 16:21:13.122   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:21:14.123   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:21:15.124   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:21:15.254  5961  5961 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 16:21:15.262  5961  5961 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 16:21:15.292   928  2975 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 16:21:15.294   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 16:21:15.294   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 16:21:15.305   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 16:21:15.340   928  2975 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 16:21:15.346  5961  5961 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 16:21:15.784  5961  5961 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 16:21:15.817  5961  5961 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 16:21:15.819  5961  5961 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 16:21:15.831   928  2975 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 16:21:15.831   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 16:21:15.831   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 16:21:15.851   928  2975 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 16:21:15.865   510   922 D CommandListener: Setting iface cfg
,11-24 16:21:15.871   928  2975 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 16:21:15.877   928  5966 D DhcpClient: Receive thread started
,11-24 16:21:15.882   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 16:21:15.883   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 16:21:15.883   928  2977 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 16:21:15.964   928  2975 E native  : do suspend false
,11-24 16:21:15.975   928  5965 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 16:21:15.988   928  5966 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-24 16:21:15.989   928  5965 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-24 16:21:15.991   928  5965 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-24 16:21:16.002   928  5966 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 16:21:16.003   928  5965 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 16:21:16.005   510   922 D CommandListener: Setting iface cfg
11-24 16:21:16.011   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 16:21:16.014   928  5965 D DhcpClient: Scheduling renewal in 86399s
,11-24 16:21:16.029   928  2975 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 16:21:16.030   928  2975 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 16:21:16.031   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 16:21:16.033   928  2977 D ConnectivityService: Adding iface wlan0 to network 102
,11-24 16:21:16.040   928  2975 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 16:21:16.085   928  2977 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 16:21:16.085   928  2977 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-24 16:21:16.087   928  2977 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-24 16:21:16.089   928  2977 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-24 16:21:16.093   928  2977 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-24 16:21:16.101   928  2977 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 16:21:16.106   928  2977 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-24 16:21:16.107   928  2977 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-24 16:21:16.107   928  2977 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 16:21:16.107   928  2977 D ConnectivityService:    accepting network in place of null
11-24 16:21:16.107   928  2975 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 16:21:16.107   928  2975 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 16:21:16.108   928  2977 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 16:21:16.123   928  5964 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167941, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 16:21:16.125   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:21:16.132   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 16:21:16.154   510   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 16:21:16.157   928  2977 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-24 16:21:16.157  3770  3891 W QCNEJ   : |CORE| network available: 102
,11-24 16:21:16.157   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 16:21:16.158   928  2977 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-24 16:21:16.160  3770  3891 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 16:21:16.163  3770  3891 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 16:21:16.163  3770  3891 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 16:21:16.164   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-24 16:21:16.175  5031  5055 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 16:21:16.175  5031  5055 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-24 16:21:16.176  5031  5055 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,11-24 16:21:16.179  5031  5055 E SarControlService: no key has been found,reset the power
,11-24 16:21:16.179  5031  5065 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-24 16:21:16.179  5031  5065 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-24 16:21:16.179  5031  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 16:21:16.180  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:21:16.180  5056  5056 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 16:21:16.181  5031  5065 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 16:21:16.181  5031  5065 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 16:21:16.181  5031  5065 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 16:21:16.182  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 16:21:16.183  5056  5056 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 16:21:16.185  3846  3846 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 16:21:16.189  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6aa7f97 HexData = [00000000f003000000000000ffffffff]
,11-24 16:21:16.189  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:21:16.189  5056  5070 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-24 16:21:16.189  5056  5070 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@6aa7f97 HexData = [00000000f103000000000000ffffffff]
11-24 16:21:16.189  5056  5070 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 16:21:16.189  5056  5070 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-24 16:21:16.190  3846  3846 D SystemUpdateService: onCreate
11-24 16:21:16.191  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 16:21:16.191  5031  5041 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 16:21:16.178  3975  3975 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 16:21:16.193  5056  5056 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 16:21:16.196  5031  5042 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 16:21:16.199   928  5963 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 16:21:16.200  3846  3846 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 16:21:16.212  5603  5650 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 16:21:16.212  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 16:21:16.212  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 16:21:16.212  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 16:21:16.212  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 16:21:16.212  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 16:21:16.212  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 16:21:16.212  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 16:21:16.212  5603  5650 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 16:21:16.215  5603  5650 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 16:21:16.215  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.215  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@54176b4 removed from the list
11-24 16:21:16.215  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:21:16.216  3846  5977 I SystemUpdateService: active receiver: enabled
,11-24 16:21:16.220  5603  5650 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-24 16:21:16.221  5603  5650 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-24 16:21:16.223  5603  5650 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b5080ab Bundle[{}]
,11-24 16:21:16.223  5603  5650 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 16:21:16.224  5603  5650 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 16:21:16.224  5603  5650 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-24 16:21:16.225  5603  5650 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-24 16:21:16.225  3846  5977 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 16:21:16.226  5603  5650 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-24 16:21:16.227  5603  5650 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-24 16:21:16.233  5603  5650 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-24 16:21:16.233  3846  3846 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 16:21:16.234  5603  5650 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 16:21:16.234  5603  5650 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
11-24 16:21:16.235  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:21:16.236  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24292dd added. We now have 3 listener(s)
,11-24 16:21:16.237  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:21:16.237  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.237  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:21:16.238  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.238  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3060e52 added. We now have 4 listener(s)
11-24 16:21:16.238  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:21:16.238  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 16:21:16.239  3846  5379 I iu.UploadsManager: num queued entries: 0
,11-24 16:21:16.239  3846  5379 I iu.UploadsManager: num updated entries: 0
11-24 16:21:16.239  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:21:16.240  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75d4523 added. We now have 4 listener(s)
11-24 16:21:16.240  3846  5379 I iu.SyncManager: NEXT; no task
,11-24 16:21:16.241  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:21:16.241  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.241  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:21:16.241  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.242  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d94a20 added. We now have 5 listener(s)
11-24 16:21:16.242  3846  3846 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 16:21:16.242  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:21:16.242  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:21:16.242  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:21:16.242  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:21:16.242  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:21:16.242  3846  5977 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 16:21:16.242  3846  5977 I SystemUpdateService: now status is 0 (complete)
,11-24 16:21:16.242  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.242  3846  5977 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 16:21:16.242  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.242  3846  5977 I SystemUpdateService: file has been verified
11-24 16:21:16.242  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24292dd removed from the list
11-24 16:21:16.243  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.243  3846  5977 I SystemUpdateService: OTA package size = 21989297
11-24 16:21:16.243  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3060e52 removed from the list
,11-24 16:21:16.243  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:21:16.243  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.243  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.243  3846  3846 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 16:21:16.244  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.244  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.244  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.244  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.244  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 16:21:16.245  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.245  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3060e52 not in the list
11-24 16:21:16.245  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.245  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.246  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.246  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.246  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.246  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 16:21:16.246  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.246  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.246  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d94a20 removed from the list
11-24 16:21:16.247  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:21:16.247  5753  5753 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-24 16:21:16.247  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.247  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.247  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@75d4523 removed from the list
11-24 16:21:16.247  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:21:16.248  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ada7fd9 added. We now have 3 listener(s)
,11-24 16:21:16.249  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:21:16.249  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.249  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:21:16.249  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.250  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd2bd9e added. We now have 4 listener(s)
11-24 16:21:16.250  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:21:16.250  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 16:21:16.251   928  5963 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 15:21:16 GMT], X-Android-Received-Millis=[1480000876250], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480000876224]}
11-24 16:21:16.251  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:21:16.251  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b5107f added. We now have 4 listener(s)
11-24 16:21:16.251   928  2977 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 16:21:16.252   928  2977 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-24 16:21:16.252   928  2977 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 16:21:16.252  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-24 16:21:16.252  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.253  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:21:16.253   928  2977 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 16:21:16.253  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.253  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@658e84c added. We now have 5 listener(s)
11-24 16:21:16.253  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:21:16.253  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:21:16.253  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:21:16.253  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:21:16.253  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:21:16.253  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 16:21:16.254  5753  5753 D SprintDMHelper: simOperator: 
11-24 16:21:16.254  5753  5753 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 16:21:16.256  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 16:21:16.259  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 16:21:16.259  5603  5650 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:21:16.259  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 16:21:16.262  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.262  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:21:16.262  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:21:16.263  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:21:16.263  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 16:21:16.266  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.266  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:21:16.266  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:21:16.266  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:21:16.266  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:21:16.266  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.267  5603  5650 D BluetoothAdapter: STATE_ON
,11-24 16:21:16.270  5907  5946 D BtGatt.GattService: registerClient() - UUID=867578bd-8bd3-4376-81df-9da4d1900451
,11-24 16:21:16.270  5907  5923 D BtGatt.GattService: onClientRegistered() - UUID=867578bd-8bd3-4376-81df-9da4d1900451, clientIf=5
,11-24 16:21:16.271  5603  5721 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 16:21:16.272  5907  5942 D BtGatt.GattService: start scan with filters
11-24 16:21:16.273  3846  5977 I SystemUpdateService: showing system update notification
11-24 16:21:16.275  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 16:21:16.275  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.275  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 16:21:16.275  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.275  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:21:16.275  5907  5926 D BtGatt.ScanManager: handling starting scan
11-24 16:21:16.276  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:21:16.276  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.277  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:21:16.277  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.277  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:21:16.277  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 16:21:16.277  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.277  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.277  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.277  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.277  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.277  5907  5926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5f3011c
11-24 16:21:16.278  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.278  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.278  5603  5650 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 16:21:16.278  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.278  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 16:21:16.278  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 16:21:16.282  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.282  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:21:16.282  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.282  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.283  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:21:16.283  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:21:16.283  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:21:16.283  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:21:16.283  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:21:16.283  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.283  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 16:21:16.283  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.283  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.283  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ada7fd9 removed from the list
11-24 16:21:16.283  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.283  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd2bd9e removed from the list
11-24 16:21:16.283  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:21:16.283  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.283  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:21:16.284  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.284  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.284  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 16:21:16.284  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.284  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:21:16.284  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.285  5907  5923 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:21:16.285  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.285  5907  5926 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 16:21:16.286  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.286  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.286  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.286  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.286  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:21:16.286  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.286  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd2bd9e not in the list
11-24 16:21:16.286  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:21:16.287  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.287  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:21:16.287  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:21:16.287  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertise,r: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.287  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.287  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.287  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 16:21:16.287  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.288  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:21:16.289  5907  5942 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:21:16.289  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:21:16.290  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:21:16.290  5907  5917 D BtGatt.GattService: stopScan() - queue size =1
11-24 16:21:16.291  5907  5946 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:21:16.291  5907  5923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:21:16.291  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.291  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:21:16.291  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.292  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:21:16.292  5907  5926 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:21:16.292  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.292  5907  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 16:21:16.292  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.292  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.292  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.292  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:21:16.292  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.292  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.292  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.293  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:21:16.293  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 16:21:16.293  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 16:21:16.294  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.295  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.295  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:21:16.295  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.295  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.295  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:21:16.295  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.295  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.296  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@658e84c removed from the list
11-24 16:21:16.296  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 16:21:16.296  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:21:16.296  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.296  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.296  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:21:16.296  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b5107f removed from the list
11-24 16:21:16.296  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:21:16.296  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.296  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:21:16.296  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:21:16.296  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.296  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.296  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.296  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:21:16.296  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.296  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.297  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:21:16.297  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfb5111 added. We now have 3 listener(s)
11-24 16:21:16.297  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.297  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.298  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.300   928   928 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-24 16:21:16.301  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:21:16.301  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.301  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:21:16.301  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.301  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adae276 added. We now have 4 listener(s)
11-24 16:21:16.301  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:21:16.302  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 16:21:16.303  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:21:16.303  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d769077 added. We now have 4 listener(s)
11-24 16:21:16.303  5907  5923 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:21:16.303  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.305  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:21:16.305  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.305  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:21:16.305  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.305  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89f4e4 added. We now have 5 listener(s)
11-24 16:21:16.305  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:21:16.305  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 16:21:16.306  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:21:16.306  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:21:16.306  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:21:16.306  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:21:16.306  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 16:21:16.308  3846  3846 D SystemUpdateService: onDestroy
11-24 16:21:16.308  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 16:21:16.308  5907  5923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 16:21:16.309  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:21:16.311  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 16:21:16.311  5603  5650 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 16:21:16.311  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 16:21:16.312  5907  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 16:21:16.315  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.316  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:21:16.316  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:21:16.316  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:21:16.316  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 16:21:16.317  5907  5923 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:21:16.317  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.317  5907  5923 E BtGatt.ContextMap: Context not found for ID 5
11-24 16:21:16.319  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.319  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 16:21:16.319  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:21:16.320  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:21:16.320  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:21:16.320  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.321  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:21:16.322  5907  5942 D BtGatt.GattService: registerClient() - UUID=7efc04ba-76ac-4110-9339-ad3ac6a1a7f4
11-24 16:21:16.323  5907  5923 D BtGatt.GattService: onClientRegistered() - UUID=7efc04ba-76ac-4110-9339-ad3ac6a1a7f4, clientIf=5
,11-24 16:21:16.323  5603  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 16:21:16.323  5907  5918 D BtGatt.GattService: start scan with filters
11-24 16:21:16.324  5907  5923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 16:21:16.324  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.325  5907  5926 D BtGatt.ScanManager: stopping BLe Batch
,11-24 16:21:16.326  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 16:21:16.327  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.327  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 16:21:16.327  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.327  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:21:16.327  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:21:16.327  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.327  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:21:16.327  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 16:21:16.327  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.327  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.327  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.327  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.328  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:21:16.328  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.330  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.330  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:21:16.330  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.330  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.330  5907  5923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 16:21:16.330  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:21:16.330  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.330  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.330  5603  5650 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 16:21:16.330  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:21:16.330  5907  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 16:21:16.331  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:21:16.331  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:21:16.331  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:21:16.331  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.331  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:21:16.331  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.331  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.331  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfb5111 removed from the list
11-24 16:21:16.331  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.331  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adae276 removed from the list
11-24 16:21:16.331  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:21:16.331  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.331  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:21:16.331  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.331  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.331  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 16:21:16.331  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.331  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:21:16.331  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.332  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.332  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.332  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.332  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.332  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:21:16.332  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.332  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adae276 not in the list
11-24 16:21:16.333  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.333  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.333  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.333  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:21:16.333  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 16:21:16.333  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.333  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:21:16.333  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:21:16.333  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.333  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.334  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.334  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 16:21:16.334  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.334  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:21:16.335  5907  5942 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:21:16.335  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:21:16.336  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:21:16.336  5907  5923 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 16:21:16.336  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.337  5907  5918 D BtGatt.GattService: stopScan() - queue size =0
11-24 16:21:16.337  5907  5917 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.338  5907  5926 D BtGatt.ScanManager: handling starting scan
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.338  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:21:16.338  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 16:21:16.339  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:21:16.339  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.341  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.341  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:21:16.341  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.341  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.341  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:21:16.341  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.341  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.341  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e89f4e4 removed from the list
11-24 16:21:16.341  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:21:16.341  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.341  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.341  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d769077 removed from the list
11-24 16:21:16.342  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:21:16.342  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:21:16.342  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:21:16.342  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce1149 added. We now have 3 listener(s)
11-24 16:21:16.342  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:21:16.342  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.342  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:21:16.342  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:21:16.342  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.342  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.343  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.343  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:21:16.343  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.343  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.343  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:21:16.343  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.343  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 16:21:16.343  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.343  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@877ca4e added. We now have 4 listener(s)
11-24 16:21:16.343  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:21:16.344  5907  5923 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:21:16.344  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.344  5907  5926 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 16:21:16.344  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.344  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 16:21:16.344  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.344  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.345  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:21:16.345  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9176f added. We now have 4 listener(s)
11-24 16:21:16.346  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:21:16.347  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.347  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:21:16.347  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.347  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0cfc7c added. We now have 5 listener(s)
11-24 16:21:16.347  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 16:21:16.347  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:21:16.347  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 16:21:16.347  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 16:21:16.347  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 16:21:16.347  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-24 16:21:16.350  5907  5923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:21:16.350  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.350  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 16:21:16.350  5907  5926 ,D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:21:16.350  5907  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 16:21:16.357  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 16:21:16.357  5603  5650 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-24 16:21:16.357  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 16:21:16.358  5006  5983 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-24 16:21:16.359  5907  5923 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 16:21:16.359  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:21:16.362  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.362  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 16:21:16.362  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 16:21:16.363  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 16:21:16.363  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 16:21:16.363  5907  5923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 16:21:16.363  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:21:16.365  5907  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:21:16.366  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.367  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 16:21:16.367  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 16:21:16.367  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 16:21:16.367  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 16:21:16.367  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.367  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:21:16.369  5907  5923 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 16:21:16.369  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.369  5907  5923 E BtGatt.ContextMap: Context not found for ID 5
,11-24 16:21:16.371  5907  5942 D BtGatt.GattService: registerClient() - UUID=46e86a58-362d-4595-aa04-1236aa6616af
11-24 16:21:16.371  5907  5923 D BtGatt.GattService: onClientRegistered() - UUID=46e86a58-362d-4595-aa04-1236aa6616af, clientIf=5
11-24 16:21:16.371  5603  5613 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 16:21:16.372  5907  5918 D BtGatt.GattService: start scan with filters
,11-24 16:21:16.375  5907  5923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 16:21:16.375  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.375  5907  5926 D BtGatt.ScanManager: stopping BLe Batch
11-24 16:21:16.375  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 16:21:16.375  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.375  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 16:21:16.375  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.375  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 16:21:16.376  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 16:21:16.376  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.376  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 16:21:16.376  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 16:21:16.376  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.376  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.376  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.376  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.377  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 16:21:16.377  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.379  5907  5923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 16:21:16.379  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.379  5907  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 16:21:16.380  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.380  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 16:21:16.380  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.380  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.381  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.382  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 16:21:16.383  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:21:16.383  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:21:16.383  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:21:16.383  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.383  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:21:16.383  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.383  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.383  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce1149 removed from the list
11-24 16:21:16.383  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 16:21:16.383  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@877ca4e removed from the list
11-24 16:21:16.383  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
11-24 16:21:16.383  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.383  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:21:16.383  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.383  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.383  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 16:21:16.383  5603  5650 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 16:21:16.383  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 16:21:16.383  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.384  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.384  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.384  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.384  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 16:21:16.384  5907  5923 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 16:21:16.385  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.385  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.385  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.385  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.385  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.385  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:21:16.385  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.385  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@877ca4e not in the list
11-24 16:21:16.385  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 16:21:16.385  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.385  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 16:21:16.385  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 16:21:16.385  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.385  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.385  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.385  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 16:21:16.386  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.386  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:21:16.386  5907  5946 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 16:21:16.386  5907  5926 D BtGatt.ScanManager: handling starting scan
11-24 16:21:16.386  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 16:21:16.387  5603  5650 D BluetoothAdapter: STATE_ON
11-24 16:21:16.388  5907  5917 D BtGatt.GattService: stopScan() - queue size =1
,11-24 16:21:16.388  5907  5918 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.389  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 16:21:16.389  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 16:21:16.390  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 16:21:16.390  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.391  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.391  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:21:16.391  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.391  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.391  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:21:16.391  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.391  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.391  5907  5923 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 16:21:16.391  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 16:21:16.391  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.391  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0cfc7c removed from the list
11-24 16:21:16.391  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:21:16.391  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 16:21:16.391  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.392  5603  5603 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 16:21:16.392  5907  5926 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 16:21:16.392  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.392  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.392  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9176f removed from the list
11-24 16:21:16.392  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 16:21:16.392  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 16:21:16.392  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.392  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-24 16:21:16.392  5603  5603 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.392  5603  5603 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 16:21:16.392  5603  5603 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.392  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.392  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 16:21:16.392  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc1a081 added. We now have 3 listener(s)
11-24 16:21:16.393  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.393  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.393  5603  5603 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 16:21:16.393  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:21:16.393  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.393  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:21:16.393  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.394  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51ed526 added. We now have 4 listener(s)
11-24 16:21:16.394  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:21:16.394  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 16:21:16.395  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 16:21:16.395  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4768567 added. We now have 4 listener(s)
11-24 16:21:16.396  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-24 16:21:16.396  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 16:21:16.396  5603  5650 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 16:21:16.396  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 16:21:16.396  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c65f14 added. We now have 5 listener(s)
11-24 16:21:16.397  5603  5650 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 16:21:16.397  5603  5650 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 16:21:16.397  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 16:21:16.397  5603  5650 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 16:21:16.397  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:21:16.397  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.397  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.397  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bc1a081 removed from the list
11-24 16:21:16.397  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.397  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51ed526 removed from the list
11-24 16:21:16.397  5603  5650 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 16:21:16.398  5907  5923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 16:21:16.398  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.398  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.398  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.398  5907  5926 D BtGatt.ScanManager: Starting BLE batch scan
11-24 16:21:16.398  5907  5926 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 16:21:16.401  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.401  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.401  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.401  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.401  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:21:16.401  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.401  5603  5650 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51ed526 not in the list
11-24 16:21:16.401  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.401  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.402  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.402  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 16:21:16.402  5603  5650 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 16:21:16.402  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 16:21:16.402  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 16:21:16.402  5603  5650 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 16:21:16.402  5603  5650 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c65f14 removed from the list
11-24 16:21:16.402  5603  5650 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 16:21:16.402  5603  5650 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 16:21:16.402  5603  5650 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 16:21:16.402  5603  5650 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4768567 removed from the list
11-24 16:21:16.403  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 16:21:16.403  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-24 16:21:16.403  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 16:21:16.403  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:21:16.403  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 16:21:16.403  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 16:21:16.407  5907  5923 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 16:21:16.407  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:21:16.410  5907  5923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 16:21:16.410  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:21:16.411  5907  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:21:16.416  5907  5923 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 16:21:16.416  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.416  5907  5923 E BtGatt.ContextMap: Context not found for ID 5
,11-24 16:21:16.420  5907  5923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 16:21:16.420  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.421  5907  5926 D BtGatt.ScanManager: stopping BLe Batch
,11-24 16:21:16.425  5907  5923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 16:21:16.425  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 16:21:16.425  5907  5926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 16:21:16.429  5907  5923 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 16:21:16.429  5907  5923 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 16:21:16.797  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:21:16.844  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:21:16.893  5603  5603 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 16:21:17.125   619   619 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 16:21:18.562  5603  5989 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 16:21:18.562  5603  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:21:19.379  5603  5989 W !!      : call onHalfStreamCopied
,11-24 16:21:19.379  5603  5989 I testCopyDataAndClose: closing input stream
,11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 16:21:20.150  5603  5989 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 16:21:24.113   928  2977 D ConnectivityService: handlePromptUnvalidated 102
,11-24 16:21:24.576  5603  5990 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:21:24.576  5603  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:21:26.576  5603  5650 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-24 16:21:26.576  5603  5650 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:21:26.576  5603  5650 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-24 16:21:26.640  5603  5990 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 16:21:26.640  5603  5990 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:21:26.640  5603  5990 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,11-24 16:21:26.724  5603  5991 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 16:21:26.724  5603  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:21:27.217   928  2975 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-24 16:21:28.419  5603  5991 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 16:21:28.419  5603  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:21:28.419  5603  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 16:21:28.419  5603  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 16:21:28.420  5603  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-24 16:21:28.420  5603  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 16:21:28.420  5603  5991 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 16:21:28.420  5603  5991 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 16:21:28.420  5603  5991 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 16:21:28.420  5603  5991 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 16:21:28.420  5603  5991 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 16:21:32.611  5603  5992 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:21:32.611  5603  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:21:32.611  5603  5992 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:21:32.611  5603  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:21:32.611  5603  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 16:21:32.611  5603  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 16:21:32.611  5603  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 16:21:32.612  5603  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 16:21:32.612  5603  5992 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 16:21:32.612  5603  5992 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 16:21:32.612  5603  5992 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 16:21:32.612  5603  5992 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:21:32.612  5603  5992 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-24 16:21:32.614  5603  5650 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-24 16:21:32.617  5603  5993 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:21:32.617  5603  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 16:21:32.618  5603  5993 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-24 16:21:32.618  5603  5993 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:21:32.618  5603  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 16:21:32.618  5603  5993 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-24 16:21:32.619  5603  5993 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 16:21:32.619  5603  5993 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 16:21:32.622  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 16:21:32.622  5603  5650 I jxcore-log: 
,11-24 16:21:32.623  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG UnitTest_app: 'Number of passed tests:  81'
11-24 16:21:32.623  5603  5650 I jxcore-log: 
11-24 16:21:32.623  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG UnitTest_app: 'Number of failed tests:  1'
11-24 16:21:32.623  5603  5650 I jxcore-log: 
11-24 16:21:32.623  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 16:21:32.623  5603  5650 I jxcore-log: 
11-24 16:21:32.624  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG UnitTest_app: 'Total duration:  91993'
11-24 16:21:32.624  5603  5650 I jxcore-log: 
,11-24 16:21:32.625  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG UnitTest_app: 'Failures: 
11-24 16:21:32.625  5603  5650 I jxcore-log:  mCurrentOperation should not be null
11-24 16:21:32.625  5603  5650 I jxcore-log: Expected: is not null
11-24 16:21:32.625  5603  5650 I jxcore-log:      but: was null
11-24 16:21:32.625  5603  5650 I jxcore-log: '
11-24 16:21:32.625  5603  5650 I jxcore-log: 
11-24 16:21:32.625  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-24 16:21:32.625  5603  5650 I jxcore-log: 
,11-24 16:21:32.627  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 16:21:32.627  5603  5650 I jxcore-log: 
,11-24 16:21:32.630  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:21:32.630  5603  5650 I jxcore-log: 
,11-24 16:21:32.632  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:21:32.632  5603  5650 I jxcore-log: 
11-24 16:21:32.632  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 16:21:32.632  5603  5650 I jxcore-log: 
11-24 16:21:32.632  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 16:21:32.632  5603  5650 I jxcore-log: 
,11-24 16:21:32.633  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:21:32.633  5603  5650 I jxcore-log: 
11-24 16:21:32.633  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:21:32.633  5603  5650 I jxcore-log: 
11-24 16:21:32.633  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:21:32.633  5603  5650 I jxcore-log: 
11-24 16:21:32.633  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:21:32.633  5603  5650 I jxcore-log: 
,11-24 16:21:32.634  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:21:32.634  5603  5650 I jxcore-log: 
,11-24 16:21:32.634  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 16:21:32.634  5603  5650 I jxcore-log: 
11-24 16:21:32.635  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 16:21:32.635  5603  5650 I jxcore-log: 
11-24 16:21:32.635  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:21:32.635  5603  5650 I jxcore-log: 
11-24 16:21:32.635  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:21:32.635  5603  5650 I jxcore-log: 
11-24 16:21:32.635  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:21:32.635  5603  5650 I jxcore-log: 
11-24 16:21:32.635  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:21:32.635  5603  5650 I jxcore-log: 
11-24 16:21:32.636  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:21:32.636  5603  5650 I jxcore-log: 
11-24 16:21:32.636  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 16:21:32.636  5603  5650 I jxcore-log: 
11-24 16:21:32.636  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:21:32.636  5603  5650 I jxcore-log: 
,11-24 16:21:32.636  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 16:21:32.636  5603  5650 I jxcore-log: 
11-24 16:21:32.637  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 16:21:32.637  5603  5650 I jxcore-log: 
11-24 16:21:32.637  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:21:32.637  5603  5650 I jxcore-log: 
11-24 16:21:32.637  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 16:21:32.637  5603  5650 I jxcore-log: 
11-24 16:21:32.639  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 16:21:32.639  5603  5650 I jxcore-log: 
11-24 16:21:32.639  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 16:21:32.639  5603  5650 I jxcore-log: 
,11-24 16:21:32.639  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 16:21:32.639  5603  5650 I jxcore-log: 
11-24 16:21:32.640  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 16:21:32.640  5603  5650 I jxcore-log: 
11-24 16:21:32.640  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 16:21:32.640  5603  5650 I jxcore-log: 
11-24 16:21:32.640  5603  5650 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 16:21:32.640  5603  5650 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,11-24 16:21:32.641  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:21:32.641  5603  5650 I jxcore-log: 
11-24 16:21:32.641  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:21:32.641  5603  5650 I jxcore-log: 
11-24 16:21:32.641  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:21:32.641  5603  5650 I jxcore-log: 
11-24 16:21:32.641  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:21:32.641  5603  5650 I jxcore-log: 
,11-24 16:21:32.641  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 16:21:32.641  5603  5650 I jxcore-log: 
11-24 16:21:32.641  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 16:21:32.641  5603  5650 I jxcore-log: 
,11-24 16:21:32.647  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 16:21:32.647  5603  5650 I jxcore-log: 
11-24 16:21:32.647  5603  5603 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,11-24 16:21:32.647  5603  5650 I jxcore-log: 2016-11-24 15:21:32 - WARN testUtils: 'myNameCallback not set!'
11-24 16:21:32.647  5603  5650 I jxcore-log: 
11-24 16:21:32.647  5603  5603 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 16:21:34.730  5603  5650 I jxcore-log: 2016-11-24 15:21:34 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 16:21:34.730  5603  5650 I jxcore-log: 
,11-24 16:21:34.732  5603  5650 I jxcore-log: 2016-11-24 15:21:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 16:21:34.732  5603  5650 I jxcore-log: 
,11-24 16:21:35.091  5603  5650 I jxcore-log: 2016-11-24 15:21:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 16:21:35.091  5603  5650 I jxcore-log: 
,11-24 16:21:35.103  5603  5650 I jxcore-log: 2016-11-24 15:21:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 16:21:35.103  5603  5650 I jxcore-log: 
,11-24 16:21:36.038   928  5964 D NetlinkSocketObserver: NeighborEvent{elapsedMs=187857, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 16:21:36.221  5603  5650 I jxcore-log: 2016-11-24 15:21:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 16:21:36.221  5603  5650 I jxcore-log: 
,11-24 16:21:36.415  5603  5650 I jxcore-log: 2016-11-24 15:21:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 16:21:36.415  5603  5650 I jxcore-log: 
,11-24 16:21:36.421  5603  5650 I jxcore-log: 2016-11-24 15:21:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 16:21:36.421  5603  5650 I jxcore-log: 
,11-24 16:21:36.426  5603  5650 I jxcore-log: 2016-11-24 15:21:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 16:21:36.426  5603  5650 I jxcore-log: 
,11-24 16:21:36.910  5603  5650 I jxcore-log: 2016-11-24 15:21:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 16:21:36.910  5603  5650 I jxcore-log: 
,11-24 16:21:36.956  5603  5650 I jxcore-log: 2016-11-24 15:21:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 16:21:36.956  5603  5650 I jxcore-log: 
,11-24 16:21:36.969  5603  5650 I jxcore-log: 2016-11-24 15:21:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testSSDPServer.js'
11-24 16:21:36.969  5603  5650 I jxcore-log: 
,11-24 16:21:36.999  5603  5650 I jxcore-log: 2016-11-24 15:21:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 16:21:36.999  5603  5650 I jxcore-log: 
,11-24 16:21:37.003  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 16:21:37.003  5603  5650 I jxcore-log: 
,11-24 16:21:37.127   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:21:37.265  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 16:21:37.265  5603  5650 I jxcore-log: 
,11-24 16:21:37.392  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 16:21:37.392  5603  5650 I jxcore-log: 
,11-24 16:21:37.752  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 16:21:37.752  5603  5650 I jxcore-log: 
,11-24 16:21:37.760  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 16:21:37.760  5603  5650 I jxcore-log: 
,11-24 16:21:37.764  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 16:21:37.764  5603  5650 I jxcore-log: 
,11-24 16:21:37.770  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 16:21:37.770  5603  5650 I jxcore-log: 
,11-24 16:21:37.775  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 16:21:37.775  5603  5650 I jxcore-log: 
,11-24 16:21:37.803  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 16:21:37.803  5603  5650 I jxcore-log: 
,11-24 16:21:37.839  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 16:21:37.839  5603  5650 I jxcore-log: 
,11-24 16:21:37.846  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 16:21:37.846  5603  5650 I jxcore-log: 
,11-24 16:21:37.852  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 16:21:37.852  5603  5650 I jxcore-log: 
,11-24 16:21:37.869  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 16:21:37.869  5603  5650 I jxcore-log: 
,11-24 16:21:37.884  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 16:21:37.884  5603  5650 I jxcore-log: 
,11-24 16:21:37.890  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 16:21:37.890  5603  5650 I jxcore-log: 
,11-24 16:21:37.895  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 16:21:37.895  5603  5650 I jxcore-log: 
,11-24 16:21:37.908  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 16:21:37.908  5603  5650 I jxcore-log: 
,11-24 16:21:37.926  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 16:21:37.926  5603  5650 I jxcore-log: 
,11-24 16:21:37.940  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 16:21:37.940  5603  5650 I jxcore-log: 
,11-24 16:21:37.950  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 16:21:37.950  5603  5650 I jxcore-log: 
,11-24 16:21:37.963  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 16:21:37.963  5603  5650 I jxcore-log: 
,11-24 16:21:37.973  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 16:21:37.973  5603  5650 I jxcore-log: 
,11-24 16:21:37.987  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 16:21:37.987  5603  5650 I jxcore-log: 
,11-24 16:21:37.996  5603  5650 I jxcore-log: 2016-11-24 15:21:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 16:21:37.996  5603  5650 I jxcore-log: 
,11-24 16:21:38.003  5603  5650 I jxcore-log: 2016-11-24 15:21:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 16:21:38.003  5603  5650 I jxcore-log: 
,11-24 16:21:38.017  5603  5650 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 16:21:38.018  5603  5650 I jxcore-log: 2016-11-24 15:21:38 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 16:21:38.018  5603  5650 I jxcore-log: 
,11-24 16:21:38.049  5603  5650 I jxcore-log: 2016-11-24 15:21:38 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 16:21:38.049  5603  5650 I jxcore-log: 
,11-24 16:21:38.128   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:21:38.420  5603  5650 I jxcore-log: 2016-11-24 15:21:38 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 16:21:38.420  5603  5650 I jxcore-log: 
,11-24 16:21:38.711  5603  5650 I jxcore-log: 2016-11-24 15:21:38 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-24 16:21:38.711  5603  5650 I jxcore-log: 
,11-24 16:21:38.714  5603  5650 I jxcore-log: 2016-11-24 15:21:38 - DEBUG CoordinatedClient: 'test client failed'
11-24 16:21:38.714  5603  5650 I jxcore-log: 
,11-24 16:21:38.719  5603  5650 I jxcore-log: 2016-11-24 15:21:38 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 16:21:38.719  5603  5650 I jxcore-log: 
,11-24 16:21:38.725  5603  5650 I jxcore-log: 2016-11-24 15:21:38 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:190:20
11-24 16:21:38.725  5603  5650 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-24 16:21:38.725  5603  5650 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-24 16:21:38.725  5603  5650 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-24 16:21:38.725  5603  5650 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-24 16:21:38.725  5603  5650 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-24 16:21:38.725  5603  5650 I jxcore-log: 
,11-24 16:21:38.726  5603  5650 I jxcore-log: 2016-11-24 15:21:38 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 16:21:38.726  5603  5650 I jxcore-log: 
,11-24 16:21:39.129   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:21:39.287  6002  6002 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 16:21:39.308  6002  6002 D AndroidRuntime: CheckJNI is OFF
,11-24 16:21:39.336  6002  6002 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 16:21:39.366  6002  6002 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 16:21:39.382  6002  6002 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 16:21:39.392   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-24 16:21:39.392   928   941 I ActivityManager: Killing 5603:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 16:21:39.506   928  2976 D WifiService: Client connection lost with reason: 4
,11-24 16:21:39.506   928   939 D GraphicsStats: Buffer count: 2
11-24 16:21:39.506   928   939 I WindowState: WIN DEATH: Window{890a82e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 16:21:39.521   928   941 W ActivityManager: Force removing ActivityRecord{e89d6f7 u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-24 16:21:39.545   928   952 I art     : Starting a blocking GC Explicit
,11-24 16:21:39.552   928  3150 W ActivityManager: Spurious death for ProcessRecord{d79b2e5 0:com.test.thalitest/u0a77}, curProc for 5603: null
,11-24 16:21:39.575   928   939 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5603 uid 10077
,11-24 16:21:39.571   939   939 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[28154]" dev="sockfs" ino=28154 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:21:39.571   939   939 W Binder_2: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28154]" dev="sockfs" ino=28154 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 16:21:39.578  3659  3659 I Keyboard.Facilitator: onFinishInput()
,11-24 16:21:39.638   928   952 I art     : Explicit concurrent mark sweep GC freed 52973(3MB) AllocSpace objects, 9(272KB) LOS objects, 33% free, 29MB/43MB, paused 1.908ms total 92.833ms
,11-24 16:21:39.649  3975  6015 I MicroRecognitionRnrImpl: Starting detection.
,11-24 16:21:39.654  3975  6016 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@9a77042
,11-24 16:21:39.655   515  6018 I AudioFlinger: AudioFlinger's thread 0xf1c80000 ready to run
,11-24 16:21:39.656   928   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 16:21:39.660   515  2999 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 16:21:39.660  6002  6002 I art     : System.exit called, status: 0
11-24 16:21:39.661  6002  6002 I AndroidRuntime: VM exiting with result code 0.
,11-24 16:21:39.661  3975  6016 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@9a77042
,11-24 16:21:39.672   515  6018 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-24 16:21:39.672   515  6018 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-24 16:21:39.672   515  6018 I ACDB-LOADER: ACDB AFE returned = -19
11-24 16:21:39.672   515  6018 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-24 16:21:39.672   515  6018 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
,11-24 16:21:39.672   515  6018 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-24 16:21:39.678   515  6018 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-24 16:21:39.682   928   952 I ActivityManager: Start proc 6020:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-24 16:21:39.685   928   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 16:21:39.692  3659  3659 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-24 16:21:39.695  5907  5907 D BluetoothMapAppObserver: onReceive
11-24 16:21:39.695  5907  5907 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 16:21:39.705  3659  6033 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 16:21:39.714  4048  4186 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-24 16:21:39.716  3659  6033 I Decoder : createOrResetDecoder
,11-24 16:21:39.718   928  2936 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 16:21:39.719   928   941 I ActivityManager: Start proc 6035:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,11-24 16:21:39.761   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-24 16:21:39.763  3587  3587 I ConfigService: onCreate
,11-24 16:21:39.766  3975  3975 I HotwordWorkerImpl: onReady
,11-24 16:21:39.770  3815  3815 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 16:21:39.761    28    28 W kworker/2:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 16:21:39.764    28    28 W kworker/2:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 16:21:39.779  3830  3934 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-24 16:21:39.777    28    28 W kworker/2:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 16:21:39.790  3659  6033 I Keyboard.Facilitator.MainLanguageModelLoader: run()
11-24 16:21:39.793   928   938 I ActivityManager: Start proc 6050:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-24 16:21:39.794  3830  3934 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 16:21:39.794  3830  3934 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3830
11-24 16:21:39.794  3830  3934 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 16:21:39.794  3830  3934 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: Can't write: system_app_crash
11-24 16:21:39.797   928  6055 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 16:21:39.797   928  6055 E DropBoxManagerService: 	... 5 more
11-24 16:21:39.797   928   939 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 16:21:39.800  3975  3992 W SearchService: Abort, client detached.
,11-24 16:21:39.806  3975  3975 I HotwordDetector: Closing mic
,11-24 16:21:39.807  3975  4208 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@9a77042
,11-24 16:21:39.807  3975  6016 E AudioRecord-JNI: Error -4 during AudioRecord native read
,11-24 16:21:39.811  3882  3882 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[36883]" dev="sockfs" ino=36883 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:21:39.811  3882  3882 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[36883]" dev="sockfs" ino=36883 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:21:39.811   951   951 W Binder_3: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[32584]" dev="sockfs" ino=32584 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 16:21:39.814   951   951 W Binder_3: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[32584]" dev="sockfs" ino=32584 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 16:21:39.817   928  6063 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 16:21:39.819  6035  6035 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,11-24 16:21:39.859  3659  6033 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,11-24 16:21:39.859   928  6063 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 16:21:39.859   928  6063 I Adreno  : Build Date                       : 12/06/15
11-24 16:21:39.859   928  6063 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 16:21:39.859   928  6063 I Adreno  : Local Branch                     : mybranch17112971
11-24 16:21:39.859   928  6063 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 16:21:39.859   928  6063 I Adreno  : Remote Branch                    : NONE
11-24 16:21:39.859   928  6063 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 16:21:39.869   928  6063 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 16:21:39.872  3659  6033 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,11-24 16:21:39.873  3659  6033 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-24 16:21:39.877   515  6018 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,11-24 16:21:39.879   515  6018 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-24 16:21:39.882   515  6018 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-24 16:21:39.883   515  6018 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,11-24 16:21:39.885  3659  6033 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-24 16:21:39.884   515  2999 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-24 16:21:39.885  3659  6033 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-24 16:21:39.886  3659  6033 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-24 16:21:39.887  3659  6033 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-24 16:21:39.888  3975  4211 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-24 16:21:39.888  3975  6015 I MicroRecognitionRnrImpl: Detection finished
,11-24 16:21:39.894  3659  6033 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-24 16:21:39.894  3659  6033 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-24 16:21:39.895  3659  6033 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-24 16:21:39.895  3659  6033 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-24 16:21:39.895  3659  6033 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-24 16:21:39.895  3659  6033 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-24 16:21:39.943  6035  6035 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,11-24 16:21:39.962  6035  6073 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 16:21:39.963  5961  5961 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 16:21:40.130   619   619 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 16:21:40.172   386   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
