#### Test 9554107330bd934_thali07_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-28 18:57:09.618  3805  4158 I Icing   : Indexing 3C763AF371F9E97B4ECFEA01A338ADB468C38476 from com.google.android.googlequicksearchbox
,11-28 18:57:09.693  3805  4158 I Icing   : Indexing done 3C763AF371F9E97B4ECFEA01A338ADB468C38476
11-28 18:57:10.081  5564  5564 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-28 18:57:10.087  5564  5564 D AndroidRuntime: CheckJNI is OFF
11-28 18:57:10.115  5564  5564 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-28 18:57:10.148  5564  5564 I Radio-JNI: register_android_hardware_Radio DONE
11-28 18:57:10.163  5564  5564 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-28 18:57:10.166   929  3573 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-28 18:57:10.190  5564  5564 D AndroidRuntime: Shutting down VM
11-28 18:57:10.196  3932  3947 W SearchService: Abort, client detached.
11-28 18:57:10.208  3932  3932 I HotwordDetector: Closing mic
11-28 18:57:10.209  3932  4133 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@17084de
11-28 18:57:10.209  3932  4146 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-28 18:57:10.222   929  3377 I ActivityManager: Start proc 5573:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-28 18:57:10.277   513  4148 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-28 18:57:10.279   513  4148 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
11-28 18:57:10.285   513  4148 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-28 18:57:10.285   513  4148 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-28 18:57:10.286   513  2961 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 18:57:10.288  3932  4139 I MicroRecognitionRnrImpl: Stopping hotword detection.
11-28 18:57:10.288  3932  4145 I MicroRecognitionRnrImpl: Detection finished
11-28 18:57:10.319  5573  5573 I CordovaLog: Changing log level to DEBUG(3)
11-28 18:57:10.320  5573  5573 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-28 18:57:10.320  5573  5573 D CordovaActivity: CordovaActivity.onCreate()
11-28 18:57:10.324  5573  5573 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
11-28 18:57:10.344  5573  5573 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
11-28 18:57:10.410  5573  5573 I LibraryLoader: Time to load native libraries: 63 ms (timestamps 347-410)
11-28 18:57:10.411  5573  5573 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-28 18:57:10.447  5573  5573 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10a1ccf}
11-28 18:57:10.448  5573  5573 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-28 18:57:10.448  5573  5573 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-28 18:57:10.454  5573  5573 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-28 18:57:10.456  5573  5573 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-28 18:57:10.519  5573  5573 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-28 18:57:10.533  5573  5573 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-28 18:57:10.533  5573  5573 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-28 18:57:10.533  5573  5573 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-28 18:57:10.533  5573  5573 I Adreno  : Build Date                       : 12/06/15
11-28 18:57:10.533  5573  5573 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-28 18:57:10.533  5573  5573 I Adreno  : Local Branch                     : mybranch17112971
11-28 18:57:10.533  5573  5573 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-28 18:57:10.533  5573  5573 I Adreno  : Remote Branch                    : NONE
11-28 18:57:10.533  5573  5573 I Adreno  : Reconstruct Branch               : NOTHING
,11-28 18:57:10.598   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a1d0ca:true
,11-28 18:57:10.635   739   739 W Binder_4: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[26164]" dev="sockfs" ino=26164 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:57:10.635   739   739 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26164]" dev="sockfs" ino=26164 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 18:57:10.650  5573  5573 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-28 18:57:10.659  5573  5573 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-28 18:57:10.664  5573  5573 D PluginManager: init()
,11-28 18:57:10.667  5573  5573 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-28 18:57:10.683  5573  5573 D CordovaActivity: Started the activity.
,11-28 18:57:10.683  5573  5573 D CordovaActivity: Resumed the activity.
,11-28 18:57:10.685   739   739 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[31668]" dev="sockfs" ino=31668 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-28 18:57:10.685   739   739 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31668]" dev="sockfs" ino=31668 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:57:10.687  5573  5610 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-28 18:57:10.688  3740  3740 W Binder_9: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[26175]" dev="sockfs" ino=26175 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:57:10.688  3740  3740 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[26175]" dev="sockfs" ino=26175 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 18:57:10.691  5573  5597 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-28 18:57:10.714  5573  5610 I OpenGLRenderer: Initialized EGL, version 1.4
,11-28 18:57:10.792  3716  3716 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31674]" dev="sockfs" ino=31674 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 18:57:10.792  3716  3716 W Binder_8: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[31674]" dev="sockfs" ino=31674 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 18:57:10.793   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +593ms
,11-28 18:57:10.797  3623  3623 I Keyboard.Facilitator: onFinishInput()
,11-28 18:57:10.792  3716  3716 W Binder_8: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[31673]" dev="sockfs" ino=31673 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 18:57:10.792  3716  3716 W Binder_8: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[31673]" dev="sockfs" ino=31673 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:57:10.806  5573  5573 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-28 18:57:10.823  5573  5573 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5573
,11-28 18:57:10.931  5573  5573 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-28 18:57:11.103  5573  5612 D jxcore_app_log: JniHelper::setJavaVM(0xf50bc000), pthread_self() = -565184208
,11-28 18:57:11.109  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-28 18:57:11.109  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-28 18:57:11.109  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-28 18:57:11.109  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-28 18:57:11.109  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-28 18:57:11.109  5573  5612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b6b552 added. We now have 1 listener(s)
,11-28 18:57:11.114  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:D4
,11-28 18:57:11.119  5573  5612 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 18:57:11.119  5573  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:57:11.119  5573  5612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:D4
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-28 18:57:11.128  5573  5612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26492d9 added. We now have 1 listener(s)
11-28 18:57:11.128  5573  5612 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 18:57:11.137   929  2914 D WifiService: New client listening to asynchronous messages
,11-28 18:57:11.138  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 18:57:11.138  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-28 18:57:11.139  5573  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-28 18:57:11.139  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-28 18:57:11.139  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-28 18:57:11.139  5573  5612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-28 18:57:11.139  5573  5612 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-28 18:57:11.141  5573  5612 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-28 18:57:11.241  5573  5573 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-28 18:57:11.245  5573  5573 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-28 18:57:11.246  5573  5573 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-28 18:57:11.518  5573  5582 I art     : Background sticky concurrent mark sweep GC freed 76336(7MB) AllocSpace objects, 15(760KB) LOS objects, 22% free, 25MB/32MB, paused 1.757ms total 201.701ms
,11-28 18:57:11.758   929  2913 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 18:57:11.765  5573  5582 I art     : Background partial concurrent mark sweep GC freed 60312(6MB) AllocSpace objects, 3(1492KB) LOS objects, 36% free, 27MB/43MB, paused 1.538ms total 109.368ms
,11-28 18:57:11.880  5573  5620 W jxcore-log: Initializing JXcore engine
,11-28 18:57:11.880  5573  5620 W jxcore-log: JXcore engine is ready
,11-28 18:57:11.902  5620  5620 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12369 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-28 18:57:11.902  5620  5620 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[15532]" dev="sockfs" ino=15532 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-28 18:57:11.902  5620  5620 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-28 18:57:11.902  5620  5620 W Thread-61: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31647]" dev="sockfs" ino=31647 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-28 18:57:11.913  5573  5620 W jxcore-log: Starting JXcore engine
,11-28 18:57:11.963  5573  5620 W jxcore-log: Platform android
11-28 18:57:11.963  5573  5620 W jxcore-log: 
,11-28 18:57:11.963  5573  5620 W jxcore-log: Process ARCH arm
11-28 18:57:11.963  5573  5620 W jxcore-log: 
,11-28 18:57:12.147  5573  5620 I jxcore-log: JXcore Cordova bridge is ready!
11-28 18:57:12.147  5573  5620 I jxcore-log: 
,11-28 18:57:12.147  5573  5620 W jxcore-log: JXcore engine is started
,11-28 18:57:12.158  5573  5612 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-28 18:57:12.164  5573  5573 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-28 18:57:12.164  5573  5573 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-28 18:57:13.746  3513  3513 I ConfigService: onDestroy
,11-28 18:57:14.234   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:15.213   929  3376 I ActivityManager: Killing 5358:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-28 18:57:15.234   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:15.257   929  3376 I ActivityManager: Killing 5014:com.google.android.apps.maps/u0a58 (adj 15): empty #18
,11-28 18:57:16.235   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:17.236   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:18.237   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:19.238   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-28 18:57:21.855  5573  5620 I jxcore-log: 2016-11-28 17:57:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-28 18:57:21.855  5573  5620 I jxcore-log: 
,11-28 18:57:21.856  5573  5620 I jxcore-log: 2016-11-28 17:57:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-28 18:57:21.856  5573  5620 I jxcore-log: 
,11-28 18:57:21.861  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
11-28 18:57:21.862  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 18:57:21.862  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:21.862  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:21.862  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:57:21.862  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:57:21.862  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:57:21.862  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:57:21.862  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:57:21.862  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 18:57:21.863  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 18:57:21.865  5573  5620 I jxcore-log: 2016-11-28 17:57:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-28 18:57:21.865  5573  5620 I jxcore-log: 
11-28 18:57:21.867  5573  5620 I jxcore-log: 2016-11-28 17:57:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-28 18:57:21.867  5573  5620 I jxcore-log: 
,11-28 18:57:22.114  5573  5620 I jxcore-log: 2016-11-28 17:57:22 - DEBUG UnitTest_app: 'Running unit tests'
11-28 18:57:22.114  5573  5620 I jxcore-log: 
,11-28 18:57:22.115  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:57:22.115  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67c9b85 added. We now have 2 listener(s)
11-28 18:57:22.116  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:57:22.116  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:57:22.116  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:57:22.116  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 18:57:22.116  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@84eedda added. We now have 2 listener(s)
11-28 18:57:22.116  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:57:22.117  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 18:57:22.118  5573  5620 D executeNativeTests: Running unit tests
,11-28 18:57:22.160  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-28 18:57:22.160  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb added. We now have 3 listener(s)
11-28 18:57:22.161  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 18:57:22.161  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:57:22.161  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:57:22.161  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:57:22.161  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 added. We now have 3 listener(s)
11-28 18:57:22.161  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:57:22.162  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 18:57:22.164  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-28 18:57:22.164  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:57:22.164  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:57:22.164  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:57:22.165  5573  5620 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-28 18:57:22.165  5573  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 18:57:22.165  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 18:57:22.166  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:57:22.166  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:57:22.166  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:57:22.166  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:22.166  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:22.166  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:22.166  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:22.167  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:22.167  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:57:22.167  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb removed from the list
11-28 18:57:22.167  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:22.167  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 removed from the list
11-28 18:57:22.167  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:22.168  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.168  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.168  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.169  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.169  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.169  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:22.169  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:22.169  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:22.169  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.,thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:22.170  5573  5620 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-28 18:57:22.170  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:22.170  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:22.170  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:22.170  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:22.170  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:22.170  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:22.170  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:22.171  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:22.171  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:22.171  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:22.171  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.171  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.171  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:22.171  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.171  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-28 18:57:22.171  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-28 18:57:22.172  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:22.172  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
,11-28 18:57:22.174  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-28 18:57:22.174  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 18:57:22.174  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 18:57:22.174  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-28 18:57:22.174  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 18:57:22.174  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 18:57:22.174  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-28 18:57:22.174  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-28 18:57:22.174  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 18:57:22.175  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-28 18:57:22.175  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:22.175  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:22.175  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:22.175  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 18:57:22.175  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:22.175  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:22.176  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:22.176  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:22.176  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:57:22.176  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.176  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.177  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.177  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.177  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.177  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-28 18:57:22.177  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:22.177  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:22.177  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:22.177  5573  5620 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-28 18:57:22.178  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:57:22.179  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 18:57:22.186  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 18:57:22.186  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:22.186  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:22.186  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:57:22.186  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:57:22.186  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:57:22.186  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:57:22.186  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:57:22.186  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 18:57:22.187  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 18:57:22.187  5573  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
11-28 18:57:22.188  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:57:22.188  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 18:57:22.188  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 18:57:22.188  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 18:57:22.188  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 18:57:22.190  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 18:57:22.190  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:57:22.190  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 18:57:22.192  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 18:57:22.194  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 18:57:22.194  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:22.194  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 18:57:22.195  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:57:22.195  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:57:22.195  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-28 18:57:22.196  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-28 18:57:22.198  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-28 18:57:22.198  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:22.198  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 18:57:22.198  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 18:57:22.198  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 18:57:22.198  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 18:57:22.198  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.199  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:57:22.201  4611  4626 D BtGatt.GattService: registerClient() - UUID=239ad0b9-1c09-4d51-bc59-b409b317436f
,11-28 18:57:22.202  4611  4675 D BtGatt.GattService: onClientRegistered() - UUID=239ad0b9-1c09-4d51-bc59-b409b317436f, clientIf=5
,11-28 18:57:22.203  5573  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-28 18:57:22.204  4611  4836 D BtGatt.GattService: start scan with filters
,11-28 18:57:22.208  4611  4678 D BtGatt.ScanManager: handling starting scan
11-28 18:57:22.208  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 18:57:22.208  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.208  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 18:57:22.208  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.209  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 18:57:22.209  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:57:22.209  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:57:22.209  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 18:57:22.209  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:57:22.209  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.209  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-28 18:57:22.209  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:57:22.210  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 18:57:22.210  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:57:22.210  4611  4678 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:57:22.210  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 18:57:22.210  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.210  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.210  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:22.211  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:57:22.211  5573  5620 I io.jxcore.node.ConnectionHelper: start: OK
11-28 18:57:22.214  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:57:22.214  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:57:22.215  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:22.215  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:22.215  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-28 18:57:22.218  4611  4675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 18:57:22.218  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:22.219  4611  4678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-28 18:57:22.226  4611  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 18:57:22.226  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:57:22.227  4611  4678 D BtGatt.ScanManager: Starting BLE batch scan
11-28 18:57:22.227  4611  4678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 18:57:22.239  4611  4675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 18:57:22.239  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:57:22.245  4611  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-28 18:57:22.245  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:57:22.716  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-28 18:57:22.717  5573  5573 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:57:22.717  5573  5573 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 18:57:23.055   929  2915 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 18:57:23.060   929  2915 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-28 18:57:26.087   929  2915 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 18:57:26.095   929  2915 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-28 18:57:27.215  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 18:57:27.215  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:27.215  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 18:57:27.216  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-28 18:57:27.216  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 18:57:27.216  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:27.216  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 18:57:27.216  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:57:27.216  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.216  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:57:27.217  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:57:27.217  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.217  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.218  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.218  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-28 18:57:27.218  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.219  5573  5620 D BluetoothAdapter: STATE_ON
,11-28 18:57:27.219  4611  4836 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-28 18:57:27.220  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:57:27.220  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:57:27.221  4611  4826 D BtGatt.GattService: stopScan() - queue size =1
11-28 18:57:27.221  4611  4678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 18:57:27.222  4611  4626 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:57:27.222  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:57:27.222  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.223  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 18:57:27.223  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.223  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.223  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.223  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.223  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:57:27.224  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.224  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.224  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.224  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 18:57:27.224  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 18:57:27.225  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:57:27.225  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.226  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.226  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:57:27.227  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.227  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:27.227  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:27.227  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:57:27.227  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:57:27.227  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:57:27.227  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:27.227  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:27.227  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:27.227  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:57:27.228  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:27.228  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:27.228  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 18:57:27.228  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:57:27.228  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-28 18:57:27.228  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:57:27.228  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 18:57:27.228  4611  4611 D BtGatt.ScanManager: awakened up at time 97229
11-28 18:57:27.229  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:57:27.229  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 18:57:27.229  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:57:27.229  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:57:27.230  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:57:27.230  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:57:27.233  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:57:27.234  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:27.234  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 18:57:27.286  4611  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-28 18:57:27.286  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:27.287  4611  4675 D BtGatt.GattService: current time is 97287607616
11-28 18:57:27.287  4611  4675 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -79, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -92, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -85, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -88, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 18:57:27.289  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-28 18:57:27.292  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 18:57:27.292  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-28 18:57:27.292  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-28 18:57:27.292  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-28 18:57:27.293  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,11-28 18:57:27.298  4611  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 18:57:27.298  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:27.298  4611  4678 D BtGatt.ScanManager: stopping BLe Batch
,11-28 18:57:27.303  4611  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-28 18:57:27.303  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:27.303  4611  4678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:57:27.308  4611  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 18:57:27.308  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:57:27.311  3932  5622 W CronetSyncConnectionRcs: Upload content type not set.
,11-28 18:57:27.383  4796  4855 D Finsky  : [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-28 18:57:27.384  4796  4796 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-28 18:57:27.731  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 18:57:31.761   929  2913 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-28 18:57:32.278  5573  5620 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-28 18:57:32.284  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 18:57:32.285  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 18:57:32.299  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 18:57:32.299  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:32.299  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:32.299  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:57:32.299  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:57:32.299  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:57:32.299  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:57:32.299  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:57:32.299  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 18:57:32.304  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 18:57:32.305  5573  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
11-28 18:57:32.305  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:57:32.305  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 18:57:32.305  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 18:57:32.305  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 18:57:32.306  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 18:57:32.313  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:57:32.316  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 18:57:32.317  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:57:32.317  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 18:57:32.319  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:57:32.324  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:32.325  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-28 18:57:32.326  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:57:32.326  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-28 18:57:32.326  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-28 18:57:32.334  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.334  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-28 18:57:32.334  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 18:57:32.334  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 18:57:32.334  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 18:57:32.334  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:32.335  5573  5620 D BluetoothAdapter: STATE_ON
,11-28 18:57:32.340  4611  4626 D BtGatt.GattService: registerClient() - UUID=79333add-68bc-4482-a50c-80791809f7c2
11-28 18:57:32.341  4611  4675 D BtGatt.GattService: onClientRegistered() - UUID=79333add-68bc-4482-a50c-80791809f7c2, clientIf=5
,11-28 18:57:32.341  5573  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 18:57:32.342  4611  4836 D BtGatt.GattService: start scan with filters
,11-28 18:57:32.347  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-28 18:57:32.347  4611  4678 D BtGatt.ScanManager: handling starting scan
11-28 18:57:32.347  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.348  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 18:57:32.348  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.348  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-28 18:57:32.348  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:57:32.348  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.348  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-28 18:57:32.348  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:57:32.348  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.348  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.349  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.349  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.350  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:57:32.350  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:32.354  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.354  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:57:32.354  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.354  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.355  5573  5620 I io.jxcore.node.ConnectionHelper: start: OK
11-28 18:57:32.355  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.357  4611  4675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 18:57:32.357  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.357  4611  4678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 18:57:32.359  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.359  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.359  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.359  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:32.359  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:57:32.360  5573  5620 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 18:57:32.360  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:32.360  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 18:57:32.360  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:57:32.360  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 18:57:32.360  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:32.360  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 18:57:32.360  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:57:32.360  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.360  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:57:32.360  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:57:32.361  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.361  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.361  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.361  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 18:57:32.361  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.362  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:57:32.363  4611  4826 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 18:57:32.363  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:57:32.364  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:57:32.364  4611  4624 D BtGatt.GattService: stopScan() - queue size =1
11-28 18:57:32.366  4611  4626 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:57:32.366  4611  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 18:57:32.366  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.366  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:57:32.366  4611  4678 D BtGatt.ScanManager: Starting BLE batch scan
11-28 18:57:32.366  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.366  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 18:57:32.366  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.366  4611  4678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 18:57:32.367  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.367  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.367  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.367  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:57:32.367  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.367  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.367  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.367  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 18:57:32.367  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 18:57:32.368  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:57:32.368  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.370  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.370  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:57:32.370  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.370  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.370  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:32.370  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:57:32.370  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:57:32.370  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:57:32.370  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:57:32.370  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:32.370  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:57:32.370  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:32.370  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:32.370  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.370  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:32.370  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:57:32.370  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:32.371  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 18:57:32.371  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 18:57:32.371  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.371  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.371  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.371  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:57:32.371  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.371  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.374  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.374  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.374  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.374  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.374  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.376  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.376  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.376  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.376  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:32.376  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:32.376  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:32.376  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:32.377  5573  5620 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-28 18:57:32.379  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:57:32.379  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-28 18:57:32.380  4611  4675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 18:57:32.380  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.385  4611  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 18:57:32.386  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.387  4611  4678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 18:57:32.387  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 18:57:32.387  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:32.387  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:32.387  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:57:32.387  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:57:32.387  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:57:32.387  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:57:32.387  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:57:32.387  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 18:57:32.389  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-28 18:57:32.390  5573  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
11-28 18:57:32.390  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:57:32.390  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 18:57:32.390  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 18:57:32.390  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:57:32.390  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 18:57:32.393  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 18:57:32.393  4611  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 18:57:32.394  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.394  4611  4675 E BtGatt.ContextMap: Context not found for ID 5
11-28 18:57:32.395  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 18:57:32.395  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:57:32.395  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 18:57:32.397  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 18:57:32.400  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.400  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 18:57:32.400  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:57:32.400  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:57:32.401  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-28 18:57:32.401  4611  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 18:57:32.402  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.402  4611  4678 D BtGatt.ScanManager: stopping BLe Batch
11-28 18:57:32.405  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.405  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 18:57:32.405  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 18:57:32.405  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 18:57:32.405  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 18:57:32.405  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.405  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:57:32.407  4611  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-28 18:57:32.407  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.407  4611  4678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 18:57:32.407  4611  4826 D BtGatt.GattService: registerClient() - UUID=6f312234-2858-413d-9037-39257b173b15
11-28 18:57:32.408  4611  4675 D BtGatt.GattService: onClientRegistered() - UUID=6f312234-2858-413d-9037-39257b173b15, clientIf=5
11-28 18:57:32.408  5573  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 18:57:32.409  4611  4836 D BtGatt.GattService: start scan with filters
11-28 18:57:32.412  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-28 18:57:32.412  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.412  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 18:57:32.412  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.412  4611  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 18:57:32.412  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 18:57:32.412  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.412  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:57:32.412  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.412  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 18:57:32.413  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:57:32.413  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.413  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.413  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.413  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.413  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:57:32.413  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.414  4611  4678 D BtGatt.ScanManager: handling starting scan
11-28 18:57:32.416  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.416  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:57:32.417  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.417  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:32.417  5573  5620 I io.jxcore.node.ConnectionHelper: start: OK
11-28 18:57:32.417  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.419  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.419  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.420  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:32.420  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:57:32.420  4611  4675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 18:57:32.420  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.420  4611  4678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 18:57:32.425  4611  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 18:57:32.425  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:32.425  4611  4678 D BtGatt.ScanManager: Starting BLE batch scan
11-28 18:57:32.425  4611  4678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 18:57:32.434  4611  4675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 18:57:32.434  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:57:32.439  4611  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 18:57:32.439  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:57:32.921  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-28 18:57:32.921  5573  5573 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-28 18:57:32.922  5573  5573 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 18:57:35.153   929  2915 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 18:57:35.158   929  2915 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-28 18:57:37.417  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 18:57:37.418  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-28 18:57:37.418  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-28 18:57:37.418  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:57:37.418  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-28 18:57:37.418  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:37.418  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 18:57:37.418  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 18:57:37.419  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.419  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:57:37.419  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-28 18:57:37.420  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:37.420  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.420  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.420  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 18:57:37.420  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.423  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:57:37.423  4611  4626 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 18:57:37.424  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:57:37.425  4611  4678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:57:37.426  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:57:37.428  4611  4826 D BtGatt.GattService: stopScan() - queue size =1
,11-28 18:57:37.430  4611  4836 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:57:37.431  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:57:37.431  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.431  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 18:57:37.432  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:37.432  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.432  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.432  4611  4611 D BtGatt.ScanManager: awakened up at time 107433
11-28 18:57:37.432  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.432  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:57:37.433  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:37.433  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.433  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.433  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 18:57:37.433  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 18:57:37.435   929   940 I ActivityManager: Killing 5370:com.android.chrome/u0a39 (adj 15): empty #17
,11-28 18:57:37.458  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:57:37.458  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:37.460  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:37.461  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:57:37.461  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.461  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:37.461  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:57:37.461  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:57:37.461  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:57:37.461  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:57:37.461  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-28 18:57:37.462  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 18:57:37.462  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:57:37.462  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 18:57:37.462  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:57:37.462  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:57:37.462  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:57:37.462  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:57:37.463  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-28 18:57:37.463  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:57:37.463  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 18:57:37.471  4611  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-28 18:57:37.471  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:37.471  4611  4675 D BtGatt.GattService: current time is 107471983320
11-28 18:57:37.471  4611  4675 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -80, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -87, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -98, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -88, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 18:57:37.471  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-28 18:57:37.472  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-28 18:57:37.472  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-28 18:57:37.472  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,11-28 18:57:37.472  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-28 18:57:37.472  4611  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-28 18:57:37.478  4611  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 18:57:37.478  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:37.478  4611  4678 D BtGatt.ScanManager: stopping BLe Batch
11-28 18:57:37.482  4611  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-28 18:57:37.483  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:57:37.483  4611  4678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:57:37.487  4611  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 18:57:37.487  4611  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:57:37.962  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 18:57:37.963  5573  5573 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:37.963  5573  5573 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-28 18:57:38.182   929  2915 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-28 18:57:38.188   929  2915 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-28 18:57:42.463  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 18:57:42.463  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-28 18:57:42.463  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:42.463  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 18:57:42.464  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:57:42.464  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:57:42.464  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:42.464  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
,11-28 18:57:42.464  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.464  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.465  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:42.465  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 18:57:42.468  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.468  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.471  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.471  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.471  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.472  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-28 18:57:42.472  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:42.472  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.472  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.473  5573  5620 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-28 18:57:42.475  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:42.475  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-28 18:57:42.475  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:42.476  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.476  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:42.476  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:42.476  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:57:42.476  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.476  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:42.477  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.477  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.480  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.480  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.480  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.480  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:42.480  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:42.480  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.481  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
,11-28 18:57:42.483  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 18:57:42.483  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:42.483  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:42.483  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:42.483  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.484  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 18:57:42.484  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:42.484  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.484  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.484  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:42.484  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.484  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.487  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.487  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.487  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.487  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:42.487  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-28 18:57:42.488  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.488  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
,11-28 18:57:42.489  5573  5620 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-28 18:57:42.490  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:42.490  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-28 18:57:42.490  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:42.490  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.490  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:42.491  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:42.491  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.491  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
,11-28 18:57:42.491  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:57:42.491  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.492  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.494  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.494  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.494  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.494  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:42.495  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-28 18:57:42.495  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.495  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
,11-28 18:57:42.497  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-28 18:57:42.497  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 18:57:42.497  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:42.497  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:42.497  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.497  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:42.497  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
,11-28 18:57:42.498  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.498  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.498  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:42.498  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.498  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.500  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.501  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.501  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:42.501  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:42.501  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.501  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.502  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 18:57:42.502  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:57:42.503  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-28 18:57:42.503  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 18:57:42.503  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:57:42.503  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:57:42.503  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-28 18:57:42.503  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-28 18:57:42.503  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-28 18:57:42.503  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:42.504  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:42.504  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:42.504  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.504  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:42.504  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:42.504  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:57:42.504  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.504  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:42.504  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.504  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.506  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.506  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.506  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.506  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:42.507  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:42.507  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.507  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.508  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:57:42.508  5573  5620 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-28 18:57:42.508  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-28 18:57:42.513  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:57:42.513  5573  5620 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,11-28 18:57:42.513  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-28 18:57:42.513  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-28 18:57:42.513  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-28 18:57:42.513  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-28 18:57:42.514  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-28 18:57:42.515  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-28 18:57:42.516  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,11-28 18:57:42.516  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-28 18:57:42.517  5573  5620 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 18:57:42.517  5573  5620 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-28 18:57:42.517  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:57:42.517  5573  5620 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 18:57:42.517  5573  5620 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-28 18:57:42.517  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:57:42.518  5573  5620 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-28 18:57:42.518  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-28 18:57:42.522  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-28 18:57:42.524  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-28 18:57:42.524  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-28 18:57:42.524  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-28 18:57:42.525  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,11-28 18:57:42.525  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-28 18:57:42.525  5573  5620 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-28 18:57:42.525  5573  5620 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-28 18:57:42.525  5573  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-28 18:57:42.525  5573  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
,11-28 18:57:42.525  5573  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-28 18:57:42.525  5573  5626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-28 18:57:42.526  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:42.526  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:42.526  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:42.527  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.527  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 18:57:42.527  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-28 18:57:42.528  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:42.528  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.528  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.528  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:42.528  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.529  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.529  5573  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-28 18:57:42.529  5573  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-28 18:57:42.530  5573  5626 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-28 18:57:42.531  5573  5626 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:57:42.532  4626  4626 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32847]" dev="sockfs" ino=32847 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 18:57:42.532  4626  4626 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32847]" dev="sockfs" ino=32847 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 18:57:42.531  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.531  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.531  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.531  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:42.531  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:42.531  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:57:42.532  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.533  5573  5620 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-28 18:57:42.534  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:42.534  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:42.534  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:42.534  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.534  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:42.535  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:42.535  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.535  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.535  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:42.535  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.535  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.537  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.537  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.537  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.537  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:42.537  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:42.537  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.537  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
,11-28 18:57:42.538  5573  5620 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-28 18:57:42.538  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:42.539  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:42.539  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:42.539  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.539  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-28 18:57:42.539  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:42.539  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:42.539  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.539  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:42.540  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.540  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.545  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.545  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:42.545  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:42.546  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:57:42.546  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
,11-28 18:57:42.546  5573  5620 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,11-28 18:57:42.547  5573  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-28 18:57:42.547  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 18:57:42.547  5573  5620 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-28 18:57:42.547  5573  5620 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 18:57:42.547  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,11-28 18:57:42.547  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 18:57:42.547  5573  5620 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-28 18:57:42.547  5573  5620 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-28 18:57:42.547  5573  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,11-28 18:57:42.547  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 18:57:42.547  5573  5620 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-28 18:57:42.547  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:42.547  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:42.548  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-28 18:57:42.548  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.548  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:42.548  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:42.548  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:57:42.548  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.548  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:42.548  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.548  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.549  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:42.549  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.549  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:42.549  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:42.549  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:42.549  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:57:42.550  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.551  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:42.551  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:42.551  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:42.551  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:57:42.551  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:42.551  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:57:44.239   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-28 18:57:44.239   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-28 18:57:47.552  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:57:47.552  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.552  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:47.553  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:47.553  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
,11-28 18:57:47.553  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:47.553  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:47.553  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:47.554  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 18:57:47.554  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:47.554  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:47.554  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.554  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
,11-28 18:57:47.554  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:47.555  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.555  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:47.560  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.561  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:47.561  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.561  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-28 18:57:47.562  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:47.562  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.562  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
,11-28 18:57:47.569  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-28 18:57:47.569  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:57:47.570  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
,11-28 18:57:47.575  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-28 18:57:47.577  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-28 18:57:47.577  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-28 18:57:47.577  5573  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-28 18:57:47.577  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-28 18:57:47.578  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-28 18:57:47.578  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-28 18:57:47.578  5573  5573 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-28 18:57:47.579  5573  5628 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:57:47.579  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:47.580  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-28 18:57:47.580  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-28 18:57:47.580  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-28 18:57:47.580  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 18:57:47.582  4826  4826 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[30539]" dev="sockfs" ino=30539 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 18:57:47.582  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-28 18:57:47.582  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-28 18:57:47.583  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:47.583  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.583  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-28 18:57:47.583  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.583  5573  5573 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-28 18:57:47.583  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:57:47.582  4826  4826 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[30539]" dev="sockfs" ino=30539 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-28 18:57:47.583  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:57:47.584  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.584  5573  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-28 18:57:47.584  5573  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-28 18:57:47.584  5573  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-28 18:57:47.588  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.588  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:57:47.588  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.588  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:57:47.589  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:57:47.589  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:57:47.589  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.589  5573  5573 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-28 18:57:47.589  5573  5573 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:47.589  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:47.589  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:57:47.590  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:47.590  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:47.590  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:47.590  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:47.590  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:47.591  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.591  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.591  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:47.591  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.592  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.594  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.595  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.595  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.595  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:47.595  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:47.595  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.595  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.598  5573  5620 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-28 18:57:47.598  5573  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-28 18:57:47.598  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-28 18:57:47.598  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:57:47.598  5573  5620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-28 18:57:47.599  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:47.599  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:47.599  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:47.599  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:47.599  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:47.599  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:47.600  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.600  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.600  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:47.601  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.601  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.603  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.603  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.604  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.604  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:47.604  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:47.604  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.604  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.611  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:47.612  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:47.612  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:47.612  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:47.612  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:47.612  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:47.612  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.612  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.612  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:47.612  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.612  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.614  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.614  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.614  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.614  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:47.614  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:47.614  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.614  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.616  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:57:47.616  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:57:47.616  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:57:47.616  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:57:47.616  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:57:47.617  5573  5620 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8163fb not in the list
11-28 18:57:47.617  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.617  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.617  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:47.617  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.617  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.618  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.618  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.618  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:57:47.618  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:57:47.619  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:57:47.619  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:47.619  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b03c18 not in the list
11-28 18:57:47.620  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-28 18:57:47.620  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 18:57:47.620  5573  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-28 18:57:47.620  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-28 18:57:47.620  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-28 18:57:47.620  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-28 18:57:47.622  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-28 18:57:47.622  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-28 18:57:47.623  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-28 18:57:47.623  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 18:57:47.623  5573  5620 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-28 18:57:47.623  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-28 18:57:47.623  5573  5620 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-28 18:57:47.623  5573  5620 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-28 18:57:47.624  5573  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-28 18:57:47.624  5573  5620 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-28 18:57:47.624  5573  5620 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-28 18:57:47.624  5573  5620 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-28 18:57:47.624  5573  5620 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-28 18:57:47.624  5573  5620 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-28 18:57:47.625  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:57:47.625  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@adb7de1 added. We now have 3 listener(s)
11-28 18:57:47.625  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:57:47.628  5573  5620 D BluetoothAdapter: enable(): BT is already enabled..!
11-28 18:57:47.628   929   939 D WifiService: setWifiEnabled: true pid=5573, uid=10077
11-28 18:57:47.628   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:57:47.661  4611  4821 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
11-28 18:57:47.662  5573  5626 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-28 18:57:47.662  5573  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-28 18:57:47.662  5573  5626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-28 18:57:47.662  4611  4823 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-28 18:57:48.090  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 18:57:49.240   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:50.241   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:51.242   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:52.243   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:52.633  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 18:57:52.634  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd55706 added. We now have 4 listener(s)
,11-28 18:57:52.634  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 18:57:52.648  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:57:52.648  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd55706 removed from the list
,11-28 18:57:52.649  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:57:52.651  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 18:57:52.651  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bfe11c7 added. We now have 4 listener(s)
,11-28 18:57:52.651  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 18:57:52.654  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:57:52.655  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bfe11c7 removed from the list
,11-28 18:57:52.655  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:57:52.657  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:57:52.658  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b8263f4 added. We now have 4 listener(s)
,11-28 18:57:52.658  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 18:57:52.663   929  3376 D WifiService: setWifiEnabled: false pid=5573, uid=10077
,11-28 18:57:52.663   929  3376 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:57:52.671   929  2913 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-28 18:57:52.671   929  2913 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-28 18:57:52.672   929  2913 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 18:57:52.673   929  2913 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 18:57:52.675  4611  4671 D BluetoothAdapterState: Current state: ON, message: 23
,11-28 18:57:52.675  4611  4671 D BluetoothAdapterProperties: Setting state to 13
11-28 18:57:52.675  4611  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-28 18:57:52.676  4611  4671 D BluetoothAdapterProperties: onBluetoothDisable()
11-28 18:57:52.677  4611  4671 I BluetoothAdapterState: Entering PendingCommandState
,11-28 18:57:52.677  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:57:52.677  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-28 18:57:52.679  4611  4675 D BluetoothAdapterProperties: Scan Mode:20
11-28 18:57:52.681  4611  4611 D BluetoothMapService: onReceive
11-28 18:57:52.681  4611  4611 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 18:57:52.681  4611  4611 D BluetoothMapService: STATE_TURNING_OFF
11-28 18:57:52.681  4611  4611 D BluetoothMapService: MAP Service closeService in
,11-28 18:57:52.681  4611  4611 D BluetoothMapMasInstance0: MAP Service shutdown
11-28 18:57:52.682  4611  4611 D ObexServerSockets0: shutdown(block = true)
,11-28 18:57:52.682  4611  4611 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-28 18:57:52.683  4611  4837 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-28 18:57:52.683  4611  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-28 18:57:52.683  4611  4611 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 18:57:52.684  4611  4823 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-28 18:57:52.688  4611  4838 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-28 18:57:52.689   929  5330 D DhcpClient: Clearing IP address
11-28 18:57:52.690   508   924 D CommandListener: Setting iface cfg
11-28 18:57:52.691  4611  4611 I BtOppRfcommListener: stopping Accept Thread
11-28 18:57:52.691  4611  5260 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-28 18:57:52.691  4611  5260 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-28 18:57:52.692   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-28 18:57:52.698   929   942 I ActivityManager: Start proc 5632:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-28 18:57:52.703   929  5331 D DhcpClient: Receive thread stopped
11-28 18:57:52.703  3513  5383 V NativeCrypto: Read error: ssl=0x7f69ac5700: I/O error during system call, Connection timed out
,11-28 18:57:52.705  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 18:57:52.706  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-28 18:57:52.706  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:52.706  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:52.706  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:57:52.706  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:57:52.706  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:57:52.706  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:57:52.706  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:57:52.706  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 18:57:52.706  4611  4611 D HeadsetService: Received stop request...Stopping profile...
,11-28 18:57:52.706  3513  5383 V NativeCrypto: SSL shutdown failed: ssl=0x7f69ac5700: I/O error during system call, Broken pipe
11-28 18:57:52.707  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 18:57:52.707  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 18:57:52.707  5573  5620 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-28 18:57:52.707   929   929 D BluetoothHeadset: Proxy object disconnected
11-28 18:57:52.708  3730  3747 D BluetoothHeadset: Proxy object disconnected
11-28 18:57:52.708  4611  4611 D A2dpService: Received stop request...Stopping profile...
11-28 18:57:52.708   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-28 18:57:52.708  4611  4828 D A2dpStateMachine: Exit Disconnected: -1
11-28 18:57:52.708   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-28 18:57:52.710   929   929 D BluetoothHeadset: Proxy object disconnected
11-28 18:57:52.710  3061  3279 D BluetoothHeadset: Proxy object disconnected
11-28 18:57:52.711   929   929 D BluetoothHeadset: Proxy object disconnected
11-28 18:57:52.711  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:57:52.711  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:57:52.711  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:52.711  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:52.711  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:57:52.711  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:57:52.711  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:57:52.711  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: <unknown ssid>
11-28 18:57:52.711  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:57:52.711  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 18:57:52.712  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:57:52.712  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: <unknown ssid>
11-28 18:57:52.713  3061  3061 D HeadsetProfile: Bluetooth service disconnected
11-28 18:57:52.714   929   929 D BluetoothA2dp: Proxy object disconnected
11-28 18:57:52.715   534   534 E Parcel  : Reading a NULL string not supported here.
11-28 18:57:52.715   929   929 D RttService: SCAN_AVAILABLE : 1
11-28 18:57:52.715   929  2915 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-28 18:57:52.716   929  3021 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 18:57:52.719  3697  3829 W QCNEJ   : |CORE| network lost: 100
11-28 18:57:52.720  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:57:52.720  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:57:52.720  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:52.720  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:52.720  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:57:52.720  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:57:52.720  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:57:52.720  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:57:52.720  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:57:52.720  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 18:57:52.720  4611  4611 V BluetoothAdapterState: isTurningOff()=true
11-28 18:57:52.720  4611  4611 V BluetoothAdapterState: isTurningOn()=false
11-28 18:57:52.720  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:57:52.720  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:57:52.721   929  2913 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-28 18:57:52.721  4611  4611 D HidService: Received stop request...Stopping profile...
11-28 18:57:52.721  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 18:57:52.721  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 18:57:52.721  4611  4611 D HidService: Stopping Bluetooth HidService
,11-28 18:57:52.722  3697  3829 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-28 18:57:52.724  4611  4611 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-28 18:57:52.724  4611  4611 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-28 18:57:52.724  4611  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:57:52.725  4611  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:57:52.725  4611  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:57:52.725  4611  4611 D HealthService: Received stop request...Stopping profile...
11-28 18:57:52.725  3061  3061 D BluetoothA2dp: Proxy object disconnected
11-28 18:57:52.726  4611  4611 V BluetoothAdapterState: isTurningOff()=true
11-28 18:57:52.726  4611  4611 V BluetoothAdapterState: isTurningOn()=false
,11-28 18:57:52.726  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:57:52.726  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:57:52.726  3061  3061 D BluetoothInputDevice: Proxy object disconnected
11-28 18:57:52.726  3061  3061 D HidProfile: Bluetooth service disconnected
11-28 18:57:52.726  4611  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-28 18:57:52.726  4611  4675 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-28 18:57:52.726  4611  4611 D PanService: Received stop request...Stopping profile...
11-28 18:57:52.727  3061  3061 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-28 18:57:52.727  3061  3061 D PanProfile: Bluetooth service disconnected
11-28 18:57:52.729  4611  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-28 18:57:52.729  4611  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:57:52.729  4611  4611 D BluetoothMapService: Received stop request...Stopping profile...
11-28 18:57:52.730  4611  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:57:52.730  4611  4611 D BluetoothMapService: stop()
11-28 18:57:52.730  4611  4821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 18:57:52.730  4611  4821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 18:57:52.730  4611  4821 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 18:57:52.730  4611  4821 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 18:57:52.731   929  2913 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 18:57:52.731  4611  4611 D BluetoothMapAppObserver: deinitObservers()
11-28 18:57:52.731  4611  4611 D BluetoothMapAppObserver: removeReceiver()
11-28 18:57:52.732  3061  3061 D BluetoothMap: Proxy object disconnected
11-28 18:57:52.732  3061  3061 D MapProfile: Bluetooth service disconnected
,11-28 18:57:52.733  4611  4611 D SapService: Received stop request...Stopping profile...
,11-28 18:57:52.733  4611  4611 V SapService: stop()
11-28 18:57:52.734  4611  4611 V BluetoothAdapterState: isTurningOff()=true
11-28 18:57:52.734  4611  4611 V BluetoothAdapterState: isTurningOn()=false
,11-28 18:57:52.734  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:57:52.734  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:57:52.735  4611  4611 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-28 18:57:52.735  4611  4611 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-28 18:57:52.735  4611  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-28 18:57:52.735  4611  4611 V BluetoothAdapterState: isTurningOff()=true
11-28 18:57:52.735  4611  4611 V BluetoothAdapterState: isTurningOn()=false
11-28 18:57:52.735  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:57:52.735  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:57:52.735  4611  4611 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-28 18:57:52.736  4611  4675 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-28 18:57:52.736  4611  4611 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-28 18:57:52.736  4611  4611 V BluetoothAdapterState: isTurningOff()=true
11-28 18:57:52.736  4611  4611 V BluetoothAdapterState: isTurningOn()=false
11-28 18:57:52.736  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:57:52.736  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:57:52.737  4611  4611 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-28 18:57:52.737  4611  4611 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-28 18:57:52.737   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-28 18:57:52.738  4611  4611 D BluetoothMapService: MAP Service closeService in
11-28 18:57:52.738  4611  4611 V BluetoothAdapterState: isTurningOff()=true
11-28 18:57:52.738  4611  4611 V BluetoothAdapterState: isTurningOn()=false
11-28 18:57:52.738  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:57:52.738  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:57:52.738  4611  4611 D BluetoothMapService: cleanup()
11-28 18:57:52.738  4611  4611 D BluetoothMapService: MAP Service closeService in
,11-28 18:57:52.738  4611  4611 V BluetoothAdapterState: isTurningOff()=true
11-28 18:57:52.739  4611  4611 V BluetoothAdapterState: isTurningOn()=false
11-28 18:57:52.739  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:57:52.739  4611  4611 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:57:52.739  4611  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-28 18:57:52.739  4611  4671 D BluetoothAdapterProperties: Setting state to 15
11-28 18:57:52.740  4611  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-28 18:57:52.740  4611  4671 I BluetoothAdapterState: Entering BleOnState
11-28 18:57:52.741  3061  3279 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:57:52.741  3061  3965 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 18:57:52.742  3061  3090 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-28 18:57:52.743  3061  3081 D BluetoothPan: onBluetoothStateChange on: false
,11-28 18:57:52.743   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:57:52.744  3061  3279 D BluetoothPbap: onBluetoothStateChange: up=false
11-28 18:57:52.745  3730  3747 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:57:52.745   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:57:52.745  3061  3965 D BluetoothMap: onBluetoothStateChange: up=false
,11-28 18:57:52.747   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-28 18:57:52.747   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-28 18:57:52.748  4611  4671 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-28 18:57:52.748  4611  4671 D BluetoothAdapterProperties: Setting state to 16
11-28 18:57:52.748  4611  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-28 18:57:52.749  4611  4671 D BluetoothAdapterProperties: onBleDisable
11-28 18:57:52.749  4611  4671 I BluetoothAdapterState: Entering PendingCommandState
11-28 18:57:52.749  4611  4672 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-28 18:57:52.750  4611  4675 D BluetoothAdapterProperties: Scan Mode:20
11-28 18:57:52.751  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:57:52.751  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:57:52.751  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:52.751  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:52.751  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:57:52.751  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:57:52.751  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:57:52.751  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:57:52.751  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:57:52.751  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 18:57:52.751  4611  4821 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-28 18:57:52.751  4611  4821 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:57:52.753  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:57:52.760   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:57:52.760   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-28 18:57:52.760   508   924 D TetherController: Setting IP forward enable = 0
,11-28 18:57:52.762   929  2915 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-28 18:57:52.762   929  2915 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-28 18:57:52.763   929  2913 D DhcpClient: doQuit
11-28 18:57:52.763   929  2913 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-28 18:57:52.763   929  5330 D DhcpClient: onQuitting
11-28 18:57:52.764  3404  3404 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-28 18:57:52.765   929   946 D Tethering: MasterInitialState.processMessage what=3
,11-28 18:57:52.771  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:57:52.771  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:57:52.771  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:52.771  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:52.771  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 18:57:52.771  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:57:52.771  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:57:52.771  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:57:52.771  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:57:52.771  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 18:57:52.773  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:57:52.773  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-28 18:57:52.775  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:57:52.776  5213  5213 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e71c6ab and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-28 18:57:52.778  3932  3932 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-28 18:57:52.780  5002  5026 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-28 18:57:52.780  5002  5026 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 18:57:52.781  5002  5026 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-28 18:57:52.781  5002  5026 E SarControlService: no key has been found,reset the power
11-28 18:57:52.781  5002  5039 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 18:57:52.781  5002  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 18:57:52.781  5002  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 18:57:52.782  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 18:57:52.782  5027  5027 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-28 18:57:52.783  5002  5039 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-28 18:57:52.783  5002  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 18:57:52.783  5002  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 18:57:52.784  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 18:57:52.784  5027  5027 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 18:57:52.787  5027  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdc7fa9 HexData = [00000000ea03000000000000ffffffff]
11-28 18:57:52.787  5027  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:57:52.787  5027  5041 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-28 18:57:52.788  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:57:52.788  5002  5013 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-28 18:57:52.791  5027  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdc7fa9 HexData = [00000000eb03000000000000ffffffff]
11-28 18:57:52.791  5027  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:57:52.791  5027  5041 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-28 18:57:52.792  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:57:52.792  5002  5012 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-28 18:57:52.794  5632  5632 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-28 18:57:52.798  3404  3404 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-28 18:57:52.805  3404  3404 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-28 18:57:52.806  5632  5632 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 18:57:52.812   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5763573:true
11-28 18:57:52.812  3513  3513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 18:57:52.817   508   924 E Netd    : netlink response contains error (No such file or directory)
,11-28 18:57:52.818   508   924 D TetherController: Setting IP forward enable = 0
,11-28 18:57:52.819   929  2915 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-28 18:57:52.825   929  3107 I ActivityManager: Start proc 5664:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-28 18:57:52.838  5632  5632 D LocalBluetoothProfileManager: Adding local MAP profile
,11-28 18:57:52.841  5632  5632 D BluetoothMap: Create BluetoothMap proxy object
,11-28 18:57:52.845  3404  3404 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-28 18:57:52.855  5632  5632 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-28 18:57:52.857  3404  3404 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-28 18:57:52.865  5664  5664 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-28 18:57:52.869  5632  5632 D DockEventReceiver: finishStartingService: stopping service
,11-28 18:57:52.875   929   940 I ActivityManager: Killing 4410:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-28 18:57:52.956  4611  4675 I bt_hci  : shut_down
,11-28 18:57:52.959   929  2913 D wifi    : In wifi stop Hal
,11-28 18:57:52.959   929  2913 D wifi    : halHandle = 0x7f67703540, mVM = 0x7f83d0d140, mCls = 0x100a02
,11-28 18:57:52.959   929  3403 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-28 18:57:52.959   929  3403 D WifiHAL : Got a signal to exit!!!
11-28 18:57:52.959   929  3403 I WifiHAL : Exit wifi_event_loop
11-28 18:57:52.960   929  2913 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-28 18:57:52.960   929  2913 E WifiHAL : Event processing terminated
,11-28 18:57:52.960   929  2913 D wifi    : In wifi cleaned up handler
11-28 18:57:52.960   929  2913 I WifiHAL : Internal cleanup completed
11-28 18:57:52.961  4942  4942 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 18:57:52.962  4611  4679 I bt_vendor: low_power_mode_cb
11-28 18:57:52.962  4611  4679 D bt_hwcfg: hw_epilog_process
11-28 18:57:52.962  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:57:52.963  4031  4157 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 18:57:52.964  4611  4679 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-28 18:57:52.964  4611  4679 I bt_vendor: epilog_cb
11-28 18:57:52.964  4611  4679 I bt_hci  : epilog_finished_callback
,11-28 18:57:52.969  4611  4675 I bt_hci_h4: hal_close
,11-28 18:57:52.970  4611  4675 I bt_userial_vendor: device fd = 54 close
,11-28 18:57:52.973   929  3403 D wifi    : set interface wlan0 flags (DOWN)
,11-28 18:57:52.974   929  2913 D WifiNative-HAL: HAL event thread stopped successfully
,11-28 18:57:53.057  5664  5664 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:57:53.057  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-28 18:57:53.058  5664  5664 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:57:53.058  5664  5664 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:57:53.058  5664  5664 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.e.b(PG:170)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:57:53.058  5664  5664 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.k.d(PG:583)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.e.b(PG:170)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:57:53.058  5664  5664 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:57:53.058  5664  5664 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.File.exists(File.java:361)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:57:53.058  5664  5664 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-28 18:57:53.058  5664  5664 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-28 18:57:53.078  5632  5632 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 18:57:53.078  4611  4672 D bt_stack_manager: event_shut_down_stack finished.
11-28 18:57:53.078  4611  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-28 18:57:53.081  4611  4611 D BtGatt.DebugUtils: handleDebugAction() action=null
11-28 18:57:53.081  4611  4671 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-28 18:57:53.081  4611  4611 D BtGatt.GattService: Received stop request...Stopping profile...
11-28 18:57:53.081  4611  4611 D BtGatt.GattService: stop()
11-28 18:57:53.081  4611  4611 D BtGatt.AdvertiseManager: advertise clients cleared
11-28 18:57:53.082  5632  5632 D DockEventReceiver: finishStartingService: stopping service
11-28 18:57:53.083  4611  4611 V BluetoothAdapterState: isTurningOff()=false
11-28 18:57:53.083  4611  4611 V BluetoothAdapterState: isTurningOn()=false
11-28 18:57:53.083  4611  4611 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:57:53.083  4611  4611 V BluetoothAdapterState: isBleTurningOff()=true
11-28 18:57:53.083  4611  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-28 18:57:53.083  4611  4671 D BluetoothAdapterProperties: Setting state to 10
11-28 18:57:53.083  4611  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-28 18:57:53.084  4611  4671 I BluetoothAdapterState: Entering OffState
11-28 18:57:53.084   929  3573 I ActivityManager: Killing 5077:com.google.android.deskclock/u0a66 (adj 15): empty #17
11-28 18:57:53.084   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-28 18:57:53.117  3513  3513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 18:57:53.123  4611  4611 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-28 18:57:53.123  4611  4611 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-28 18:57:53.123  4611  4611 I BluetoothServiceJni: cleanupNative: return from cleanup
11-28 18:57:53.124  4611  4672 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-28 18:57:53.128  4611  4611 I art     : System.exit called, status: 0
11-28 18:57:53.128  4611  4611 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-28 18:57:53.176   929   946 D Tethering: InitialState.processMessage what=4
,11-28 18:57:53.177   929  3107 I ActivityManager: Process com.android.bluetooth (pid 4611) has died
,11-28 18:57:53.181   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-28 18:57:53.186  3805  3805 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-28 18:57:53.189  3805  3805 D SystemUpdateService: onCreate
11-28 18:57:53.192  3805  3805 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-28 18:57:53.199  3805  3805 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-28 18:57:53.201  3805  5356 I iu.UploadsManager: num queued entries: 0
11-28 18:57:53.201  3805  5356 I iu.UploadsManager: num updated entries: 0
11-28 18:57:53.202  3805  5356 I iu.SyncManager: NEXT; no task
,11-28 18:57:53.206  3805  3805 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-28 18:57:53.208  3805  3805 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 18:57:53.213  3805  5697 I SystemUpdateService: active receiver: enabled
11-28 18:57:53.219  3805  5697 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-28 18:57:53.220   929  3574 I ActivityManager: Start proc 5699:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-28 18:57:53.221  3805  5697 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-28 18:57:53.221  3805  5697 I SystemUpdateService: now status is 0 (complete)
11-28 18:57:53.221  3805  5697 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 18:57:53.221  3805  5697 I SystemUpdateService: file has been verified
11-28 18:57:53.222  3805  5697 I SystemUpdateService: OTA package size = 21989297
11-28 18:57:53.233  3805  5697 I SystemUpdateService: showing system update notification
11-28 18:57:53.244   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:57:53.253  5699  5699 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-28 18:57:53.257  5699  5699 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 18:57:53.263  5699  5699 D SprintDMHelper: simOperator: 
,11-28 18:57:53.263  5699  5699 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 18:57:53.274   929  3573 I ActivityManager: Start proc 5711:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-28 18:57:53.295   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-28 18:57:53.324  3805  3805 D SystemUpdateService: onDestroy
,11-28 18:57:53.326   929  3107 I ActivityManager: Killing 5403:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-28 18:57:53.386  4942  5725 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-28 18:57:53.399   929   939 I ActivityManager: Start proc 5726:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-28 18:57:53.401   929  3573 I ActivityManager: Killing 5213:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-28 18:57:53.453  5726  5726 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-28 18:57:53.460   929   940 I ActivityManager: Killing 3838:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-28 18:57:53.485  5664  5682 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-28 18:57:53.506   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b4a6542:true
,11-28 18:57:54.244   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-28 18:57:57.710   929   940 D WifiService: setWifiEnabled: true pid=5573, uid=10077
,11-28 18:57:57.710   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:57:57.718   508   924 D SoftapController: Softap fwReload - Ok
,11-28 18:57:57.723   508   924 D CommandListener: Setting iface cfg
11-28 18:57:57.724   508   924 D CommandListener: Trying to bring down wlan0
11-28 18:57:57.726   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-28 18:57:57.733   929  2913 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 18:57:58.317   929  2913 D wifi    : set interface wlan0 flags (UP)
,11-28 18:57:58.320   929  2913 I WifiHAL : Initializing wifi
,11-28 18:57:58.320   929  2913 I WifiHAL : Creating socket
,11-28 18:57:58.322   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-28 18:57:58.326   929  2913 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-28 18:57:58.326   929  2913 D wifi    : Did set static halHandle = 0x7f67703540
11-28 18:57:58.326   929  2913 D wifi    : halHandle = 0x7f67703540, mVM = 0x7f83d0d140, mCls = 0x197e
11-28 18:57:58.327   929  2913 D wifi    : array field set
11-28 18:57:58.327   929  2913 I WifiNative-HAL: interface[0] = wlan0
11-28 18:57:58.330   929  5744 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547196253504
11-28 18:57:58.330   929  5744 D wifi    : waitForHalEvents called, vm = 0x7f83d0d140, obj = 0x197e, env = 0x7f68d8d140
,11-28 18:57:58.382  5745  5745 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-28 18:57:58.430   929  2913 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-28 18:57:58.436  5745  5745 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 18:57:58.440  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:57:58.518  5745  5745 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 18:57:58.518  5745  5745 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-28 18:57:58.538   929  2913 D WifiConfigStore: Loading config and enabling all networks 
,11-28 18:57:58.540  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 18:57:58.540  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:57:58.540  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:57:58.540  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:57:58.540  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:57:58.540  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:57:58.540  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:57:58.540  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:57:58.540  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:57:58.540  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 18:57:58.540  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-28 18:57:58.540  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 18:57:58.568   929  2913 D WifiConfigStore: loaded 0 passpoint configs
,11-28 18:57:58.569   929  2913 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
,11-28 18:57:58.569   929  2913 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-28 18:57:58.570   929  2913 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-28 18:57:58.571   929  2913 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-28 18:57:58.571   929  2913 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-28 18:57:58.572   929  2913 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-28 18:57:58.573   929  2913 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-28 18:57:58.573   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
,11-28 18:57:58.573   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
11-28 18:57:58.573   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-28 18:57:58.573   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-28 18:57:58.573   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-28 18:57:58.577   929  2913 D WifiNative-HAL: Setting external_sim to 1
,11-28 18:57:58.577   929  2913 D wifi    : setting dfs flag to true, 0x7f6c1bb320
11-28 18:57:58.578   929  2913 D WifiStateMachine: Setting OUI to DA-A1-19
11-28 18:57:58.578  4942  4942 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 18:57:58.578   929  2913 D wifi    : setting scan oui 0x7f6c1bb320
,11-28 18:57:58.578   929  2913 D WifiHAL : Sending mac address OUI
,11-28 18:57:58.582   929  2913 E native  : do suspend false
,11-28 18:57:58.589   929  2913 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-28 18:57:58.590   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-28 18:57:58.590   929   929 D RttService: SCAN_AVAILABLE : 3
11-28 18:57:58.590   929  3021 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-28 18:57:58.592   508   924 D CommandListener: Setting iface cfg
,11-28 18:57:58.597   929  2912 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '125 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 125 Failed to set address (No such device)'
,11-28 18:57:58.597   929  2912 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-28 18:57:58.610   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128611 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-28 18:57:58.613   929  2912 D WifiNative-HAL: p2pGetDeviceAddress
,11-28 18:57:58.616   929  2912 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-28 18:57:59.245   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:00.246   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:01.247   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:01.731  5745  5745 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 18:58:01.736  5745  5745 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 18:58:01.793   929  2913 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-28 18:58:01.794   929  2913 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-28 18:58:01.794   929  2913 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 18:58:01.805   929  2913 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-28 18:58:01.839   929  2913 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-28 18:58:01.844  5745  5745 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-28 18:58:02.248   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:02.269  5745  5745 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-28 18:58:02.334  5745  5745 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-28 18:58:02.336  5745  5745 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-28 18:58:02.350   929  2913 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 18:58:02.351   929  2913 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 18:58:02.351   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-28 18:58:02.366   929  2913 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 18:58:02.377   508   924 D CommandListener: Setting iface cfg
,11-28 18:58:02.384   929  2913 D WifiStateMachine: Start Dhcp Watchdog 2
,11-28 18:58:02.390   929  5751 D DhcpClient: Receive thread started
,11-28 18:58:02.394   929  2915 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 18:58:02.394   929  2913 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-28 18:58:02.394   929  2915 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-28 18:58:02.475   929  2913 E native  : do suspend false
,11-28 18:58:02.490   929  5750 D DhcpClient: Broadcasting DHCPDISCOVER
,11-28 18:58:02.513   929  5751 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172710, domain null
,11-28 18:58:02.513   929  5750 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172710 seconds
,11-28 18:58:02.516   929  5750 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-28 18:58:02.529   929  5751 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-28 18:58:02.530   929  5750 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-28 18:58:02.534   508   924 D CommandListener: Setting iface cfg
,11-28 18:58:02.539   929  2913 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-28 18:58:02.545   929  5750 D DhcpClient: Scheduling renewal in 86399s
,11-28 18:58:02.552   929  2913 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-28 18:58:02.554   929  2913 D WifiConfigStore: No blacklist allowed without epno enabled
11-28 18:58:02.555   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-28 18:58:02.557   929  2915 D ConnectivityService: Adding iface wlan0 to network 101
11-28 18:58:02.567   929  2913 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-28 18:58:02.620   929  2915 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-28 18:58:02.620   929  2915 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-28 18:58:02.621   929  2915 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-28 18:58:02.624   929  2915 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-28 18:58:02.626   929  2915 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-28 18:58:02.634   929  2915 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-28 18:58:02.639   929  2915 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-28 18:58:02.640   929  2915 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-28 18:58:02.640   929  2915 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-28 18:58:02.640   929  2913 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-28 18:58:02.640   929  2915 D ConnectivityService:    accepting network in place of null
11-28 18:58:02.640   929  2913 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 18:58:02.640   929  2915 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 18:58:02.658   929  5749 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132658, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 18:58:02.665   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:58:02.687   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:58:02.690   929  2915 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-28 18:58:02.690   929  2915 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-28 18:58:02.690  3697  3829 W QCNEJ   : |CORE| network available: 101
,11-28 18:58:02.692   929  2915 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-28 18:58:02.694  3697  3829 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-28 18:58:02.694   929   946 D Tethering: MasterInitialState.processMessage what=3
11-28 18:58:02.696  3697  3829 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-28 18:58:02.697  3697  3829 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-28 18:58:02.699  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:58:02.699  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:58:02.699  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:58:02.699  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:58:02.699  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:58:02.699  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:58:02.699  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:58:02.699  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:58:02.699  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:58:02.699  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-28 18:58:02.699  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:58:02.699  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 18:58:02.703  5002  5026 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-28 18:58:02.704  5002  5026 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 18:58:02.704  5002  5026 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-28 18:58:02.704  5002  5026 E SarControlService: no key has been found,reset the power
11-28 18:58:02.704  5002  5039 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 18:58:02.704  5002  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 18:58:02.704  5002  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 18:58:02.705  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 18:58:02.705  5027  5027 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-28 18:58:02.709  5002  5039 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-28 18:58:02.709  5002  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 18:58:02.709  5002  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 18:58:02.709  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 18:58:02.709  5027  5027 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 18:58:02.711  3932  3932 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-28 18:58:02.712  5027  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdc7fa9 HexData = [00000000ec03000000000000ffffffff]
11-28 18:58:02.712  5027  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:58:02.712  5027  5041 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-28 18:58:02.713  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-28 18:58:02.714  3805  3805 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 18:58:02.715   929  3740 D WifiService: setWifiEnabled: false pid=5573, uid=10077
11-28 18:58:02.715   929  3740 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:58:02.717  3805  3805 D SystemUpdateService: onCreate
11-28 18:58:02.717   929  2913 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-28 18:58:02.718   929  2913 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-28 18:58:02.718   929  2913 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-28 18:58:02.718   929  2913 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-28 18:58:02.718  5002  5013 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-28 18:58:02.724  5027  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdc7fa9 HexData = [00000000ed03000000000000ffffffff]
,11-28 18:58:02.724  5027  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:58:02.724  5027  5041 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-28 18:58:02.724  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:58:02.724  3805  3805 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-28 18:58:02.725   929  5750 D DhcpClient: Clearing IP address
11-28 18:58:02.726   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-28 18:58:02.726   929  5748 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-28 18:58:02.727   508   924 D CommandListener: Setting iface cfg
11-28 18:58:02.730   929  5748 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-28 18:58:02.730   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
11-28 18:58:02.733  5002  5012 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-28 18:58:02.741   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-28 18:58:02.741   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-28 18:58:02.745   929  5751 D DhcpClient: Receive thread stopped
,11-28 18:58:02.747   929  2915 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-28 18:58:02.747   929   929 D RttService: SCAN_AVAILABLE : 1
,11-28 18:58:02.749   929  3021 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 18:58:02.749   534   534 E Parcel  : Reading a NULL string not supported here.
,11-28 18:58:02.750  3697  3829 W QCNEJ   : |CORE| network lost: 101
11-28 18:58:02.752   929  2913 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-28 18:58:02.752  3697  3829 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-28 18:58:02.756   929  2913 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-28 18:58:02.757  3805  5764 I SystemUpdateService: active receiver: enabled
,11-28 18:58:02.759  3805  3805 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-28 18:58:02.761  3805  3805 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-28 18:58:02.763  5699  5699 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 18:58:02.768  5699  5699 D SprintDMHelper: simOperator: 
,11-28 18:58:02.768  5699  5699 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 18:58:02.776   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:58:02.795   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:58:02.796   929  2915 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-28 18:58:02.796   508   924 D CommandListener: Clearing all IP addresses on wlan0
11-28 18:58:02.796   929  2915 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-28 18:58:02.797  3805  5764 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-28 18:58:02.799   929   946 D Tethering: MasterInitialState.processMessage what=3
11-28 18:58:02.801   929  2913 D DhcpClient: doQuit
11-28 18:58:02.801   929  2913 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-28 18:58:02.801  5745  5745 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-28 18:58:02.802   929  5750 D DhcpClient: onQuitting
11-28 18:58:02.802  3805  5764 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-28 18:58:02.802  3805  5764 I SystemUpdateService: now status is 0 (complete)
11-28 18:58:02.802  3805  5764 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-28 18:58:02.802  3805  5764 I SystemUpdateService: file has been verified
11-28 18:58:02.802  3805  5764 I SystemUpdateService: OTA package size = 21989297
,11-28 18:58:02.805  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:58:02.806  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:58:02.806  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:58:02.806  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:58:02.806  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 18:58:02.806  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:58:02.806  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:58:02.806  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:58:02.806  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:58:02.806  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-28 18:58:02.806  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:58:02.806  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-28 18:58:02.807  3932  3932 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-28 18:58:02.807  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:58:02.809  5002  5026 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-28 18:58:02.809  5002  5026 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 18:58:02.809  5002  5026 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-28 18:58:02.810  5002  5026 E SarControlService: no key has been found,reset the power
11-28 18:58:02.810  5002  5039 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 18:58:02.810  5002  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 18:58:02.810  5002  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 18:58:02.810  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 18:58:02.810  5027  5027 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-28 18:58:02.812  5002  5039 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 18:58:02.812  5002  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-28 18:58:02.812  5002  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-28 18:58:02.813  3805  3805 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 18:58:02.814  5745  5745 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-28 18:58:02.814  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-28 18:58:02.814  5027  5027 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 18:58:02.816  3805  3805 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-28 18:58:02.817  5027  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdc7fa9 HexData = [00000000ee03000000000000ffffffff]
11-28 18:58:02.817  5027  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:58:02.817  5027  5041 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-28 18:58:02.817  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:58:02.817  5002  5012 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-28 18:58:02.818  5745  5745 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-28 18:58:02.820  5027  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdc7fa9 HexData = [00000000ef03000000000000ffffffff]
11-28 18:58:02.820  5027  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-28 18:58:02.820  5027  5041 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-28 18:58:02.821  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:58:02.821  5002  5013 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-28 18:58:02.831  3805  5764 I SystemUpdateService: showing system update notification
,11-28 18:58:02.835  5745  5745 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-28 18:58:02.842  3805  3805 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-28 18:58:02.844  3805  3805 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-28 18:58:02.845  5699  5699 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-28 18:58:02.848  5699  5699 D SprintDMHelper: simOperator: 
11-28 18:58:02.848  5699  5699 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-28 18:58:02.852   508   924 E Netd    : netlink response contains error (No such file or directory)
,11-28 18:58:02.853   929  2915 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-28 18:58:02.854   929  2915 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-28 18:58:02.856  5745  5745 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-28 18:58:02.866   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-28 18:58:02.878  3805  5784 I SystemUpdateService: active receiver: enabled
,11-28 18:58:02.881  3805  5784 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-28 18:58:02.882  3805  5784 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-28 18:58:02.883  3805  5784 I SystemUpdateService: now status is 0 (complete)
11-28 18:58:02.883  3805  5784 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 18:58:02.883  3805  5784 I SystemUpdateService: file has been verified
11-28 18:58:02.883  3805  5784 I SystemUpdateService: OTA package size = 21989297
,11-28 18:58:02.888  3805  5784 I SystemUpdateService: showing system update notification
,11-28 18:58:02.896   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
,11-28 18:58:02.897  3805  3805 D SystemUpdateService: onDestroy
,11-28 18:58:02.961   929  2913 D wifi    : In wifi stop Hal
,11-28 18:58:02.961  4942  4942 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-28 18:58:02.961   929  2913 D wifi    : halHandle = 0x7f67703540, mVM = 0x7f83d0d140, mCls = 0x197e
11-28 18:58:02.961   929  5744 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-28 18:58:02.961   929  5744 D WifiHAL : Got a signal to exit!!!
11-28 18:58:02.961   929  5744 I WifiHAL : Exit wifi_event_loop
11-28 18:58:02.961   929  2913 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-28 18:58:02.962   929  2913 E WifiHAL : Event processing terminated
11-28 18:58:02.962   929  2913 D wifi    : In wifi cleaned up handler
11-28 18:58:02.962   929  2913 I WifiHAL : Internal cleanup completed
11-28 18:58:02.963  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:58:02.966  4031  4157 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 18:58:02.985   929  5744 D wifi    : set interface wlan0 flags (DOWN)
,11-28 18:58:02.986   929  2913 D WifiNative-HAL: HAL event thread stopped successfully
,11-28 18:58:03.192   929   946 D Tethering: InitialState.processMessage what=4
,11-28 18:58:03.198   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-28 18:58:03.251   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:03.692   929  2915 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-28 18:58:04.252   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-28 18:58:07.752   929   946 I ActivityManager: Start proc 5786:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-28 18:58:07.822  5786  5786 D AdapterServiceConfig: Adding HeadsetService
,11-28 18:58:07.823  5786  5786 D AdapterServiceConfig: Adding A2dpService
11-28 18:58:07.823  5786  5786 D AdapterServiceConfig: Adding HidService
11-28 18:58:07.823  5786  5786 D AdapterServiceConfig: Adding HealthService
,11-28 18:58:07.824  5786  5786 D AdapterServiceConfig: Adding PanService
11-28 18:58:07.824  5786  5786 D AdapterServiceConfig: Adding GattService
,11-28 18:58:07.824  5786  5786 D AdapterServiceConfig: Adding BluetoothMapService
11-28 18:58:07.824  5786  5786 D AdapterServiceConfig: Adding SapService
,11-28 18:58:07.837   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9fed07c:true
,11-28 18:58:07.837  5786  5786 D BluetoothAdapterState: make() - Creating AdapterState
,11-28 18:58:07.839  5786  5786 I bt_bluedroid: init
,11-28 18:58:07.839  5786  5798 I BluetoothAdapterState: Entering OffState
,11-28 18:58:07.840  5786  5799 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-28 18:58:07.840  5786  5799 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-28 18:58:07.840  5786  5799 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-28 18:58:07.841  5786  5799 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-28 18:58:07.841  5786  5786 I bt_bluedroid: get_profile_interface socket
,11-28 18:58:07.842  5786  5802 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-28 18:58:07.843  5786  5786 I bt_bluedroid: get_profile_interface sdp
,11-28 18:58:07.844  5786  5802 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 18:58:07.847  5786  5797 I bt_bluedroid: config_hci_snoop_log
,11-28 18:58:07.848   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-28 18:58:07.851  5786  5798 D BluetoothAdapterState: Current state: OFF, message: 0
,11-28 18:58:07.851  5786  5798 D BluetoothAdapterProperties: Setting state to 14
11-28 18:58:07.852  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-28 18:58:07.853  5786  5798 D BluetoothBondStateMachine: make
,11-28 18:58:07.854  5786  5803 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-28 18:58:07.857  5786  5798 I BluetoothAdapterState: Entering PendingCommandState
,11-28 18:58:07.858  5786  5786 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-28 18:58:07.859  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:07.860  5786  5786 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-28 18:58:07.860  5786  5786 D BtGatt.GattService: Received start request. Starting profile...
,11-28 18:58:07.860  5786  5786 D BtGatt.GattService: start()
11-28 18:58:07.860  5786  5786 I bt_bluedroid: get_profile_interface gatt
11-28 18:58:07.861  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:07.861  5786  5786 D BtGatt.AdvertiseManager: advertise manager created
,11-28 18:58:07.865  5786  5786 V BluetoothAdapterState: isTurningOff()=false
,11-28 18:58:07.865  5786  5786 V BluetoothAdapterState: isTurningOn()=false
11-28 18:58:07.865  5786  5786 V BluetoothAdapterState: isBleTurningOn()=true
11-28 18:58:07.865  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:58:07.865  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-28 18:58:07.866  5786  5798 I bt_bluedroid: bt_bluedroid
11-28 18:58:07.867  5786  5799 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-28 18:58:07.867  5786  5799 I bt_hci  : start_up
,11-28 18:58:07.871  5786  5799 I bt_vendor: alloc value 0xf3d7f871
,11-28 18:58:07.871  5786  5799 I bt_vendor: init
11-28 18:58:07.871  5786  5799 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-28 18:58:07.871  5786  5799 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-28 18:58:07.981  5786  5799 D bt_hci  : start_up starting async portion
11-28 18:58:07.981  5786  5806 I bt_hci  : event_finish_startup
,11-28 18:58:07.981  5786  5806 I bt_hci_h4: hal_open
11-28 18:58:07.981  5786  5806 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-28 18:58:07.978  5807  5807 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 18:58:07.984  5786  5806 I bt_userial_vendor: device fd = 54 open
,11-28 18:58:07.999  5786  5806 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 18:58:08.001  5786  5806 D bt_hwcfg: Chipset BCM4358A3
,11-28 18:58:08.001  5786  5806 D bt_hwcfg: Target name = [BCM4358A3]
11-28 18:58:08.002  5786  5806 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-28 18:58:08.407  5786  5806 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-28 18:58:08.407  5786  5806 D bt_hwcfg: Settlement delay -- 100 ms
11-28 18:58:08.407  5786  5806 I bt_hwcfg: Setting fw settlement delay to 100 
,11-28 18:58:08.540  5786  5806 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 18:58:08.541  5786  5806 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
,11-28 18:58:08.542  5786  5806 I bt_hwcfg: vendor lib fwcfg completed
,11-28 18:58:08.543  5786  5806 I bt_vendor: firmware callback
,11-28 18:58:08.543  5786  5806 I bt_hci  : firmware_config_callback
,11-28 18:58:08.551  5786  5809 I bt_btu  : btu_task pending for preload complete event
,11-28 18:58:08.551  5786  5809 I bt_btu_task: Bluetooth chip preload is complete
11-28 18:58:08.551  5786  5809 I bt_btu  : btu_task received preload complete event
,11-28 18:58:08.558  5786  5809 I         : BTE_InitTraceLevels -- TRC_HCI
,11-28 18:58:08.558  5786  5809 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-28 18:58:08.558  5786  5809 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-28 18:58:08.558  5786  5809 I         : BTE_InitTraceLevels -- TRC_AVDT
11-28 18:58:08.558  5786  5809 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-28 18:58:08.559  5786  5809 I         : BTE_InitTraceLevels -- TRC_A2D
11-28 18:58:08.559  5786  5809 I         : BTE_InitTraceLevels -- TRC_BNEP
11-28 18:58:08.559  5786  5809 I         : BTE_InitTraceLevels -- TRC_BTM
11-28 18:58:08.559  5786  5809 I         : BTE_InitTraceLevels -- TRC_GAP
,11-28 18:58:08.559  5786  5809 I         : BTE_InitTraceLevels -- TRC_PAN
11-28 18:58:08.559  5786  5809 I         : BTE_InitTraceLevels -- TRC_SDP
11-28 18:58:08.560  5786  5809 I         : BTE_InitTraceLevels -- TRC_GATT
11-28 18:58:08.560  5786  5809 I         : BTE_InitTraceLevels -- TRC_SMP
,11-28 18:58:08.560  5786  5809 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-28 18:58:08.560  5786  5809 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-28 18:58:08.642  5786  5809 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cfd549
,11-28 18:58:08.643  5786  5809 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cfd549 
,11-28 18:58:08.660  5786  5802 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-28 18:58:08.661  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-28 18:58:08.662  5786  5802 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-28 18:58:08.664  5786  5802 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 18:58:08.669  5786  5802 D BluetoothAdapterProperties: Scan Mode:20
,11-28 18:58:08.670  5786  5802 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-28 18:58:08.670  5786  5802 D bt_hci  : do_postload posting postload work item
11-28 18:58:08.670  5786  5806 I bt_hci  : event_postload
11-28 18:58:08.670  5786  5806 I bt_vendor: sco_config_cb
11-28 18:58:08.671  5786  5806 I bt_hci  : sco_config_callback postload finished.
11-28 18:58:08.673  5786  5802 D bt_bte_conf: Device ID record 1 : primary
11-28 18:58:08.673  5786  5802 D bt_bte_conf:   vendorId            = 000f
11-28 18:58:08.673  5786  5802 D bt_bte_conf:   vendorIdSource      = 0001
11-28 18:58:08.673  5786  5802 D bt_bte_conf:   product             = 1200
,11-28 18:58:08.674  5786  5802 D bt_bte_conf:   version             = 1436
11-28 18:58:08.674  5786  5802 D bt_bte_conf:   clientExecutableURL = 
11-28 18:58:08.674  5786  5802 D bt_bte_conf:   serviceDescription  = 
11-28 18:58:08.674  5786  5802 D bt_bte_conf:   documentationURL    = 
11-28 18:58:08.674  5786  5802 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-28 18:58:08.674  5786  5799 D bt_stack_manager: event_start_up_stack finished
11-28 18:58:08.675  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-28 18:58:08.676  5786  5798 D BluetoothAdapterProperties: Setting state to 15
11-28 18:58:08.676  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-28 18:58:08.677  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 18:58:08.677  5786  5798 I BluetoothAdapterState: Entering BleOnState
11-28 18:58:08.682  5786  5798 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-28 18:58:08.683  5786  5798 D BluetoothAdapterProperties: Setting state to 11
,11-28 18:58:08.683  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-28 18:58:08.684  5786  5806 I bt_vendor: low_power_mode_cb
,11-28 18:58:08.688  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:58:08.692  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
,11-28 18:58:08.693  5786  5786 D HeadsetService: Received start request. Starting profile...
,11-28 18:58:08.696  5786  5786 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-28 18:58:08.697  5786  5786 D HeadsetStateMachine: make
,11-28 18:58:08.702  5786  5798 I BluetoothAdapterState: Entering PendingCommandState
,11-28 18:58:08.708  5786  5786 D HeadsetStateMachine: max_hf_connections = 1
,11-28 18:58:08.708  5786  5786 I bt_bluedroid: get_profile_interface handsfree
11-28 18:58:08.708  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-28 18:58:08.708  5786  5802 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-28 18:58:08.712  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
,11-28 18:58:08.713  5786  5786 D A2dpService: Received start request. Starting profile...
,11-28 18:58:08.714  5786  5786 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-28 18:58:08.714  5786  5786 I bt_bluedroid: get_profile_interface avrcp
,11-28 18:58:08.722  5786  5786 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-28 18:58:08.722  5786  5786 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-28 18:58:08.722  5786  5786 D A2dpStateMachine: make
,11-28 18:58:08.724  5786  5786 I bt_bluedroid: get_profile_interface a2dp
11-28 18:58:08.725  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-28 18:58:08.726  5786  5817 D A2dpStateMachine: Enter Disconnected: -2
11-28 18:58:08.727  5786  5786 I BluetoothHidServiceJni: classInitNative: succeeds
11-28 18:58:08.728  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
,11-28 18:58:08.730  5632  5632 D BluetoothInputDevice: Proxy object connected
,11-28 18:58:08.731  5632  5632 D HidProfile: Bluetooth service connected
11-28 18:58:08.732  5786  5786 D HidService: Received start request. Starting profile...
11-28 18:58:08.732  5786  5786 I bt_bluedroid: get_profile_interface hidhost
11-28 18:58:08.732  5786  5802 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cde56d
11-28 18:58:08.732  5786  5786 D HidService: setHidService(): set to: null
11-28 18:58:08.732  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-28 18:58:08.734  5786  5786 I BluetoothHealthServiceJni: classInitNative: succeeds
11-28 18:58:08.735  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:08.735  3513  3513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 18:58:08.736  5786  5786 D HealthService: Received start request. Starting profile...
,11-28 18:58:08.737  5786  5786 I bt_bluedroid: get_profile_interface health
11-28 18:58:08.738  5786  5786 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-28 18:58:08.739  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
,11-28 18:58:08.741  5632  5632 D BluetoothPan: BluetoothPAN Proxy object connected
,11-28 18:58:08.741  5632  5632 D PanProfile: Bluetooth service connected
11-28 18:58:08.741  5786  5786 D PanService: Received start request. Starting profile...
11-28 18:58:08.742  5786  5786 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-28 18:58:08.742  5786  5786 I bt_bluedroid: get_profile_interface pan
,11-28 18:58:08.742  5786  5802 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-28 18:58:08.744  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:08.745  5632  5632 D BluetoothMap: Proxy object connected
11-28 18:58:08.745  5786  5786 D BluetoothMapService: Received start request. Starting profile...
11-28 18:58:08.745  5786  5786 D BluetoothMapService: start()
11-28 18:58:08.746  5632  5632 D MapProfile: Bluetooth service connected
11-28 18:58:08.746  5632  5632 D BluetoothMap: getConnectedDevices()
,11-28 18:58:08.746  5632  5632 D BluetoothMap: Bluetooth is Not enabled
,11-28 18:58:08.748  5786  5786 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-28 18:58:08.749  5786  5786 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-28 18:58:08.749  5786  5786 D BluetoothMapAppObserver: createReceiver()
,11-28 18:58:08.750  5786  5786 D BluetoothMapAppObserver: initObservers()
,11-28 18:58:08.751  5786  5786 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-28 18:58:08.758  5786  5786 V SapService: SapBinder()
,11-28 18:58:08.758  5786  5786 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:08.759  5786  5786 D SapService: Received start request. Starting profile...
11-28 18:58:08.759  5786  5786 V SapService: start()
,11-28 18:58:08.762  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:08.762  5786  5786 V BluetoothAdapterState: isTurningOn()=true
,11-28 18:58:08.762  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:08.762  5786  5815 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-28 18:58:08.762  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:08.763  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:08.763  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:08.763  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:08.763  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:08.763  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:08.763  5786  5786 V BluetoothAdapterState: isTurningOn()=true
,11-28 18:58:08.763  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:08.763  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:58:08.763  5786  5786 V BluetoothAdapterState: isTurningOff()=false
,11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:08.764  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:08.765  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:08.765  5786  5786 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:08.765  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:08.765  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:08.765  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-28 18:58:08.765  5786  5798 D BluetoothAdapterProperties: ScanMode =  20
11-28 18:58:08.765  5786  5798 D BluetoothAdapterProperties: State =  11
11-28 18:58:08.766  5786  5798 D BluetoothAdapterProperties: Setting state to 12
11-28 18:58:08.766  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-28 18:58:08.766  5786  5798 I BluetoothAdapterState: Entering OnState
11-28 18:58:08.767  5786  5802 D BluetoothAdapterProperties: Scan Mode:21
,11-28 18:58:08.767  5786  5802 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-28 18:58:08.767  3061  3279 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:58:08.767  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-28 18:58:08.768  5632  5645 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 18:58:08.768  3061  3081 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 18:58:08.770  3061  3090 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 18:58:08.772  3061  3061 D BluetoothA2dp: Proxy object connected
11-28 18:58:08.772  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:58:08.772  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:58:08.772  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:58:08.772  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 18:58:08.772  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:58:08.772  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:58:08.772  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:58:08.772  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:58:08.772  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 18:58:08.773  3061  3279 D BluetoothPan: onBluetoothStateChange on: true
11-28 18:58:08.774  3061  3061 D BluetoothInputDevice: Proxy object connected
11-28 18:58:08.774  3061  3061 D HidProfile: Bluetooth service connected
11-28 18:58:08.775   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:58:08.775  3061  3090 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 18:58:08.776  3061  3061 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 18:58:08.776  3061  3061 D PanProfile: Bluetooth service connected
11-28 18:58:08.776  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 18:58:08.778  5786  5786 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-28 18:58:08.779  5786  5786 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-28 18:58:08.779  3730  3908 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 18:58:08.780  5632  5652 D BluetoothMap: onBluetoothStateChange: up=true
,11-28 18:58:08.780  5632  5645 D BluetoothPan: onBluetoothStateChange on: true
11-28 18:58:08.781  5786  5786 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:58:08.781   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:58:08.781  3061  3965 D BluetoothMap: onBluetoothStateChange: up=true
,11-28 18:58:08.783  3061  3061 D BluetoothMap: Proxy object connected
11-28 18:58:08.783  3061  3061 D MapProfile: Bluetooth service connected
,11-28 18:58:08.783  3061  3061 D BluetoothMap: getConnectedDevices()
11-28 18:58:08.783   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:58:08.783   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 18:58:08.783  5786  5786 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:58:08.784   929   929 D BluetoothA2dp: Proxy object connected
11-28 18:58:08.784  5632  5652 D BluetoothPbap: onBluetoothStateChange: up=true
,11-28 18:58:08.785  5786  5786 D ObexServerSockets: Succeed to create listening sockets 
11-28 18:58:08.786  5786  5786 D ObexServerSockets0: startAccept()
11-28 18:58:08.786  5786  5786 D ObexServerSockets0: prepareForNewConnect()
,11-28 18:58:08.787   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,11-28 18:58:08.788  5786  5786 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-28 18:58:08.788  5786  5786 D BluetoothSdpJni: SDP Create record success - handle: 0
11-28 18:58:08.788  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-28 18:58:08.789  5786  5824 D ObexServerSockets0: Accepting socket connection...
11-28 18:58:08.789  5786  5823 D ObexServerSockets0: Accepting socket connection...
,11-28 18:58:08.791  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:58:08.790  5786  5786 D BluetoothMapService: onReceive
11-28 18:58:08.791  5786  5786 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-28 18:58:08.792  5786  5786 D BluetoothMapService: STATE_ON
,11-28 18:58:08.793  5632  5632 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-28 18:58:08.795  5786  5826 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:58:08.796  5786  5826 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-28 18:58:08.796  5786  5826 D BluetoothSdpJni: SDP Create record success - handle: 1
11-28 18:58:08.796  5632  5632 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-28 18:58:08.802  5632  5632 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 18:58:08.804  5632  5632 D BluetoothA2dp: Proxy object connected
,11-28 18:58:08.808  3513  3513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 18:58:08.811  5632  5632 D DockEventReceiver: finishStartingService: stopping service
,11-28 18:58:08.814  5632  5632 D BluetoothPbap: Proxy object connected
,11-28 18:58:08.814  5632  5632 D PbapServerProfile: Bluetooth service connected
,11-28 18:58:08.819  5786  5786 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-28 18:58:08.819  5786  5786 D ObexServerSockets0: prepareForNewConnect()
,11-28 18:58:08.822  3061  3061 D BluetoothPbap: Proxy object connected
11-28 18:58:08.822  3061  3061 D PbapServerProfile: Bluetooth service connected
11-28 18:58:08.822  5786  5830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:58:08.835  5786  5834 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:58:08.836  5786  5834 I BtOppRfcommListener: Accept thread started.
,11-28 18:58:08.869   929   929 D BluetoothHeadset: Proxy object connected
,11-28 18:58:08.869  3730  3752 D BluetoothHeadset: Proxy object connected
11-28 18:58:08.869   929   929 D BluetoothHeadset: Proxy object connected
11-28 18:58:08.870  3061  3279 D BluetoothHeadset: Proxy object connected
,11-28 18:58:08.870  3061  3061 D HeadsetProfile: Bluetooth service connected
11-28 18:58:08.870   929   929 D BluetoothHeadset: Proxy object connected
,11-28 18:58:08.876   929   946 D BluetoothHeadset: Proxy object connected
,11-28 18:58:08.880  3730  3747 D BluetoothHeadset: Proxy object connected
11-28 18:58:08.881   929   946 D BluetoothHeadset: Proxy object connected
,11-28 18:58:08.884   929   946 D BluetoothHeadset: Proxy object connected
,11-28 18:58:08.899  5632  5652 D BluetoothHeadset: Proxy object connected
,11-28 18:58:08.900  5632  5632 D HeadsetProfile: Bluetooth service connected
,11-28 18:58:10.647   929  2915 D ConnectivityService: handlePromptUnvalidated 101
,11-28 18:58:10.798  3623  3811 I Keyboard.Facilitator.LanguageModelFlusher: run()
,11-28 18:58:10.798  3623  3811 I Keyboard.Facilitator: flushDynamicLanguageModels()
,11-28 18:58:10.827  3513  3513 I ConfigService: onCreate
,11-28 18:58:12.732  5786  5798 D BluetoothAdapterState: Current state: ON, message: 23
,11-28 18:58:12.733  5786  5798 D BluetoothAdapterProperties: Setting state to 13
11-28 18:58:12.733  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-28 18:58:12.734  5786  5798 D BluetoothAdapterProperties: onBluetoothDisable()
11-28 18:58:12.736  5786  5798 I BluetoothAdapterState: Entering PendingCommandState
,11-28 18:58:12.742  5786  5802 D BluetoothAdapterProperties: Scan Mode:20
,11-28 18:58:12.742  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-28 18:58:12.744  5786  5786 D BluetoothMapService: onReceive
,11-28 18:58:12.744  5786  5786 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 18:58:12.744  5786  5786 D BluetoothMapService: STATE_TURNING_OFF
,11-28 18:58:12.745  5786  5786 D BluetoothMapService: MAP Service closeService in
11-28 18:58:12.745  5786  5786 D BluetoothMapMasInstance0: MAP Service shutdown
11-28 18:58:12.745  5786  5786 D ObexServerSockets0: shutdown(block = true)
,11-28 18:58:12.747  5786  5786 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-28 18:58:12.747  5786  5823 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-28 18:58:12.747  5786  5824 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-28 18:58:12.747  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:58:12.747  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:58:12.747  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:58:12.747  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:58:12.747  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 18:58:12.747  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-28 18:58:12.747  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:58:12.747  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:58:12.747  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:58:12.747  5573  5573 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-28 18:58:12.748  5786  5811 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-28 18:58:12.748  5786  5786 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-28 18:58:12.750  5573  5573 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-28 18:58:12.750  5573  5573 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-28 18:58:12.753  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-28 18:58:12.754  5786  5786 I BtOppRfcommListener: stopping Accept Thread
,11-28 18:58:12.754  5786  5834 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-28 18:58:12.755  5632  5632 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-28 18:58:12.755  5786  5834 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-28 18:58:12.757  5786  5786 D HeadsetService: Received stop request...Stopping profile...
,11-28 18:58:12.760  5632  5645 D BluetoothHeadset: Proxy object disconnected
11-28 18:58:12.760   929   929 D BluetoothHeadset: Proxy object disconnected
,11-28 18:58:12.760  3730  3979 D BluetoothHeadset: Proxy object disconnected
11-28 18:58:12.761   929   929 D BluetoothHeadset: Proxy object disconnected
11-28 18:58:12.761  3061  3090 D BluetoothHeadset: Proxy object disconnected
11-28 18:58:12.761   929   929 D BluetoothHeadset: Proxy object disconnected
11-28 18:58:12.761  5786  5786 D A2dpService: Received stop request...Stopping profile...
11-28 18:58:12.762  5786  5817 D A2dpStateMachine: Exit Disconnected: -1
11-28 18:58:12.763   929   929 D BluetoothA2dp: Proxy object disconnected
,11-28 18:58:12.765  5632  5632 D DockEventReceiver: finishStartingService: stopping service
,11-28 18:58:12.766  5632  5632 D HeadsetProfile: Bluetooth service disconnected
11-28 18:58:12.766  5632  5632 D BluetoothA2dp: Proxy object disconnected
,11-28 18:58:12.768  5786  5786 D HidService: Received stop request...Stopping profile...
,11-28 18:58:12.768  5786  5786 D HidService: Stopping Bluetooth HidService
11-28 18:58:12.770  5786  5786 V BluetoothAdapterState: isTurningOff()=true
11-28 18:58:12.770  5786  5786 V BluetoothAdapterState: isTurningOn()=false
11-28 18:58:12.770  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:12.770  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:12.770  5632  5632 D BluetoothInputDevice: Proxy object disconnected
11-28 18:58:12.770  5632  5632 D HidProfile: Bluetooth service disconnected
11-28 18:58:12.772  5786  5786 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-28 18:58:12.773  5786  5786 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-28 18:58:12.773  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-28 18:58:12.773  5786  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:58:12.773  5786  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-28 18:58:12.773  5786  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:58:12.773  5786  5802 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-28 18:58:12.774  5786  5786 V BluetoothAdapterState: isTurningOff()=true
,11-28 18:58:12.774  5786  5786 V BluetoothAdapterState: isTurningOn()=false
,11-28 18:58:12.774  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:12.774  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:12.775  5786  5786 D HealthService: Received stop request...Stopping profile...
11-28 18:58:12.775  3513  3513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-28 18:58:12.776  3061  3061 D HeadsetProfile: Bluetooth service disconnected
11-28 18:58:12.777  3061  3061 D BluetoothA2dp: Proxy object disconnected
11-28 18:58:12.777  3061  3061 D BluetoothInputDevice: Proxy object disconnected
,11-28 18:58:12.777  3061  3061 D HidProfile: Bluetooth service disconnected
11-28 18:58:12.779  5786  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:58:12.779  5786  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-28 18:58:12.779  5786  5786 D PanService: Received stop request...Stopping profile...
11-28 18:58:12.779  5786  5809 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 18:58:12.779  5786  5809 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-28 18:58:12.780  5786  5809 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-28 18:58:12.780  5786  5809 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-28 18:58:12.780  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-28 18:58:12.780  5632  5632 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-28 18:58:12.780  5632  5632 D PanProfile: Bluetooth service disconnected
11-28 18:58:12.781  3061  3061 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-28 18:58:12.781  5786  5786 D BluetoothMapService: Received stop request...Stopping profile...
11-28 18:58:12.781  3061  3061 D PanProfile: Bluetooth service disconnected
11-28 18:58:12.781  5786  5786 D BluetoothMapService: stop()
,11-28 18:58:12.783  5786  5786 D BluetoothMapAppObserver: deinitObservers()
11-28 18:58:12.783  5786  5786 D BluetoothMapAppObserver: removeReceiver()
,11-28 18:58:12.785  3061  3061 D BluetoothMap: Proxy object disconnected
11-28 18:58:12.785  3061  3061 D MapProfile: Bluetooth service disconnected
11-28 18:58:12.785  5786  5786 D SapService: Received stop request...Stopping profile...
11-28 18:58:12.785  5786  5786 V SapService: stop()
11-28 18:58:12.785  5632  5632 D BluetoothMap: Proxy object disconnected
11-28 18:58:12.785  5632  5632 D MapProfile: Bluetooth service disconnected
11-28 18:58:12.786  5786  5786 V BluetoothAdapterState: isTurningOff()=true
11-28 18:58:12.786  5786  5786 V BluetoothAdapterState: isTurningOn()=false
11-28 18:58:12.786  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:12.786  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:58:12.786  5786  5786 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-28 18:58:12.787  5786  5786 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-28 18:58:12.788  5786  5802 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-28 18:58:12.789  5632  5632 D BluetoothPbap: Proxy object disconnected
11-28 18:58:12.789  5632  5632 D PbapServerProfile: Bluetooth service disconnected
,11-28 18:58:12.789  5786  5786 V BluetoothAdapterState: isTurningOff()=true
,11-28 18:58:12.790  5786  5786 V BluetoothAdapterState: isTurningOn()=false
11-28 18:58:12.790  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:12.790  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:12.790  5786  5786 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-28 18:58:12.790  5786  5802 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-28 18:58:12.790  5786  5786 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-28 18:58:12.790  3061  3061 D BluetoothPbap: Proxy object disconnected
11-28 18:58:12.790  3061  3061 D PbapServerProfile: Bluetooth service disconnected
,11-28 18:58:12.791  5786  5786 V BluetoothAdapterState: isTurningOff()=true
11-28 18:58:12.791  5786  5786 V BluetoothAdapterState: isTurningOn()=false
11-28 18:58:12.791  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:12.791  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:12.791  5786  5786 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-28 18:58:12.791  5786  5786 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-28 18:58:12.792  5786  5786 D BluetoothMapService: MAP Service closeService in
11-28 18:58:12.792  5786  5786 V BluetoothAdapterState: isTurningOff()=true
11-28 18:58:12.792  5786  5786 V BluetoothAdapterState: isTurningOn()=false
11-28 18:58:12.792  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:12.792  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:12.792  5786  5786 D BluetoothMapService: cleanup()
11-28 18:58:12.792  5786  5786 D BluetoothMapService: MAP Service closeService in
11-28 18:58:12.793  5786  5786 V BluetoothAdapterState: isTurningOff()=true
11-28 18:58:12.793  5786  5786 V BluetoothAdapterState: isTurningOn()=false
,11-28 18:58:12.793  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:12.793  5786  5786 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:12.793  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-28 18:58:12.793  5786  5798 D BluetoothAdapterProperties: Setting state to 15
11-28 18:58:12.793  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-28 18:58:12.794  5786  5798 I BluetoothAdapterState: Entering BleOnState
11-28 18:58:12.795  3061  3279 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-28 18:58:12.795  5632  5652 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-28 18:58:12.796  5632  5645 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-28 18:58:12.797  3061  3090 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 18:58:12.797  3061  3081 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-28 18:58:12.797  3061  3965 D BluetoothPan: onBluetoothStateChange on: false
11-28 18:58:12.798   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:58:12.798  3061  3279 D BluetoothPbap: onBluetoothStateChange: up=false
11-28 18:58:12.800  3730  3908 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:58:12.800  5632  5652 D BluetoothMap: onBluetoothStateChange: up=false
11-28 18:58:12.801  5632  5645 D BluetoothPan: onBluetoothStateChange on: false
11-28 18:58:12.801   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:58:12.802  3061  3081 D BluetoothMap: onBluetoothStateChange: up=false
11-28 18:58:12.802   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
11-28 18:58:12.802  5632  5652 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-28 18:58:12.802   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
11-28 18:58:12.803  5632  5645 D BluetoothPbap: onBluetoothStateChange: up=false
11-28 18:58:12.803  5786  5798 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-28 18:58:12.803  5786  5798 D BluetoothAdapterProperties: Setting state to 16
11-28 18:58:12.803  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-28 18:58:12.804  5786  5798 D BluetoothAdapterProperties: onBleDisable
11-28 18:58:12.804  5786  5798 I BluetoothAdapterState: Entering PendingCommandState
11-28 18:58:12.804  5786  5799 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-28 18:58:12.805  5786  5809 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-28 18:58:12.805  5786  5809 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-28 18:58:12.807  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:58:12.808  5786  5802 D BluetoothAdapterProperties: Scan Mode:20
,11-28 18:58:12.810  5573  5573 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:58:12.812  5632  5632 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 18:58:12.818  3513  3513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 18:58:12.818  5632  5632 D DockEventReceiver: finishStartingService: stopping service
,11-28 18:58:13.018  5786  5802 I bt_hci  : shut_down
,11-28 18:58:13.030  5786  5806 D bt_hwcfg: hw_epilog_process
,11-28 18:58:13.030  5786  5806 I bt_vendor: low_power_mode_cb
,11-28 18:58:13.033  5786  5806 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-28 18:58:13.033  5786  5806 I bt_vendor: epilog_cb
,11-28 18:58:13.033  5786  5806 I bt_hci  : epilog_finished_callback
,11-28 18:58:13.039  5786  5802 I bt_hci_h4: hal_close
,11-28 18:58:13.041  5786  5802 I bt_userial_vendor: device fd = 54 close
,11-28 18:58:13.163  5786  5799 D bt_stack_manager: event_shut_down_stack finished.
,11-28 18:58:13.164  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-28 18:58:13.167  5786  5798 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-28 18:58:13.168  5786  5786 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-28 18:58:13.169  5786  5786 D BtGatt.GattService: Received stop request...Stopping profile...
11-28 18:58:13.169  5786  5786 D BtGatt.GattService: stop()
,11-28 18:58:13.169  5786  5786 D BtGatt.AdvertiseManager: advertise clients cleared
11-28 18:58:13.173  5786  5786 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:13.173  5786  5786 V BluetoothAdapterState: isTurningOn()=false
11-28 18:58:13.173  5786  5786 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:13.173  5786  5786 V BluetoothAdapterState: isBleTurningOff()=true
,11-28 18:58:13.174  5786  5798 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-28 18:58:13.174  5786  5798 D BluetoothAdapterProperties: Setting state to 10
11-28 18:58:13.175  5786  5798 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-28 18:58:13.176  5786  5798 I BluetoothAdapterState: Entering OffState
,11-28 18:58:13.177   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-28 18:58:13.191  5786  5786 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-28 18:58:13.191  5786  5786 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-28 18:58:13.192  5786  5786 I BluetoothServiceJni: cleanupNative: return from cleanup
11-28 18:58:13.193  5786  5799 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-28 18:58:13.202  5786  5786 I art     : System.exit called, status: 0
,11-28 18:58:13.202  5786  5786 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-28 18:58:13.231   929  3107 I ActivityManager: Process com.android.bluetooth (pid 5786) has died
,11-28 18:58:14.253   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:15.254   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:15.861  3513  3513 I ConfigService: onDestroy
,11-28 18:58:16.255   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:17.256   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:17.730  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:58:17.730  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 18:58:17.737  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:58:17.738  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b8263f4 removed from the list
,11-28 18:58:17.738  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:58:17.740  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-28 18:58:17.740  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c00363 added. We now have 4 listener(s)
,11-28 18:58:17.741  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:17.743  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:58:17.743  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c00363 removed from the list
11-28 18:58:17.743  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:58:17.745  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:17.745  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95bcb60 added. We now have 4 listener(s)
,11-28 18:58:17.746  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 18:58:18.257   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:19.257   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-28 18:58:22.758  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:58:22.796   929   946 I ActivityManager: Start proc 5843:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-28 18:58:22.884  5843  5843 D AdapterServiceConfig: Adding HeadsetService
11-28 18:58:22.884  5843  5843 D AdapterServiceConfig: Adding A2dpService
11-28 18:58:22.884  5843  5843 D AdapterServiceConfig: Adding HidService
,11-28 18:58:22.885  5843  5843 D AdapterServiceConfig: Adding HealthService
11-28 18:58:22.885  5843  5843 D AdapterServiceConfig: Adding PanService
11-28 18:58:22.885  5843  5843 D AdapterServiceConfig: Adding GattService
11-28 18:58:22.885  5843  5843 D AdapterServiceConfig: Adding BluetoothMapService
11-28 18:58:22.885  5843  5843 D AdapterServiceConfig: Adding SapService
,11-28 18:58:22.896   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53ecd28:true
,11-28 18:58:22.897  5843  5843 D BluetoothAdapterState: make() - Creating AdapterState
,11-28 18:58:22.899  5843  5843 I bt_bluedroid: init
11-28 18:58:22.900  5843  5855 I BluetoothAdapterState: Entering OffState
,11-28 18:58:22.901  5843  5856 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-28 18:58:22.901  5843  5856 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-28 18:58:22.901  5843  5856 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-28 18:58:22.901  5843  5856 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-28 18:58:22.902  5843  5843 I bt_bluedroid: get_profile_interface socket
,11-28 18:58:22.904  5843  5859 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
11-28 18:58:22.904  5843  5843 I bt_bluedroid: get_profile_interface sdp
11-28 18:58:22.905  5843  5859 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 18:58:22.909  5843  5854 I bt_bluedroid: config_hci_snoop_log
,11-28 18:58:22.910   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-28 18:58:22.914  5843  5855 D BluetoothAdapterState: Current state: OFF, message: 0
,11-28 18:58:22.914  5843  5855 D BluetoothAdapterProperties: Setting state to 14
11-28 18:58:22.914  5843  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-28 18:58:22.916  5843  5855 D BluetoothBondStateMachine: make
,11-28 18:58:22.917  5843  5860 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-28 18:58:22.920  5843  5855 I BluetoothAdapterState: Entering PendingCommandState
,11-28 18:58:22.921  5843  5843 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-28 18:58:22.923  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
,11-28 18:58:22.923  5843  5843 D BtGatt.DebugUtils: handleDebugAction() action=null
11-28 18:58:22.924  5843  5843 D BtGatt.GattService: Received start request. Starting profile...
11-28 18:58:22.924  5843  5843 D BtGatt.GattService: start()
11-28 18:58:22.924  5843  5843 I bt_bluedroid: get_profile_interface gatt
11-28 18:58:22.925  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:22.925  5843  5843 D BtGatt.AdvertiseManager: advertise manager created
,11-28 18:58:22.929  5843  5843 V BluetoothAdapterState: isTurningOff()=false
,11-28 18:58:22.930  5843  5843 V BluetoothAdapterState: isTurningOn()=false
11-28 18:58:22.930  5843  5843 V BluetoothAdapterState: isBleTurningOn()=true
11-28 18:58:22.930  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:58:22.930  5843  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-28 18:58:22.931  5843  5855 I bt_bluedroid: bt_bluedroid
11-28 18:58:22.931  5843  5856 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-28 18:58:22.931  5843  5856 I bt_hci  : start_up
,11-28 18:58:22.936  5843  5856 I bt_vendor: alloc value 0xf3d7f871
,11-28 18:58:22.936  5843  5856 I bt_vendor: init
11-28 18:58:22.936  5843  5856 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-28 18:58:22.936  5843  5856 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-28 18:58:23.043  5843  5856 D bt_hci  : start_up starting async portion
,11-28 18:58:23.044  5843  5863 I bt_hci  : event_finish_startup
11-28 18:58:23.044  5843  5863 I bt_hci_h4: hal_open
11-28 18:58:23.044  5843  5863 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-28 18:58:23.045  5843  5863 I bt_userial_vendor: device fd = 54 open
,11-28 18:58:23.045  5864  5864 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 18:58:23.061  5843  5863 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 18:58:23.064  5843  5863 D bt_hwcfg: Chipset BCM4358A3
,11-28 18:58:23.064  5843  5863 D bt_hwcfg: Target name = [BCM4358A3]
,11-28 18:58:23.064  5843  5863 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-28 18:58:23.566  5843  5863 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-28 18:58:23.566  5843  5863 D bt_hwcfg: Settlement delay -- 100 ms
11-28 18:58:23.566  5843  5863 I bt_hwcfg: Setting fw settlement delay to 100 
,11-28 18:58:23.700  5843  5863 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-28 18:58:23.700  5843  5863 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:D4
11-28 18:58:23.702  5843  5863 I bt_hwcfg: vendor lib fwcfg completed
11-28 18:58:23.702  5843  5863 I bt_vendor: firmware callback
11-28 18:58:23.702  5843  5863 I bt_hci  : firmware_config_callback
,11-28 18:58:23.711  5843  5866 I bt_btu  : btu_task pending for preload complete event
,11-28 18:58:23.711  5843  5866 I bt_btu_task: Bluetooth chip preload is complete
,11-28 18:58:23.712  5843  5866 I bt_btu  : btu_task received preload complete event
,11-28 18:58:23.719  5843  5866 I         : BTE_InitTraceLevels -- TRC_HCI
,11-28 18:58:23.719  5843  5866 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-28 18:58:23.719  5843  5866 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-28 18:58:23.719  5843  5866 I         : BTE_InitTraceLevels -- TRC_AVDT
11-28 18:58:23.719  5843  5866 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-28 18:58:23.720  5843  5866 I         : BTE_InitTraceLevels -- TRC_A2D
,11-28 18:58:23.720  5843  5866 I         : BTE_InitTraceLevels -- TRC_BNEP
11-28 18:58:23.720  5843  5866 I         : BTE_InitTraceLevels -- TRC_BTM
,11-28 18:58:23.720  5843  5866 I         : BTE_InitTraceLevels -- TRC_GAP
11-28 18:58:23.720  5843  5866 I         : BTE_InitTraceLevels -- TRC_PAN
11-28 18:58:23.720  5843  5866 I         : BTE_InitTraceLevels -- TRC_SDP
11-28 18:58:23.721  5843  5866 I         : BTE_InitTraceLevels -- TRC_GATT
,11-28 18:58:23.721  5843  5866 I         : BTE_InitTraceLevels -- TRC_SMP
11-28 18:58:23.721  5843  5866 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-28 18:58:23.721  5843  5866 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-28 18:58:23.819  5843  5866 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3cfd549
11-28 18:58:23.820  5843  5866 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3cfd549 
,11-28 18:58:23.835  5843  5859 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-28 18:58:23.838  5843  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-28 18:58:23.838  5843  5859 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:D4
,11-28 18:58:23.841  5843  5859 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-28 18:58:23.844  5843  5859 D BluetoothAdapterProperties: Scan Mode:20
11-28 18:58:23.844  5843  5859 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 18:58:23.844  5843  5859 D bt_hci  : do_postload posting postload work item
,11-28 18:58:23.844  5843  5863 I bt_hci  : event_postload
11-28 18:58:23.845  5843  5863 I bt_vendor: sco_config_cb
11-28 18:58:23.845  5843  5863 I bt_hci  : sco_config_callback postload finished.
11-28 18:58:23.849  5843  5859 D bt_bte_conf: Device ID record 1 : primary
11-28 18:58:23.849  5843  5859 D bt_bte_conf:   vendorId            = 000f
11-28 18:58:23.849  5843  5859 D bt_bte_conf:   vendorIdSource      = 0001
,11-28 18:58:23.849  5843  5859 D bt_bte_conf:   product             = 1200
11-28 18:58:23.849  5843  5859 D bt_bte_conf:   version             = 1436
11-28 18:58:23.849  5843  5859 D bt_bte_conf:   clientExecutableURL = 
11-28 18:58:23.849  5843  5859 D bt_bte_conf:   serviceDescription  = 
11-28 18:58:23.850  5843  5859 D bt_bte_conf:   documentationURL    = 
11-28 18:58:23.850  5843  5859 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-28 18:58:23.850  5843  5856 D bt_stack_manager: event_start_up_stack finished
11-28 18:58:23.851  5843  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-28 18:58:23.851  5843  5855 D BluetoothAdapterProperties: Setting state to 15
11-28 18:58:23.851  5843  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-28 18:58:23.853  5843  5855 I BluetoothAdapterState: Entering BleOnState
,11-28 18:58:23.858  5843  5863 I bt_vendor: low_power_mode_cb
11-28 18:58:23.859  5843  5855 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-28 18:58:23.859  5843  5855 D BluetoothAdapterProperties: Setting state to 11
,11-28 18:58:23.859  5843  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-28 18:58:23.865  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:23.866  5843  5843 D HeadsetService: Received start request. Starting profile...
11-28 18:58:23.869  5843  5843 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-28 18:58:23.871  5843  5843 D HeadsetStateMachine: make
11-28 18:58:23.883  5843  5855 I BluetoothAdapterState: Entering PendingCommandState
,11-28 18:58:23.883  5843  5843 D HeadsetStateMachine: max_hf_connections = 1
,11-28 18:58:23.884  5843  5843 I bt_bluedroid: get_profile_interface handsfree
11-28 18:58:23.884  5843  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-28 18:58:23.885  5843  5859 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-28 18:58:23.888  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:23.889  5843  5843 D A2dpService: Received start request. Starting profile...
11-28 18:58:23.890  5843  5843 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-28 18:58:23.890  5843  5843 I bt_bluedroid: get_profile_interface avrcp
,11-28 18:58:23.897  5843  5843 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-28 18:58:23.898  5843  5843 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-28 18:58:23.898  5843  5843 D A2dpStateMachine: make
,11-28 18:58:23.900  5843  5843 I bt_bluedroid: get_profile_interface a2dp
,11-28 18:58:23.901  5843  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-28 18:58:23.903  5843  5874 D A2dpStateMachine: Enter Disconnected: -2
11-28 18:58:23.903  5843  5843 I BluetoothHidServiceJni: classInitNative: succeeds
11-28 18:58:23.904  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
,11-28 18:58:23.904  5843  5843 D HidService: Received start request. Starting profile...
,11-28 18:58:23.905  5843  5843 I bt_bluedroid: get_profile_interface hidhost
11-28 18:58:23.905  5843  5843 D HidService: setHidService(): set to: null
,11-28 18:58:23.905  5843  5859 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3cde56d
,11-28 18:58:23.905  5843  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-28 18:58:23.905  5843  5843 I BluetoothHealthServiceJni: classInitNative: succeeds
11-28 18:58:23.906  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:23.907  5843  5843 D HealthService: Received start request. Starting profile...
11-28 18:58:23.909  5843  5843 I bt_bluedroid: get_profile_interface health
11-28 18:58:23.910  5843  5843 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-28 18:58:23.911  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:23.912  5843  5843 D PanService: Received start request. Starting profile...
11-28 18:58:23.912  5843  5843 D BluetoothPanServiceJni: initializeNative(L110): pan
11-28 18:58:23.913  5843  5843 I bt_bluedroid: get_profile_interface pan
11-28 18:58:23.913  5843  5859 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-28 18:58:23.916  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
11-28 18:58:23.916  5843  5843 D BluetoothMapService: Received start request. Starting profile...
11-28 18:58:23.916  5843  5843 D BluetoothMapService: start()
,11-28 18:58:23.919  3513  3513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 18:58:23.922  5843  5843 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-28 18:58:23.923  5843  5843 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-28 18:58:23.923  5843  5843 D BluetoothMapAppObserver: createReceiver()
,11-28 18:58:23.924  5843  5843 D BluetoothMapAppObserver: initObservers()
,11-28 18:58:23.925  5843  5843 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-28 18:58:23.934  5843  5843 V SapService: SapBinder()
11-28 18:58:23.934  5843  5843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
,11-28 18:58:23.935  5843  5843 D SapService: Received start request. Starting profile...
11-28 18:58:23.935  5843  5843 V SapService: start()
,11-28 18:58:23.936  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:23.937  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:23.937  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:23.937  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:58:23.937  5843  5871 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-28 18:58:23.937  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:23.937  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:23.937  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:23.937  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:23.937  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:23.938  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:58:23.939  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:23.939  5843  5843 V BluetoothAdapterState: isTurningOn()=true
11-28 18:58:23.939  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:23.939  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
,11-28 18:58:23.942  5843  5843 V BluetoothAdapterState: isTurningOff()=false
11-28 18:58:23.942  5843  5843 V BluetoothAdapterState: isTurningOn()=true
,11-28 18:58:23.942  5843  5843 V BluetoothAdapterState: isBleTurningOn()=false
11-28 18:58:23.942  5843  5843 V BluetoothAdapterState: isBleTurningOff()=false
11-28 18:58:23.942  5843  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-28 18:58:23.942  5843  5855 D BluetoothAdapterProperties: ScanMode =  20
11-28 18:58:23.942  5843  5855 D BluetoothAdapterProperties: State =  11
11-28 18:58:23.944  5843  5859 D BluetoothAdapterProperties: Scan Mode:21
11-28 18:58:23.944  5843  5859 D BluetoothAdapterProperties: Discoverable Timeout:120
11-28 18:58:23.944  5843  5855 D BluetoothAdapterProperties: Setting state to 12
11-28 18:58:23.944  5843  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-28 18:58:23.945  5843  5855 I BluetoothAdapterState: Entering OnState
,11-28 18:58:23.945  3061  3090 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:58:23.946  5632  5652 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-28 18:58:23.947  5632  5645 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-28 18:58:23.950  3061  3965 D BluetoothA2dp: onBluetoothStateChange: up=true
11-28 18:58:23.951  5843  5843 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-28 18:58:23.952  3061  3061 D BluetoothA2dp: Proxy object connected
11-28 18:58:23.951  5632  5632 D BluetoothInputDevice: Proxy object connected
11-28 18:58:23.952  3061  3279 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-28 18:58:23.952  5632  5632 D HidProfile: Bluetooth service connected
11-28 18:58:23.952  5843  5843 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-28 18:58:23.954  3061  3061 D BluetoothInputDevice: Proxy object connected
,11-28 18:58:23.954  3061  3061 D HidProfile: Bluetooth service connected
11-28 18:58:23.954  5632  5632 D BluetoothA2dp: Proxy object connected
11-28 18:58:23.955  5843  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:58:23.955  3061  3081 D BluetoothPan: onBluetoothStateChange on: true
11-28 18:58:23.957   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 18:58:23.957  3061  3965 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 18:58:23.957  5843  5843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-28 18:58:23.958  5843  5843 D ObexServerSockets: Succeed to create listening sockets 
11-28 18:58:23.958  5843  5843 D ObexServerSockets0: startAccept()
11-28 18:58:23.958  5843  5843 D ObexServerSockets0: prepareForNewConnect()
11-28 18:58:23.959  3730  3908 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 18:58:23.960  5632  5645 D BluetoothMap: onBluetoothStateChange: up=true
11-28 18:58:23.961  5843  5843 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-28 18:58:23.961  5843  5843 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-28 18:58:23.962  5843  5881 D ObexServerSockets0: Accepting socket connection...
,11-28 18:58:23.962  5632  5652 D BluetoothPan: onBluetoothStateChange on: true
11-28 18:58:23.962  5843  5880 D ObexServerSockets0: Accepting socket connection...
,11-28 18:58:23.963  3061  3061 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 18:58:23.963  3061  3061 D PanProfile: Bluetooth service connected
,11-28 18:58:23.964  5632  5632 D BluetoothMap: Proxy object connected
11-28 18:58:23.965  5632  5632 D MapProfile: Bluetooth service connected
11-28 18:58:23.965  5632  5632 D BluetoothMap: getConnectedDevices()
,11-28 18:58:23.966   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:58:23.967  3061  3279 D BluetoothMap: onBluetoothStateChange: up=true
,11-28 18:58:23.967  5632  5632 D BluetoothPan: BluetoothPAN Proxy object connected
11-28 18:58:23.967  5632  5632 D PanProfile: Bluetooth service connected
,11-28 18:58:23.970   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
11-28 18:58:23.971  3061  3061 D BluetoothMap: Proxy object connected
11-28 18:58:23.971  3061  3061 D MapProfile: Bluetooth service connected
11-28 18:58:23.971  3061  3061 D BluetoothMap: getConnectedDevices()
11-28 18:58:23.971  5632  5879 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-28 18:58:23.972   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-28 18:58:23.972  5632  5645 D BluetoothPbap: onBluetoothStateChange: up=true
11-28 18:58:23.972   929   929 D BluetoothA2dp: Proxy object connected
,11-28 18:58:23.975  5843  5843 D BluetoothMapService: onReceive
,11-28 18:58:23.975  5843  5843 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-28 18:58:23.975  5843  5843 D BluetoothMapService: STATE_ON
,11-28 18:58:23.976   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
11-28 18:58:23.978  5843  5882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:58:23.981  5843  5882 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-28 18:58:23.981  5843  5882 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-28 18:58:23.982  5632  5632 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-28 18:58:23.987  5632  5632 D DockEventReceiver: finishStartingService: stopping service
11-28 18:58:23.989  3513  3513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-28 18:58:23.996  3061  3061 D BluetoothPbap: Proxy object connected
11-28 18:58:23.996  3061  3061 D PbapServerProfile: Bluetooth service connected
,11-28 18:58:23.997  5632  5632 D BluetoothPbap: Proxy object connected
11-28 18:58:23.997  5632  5632 D PbapServerProfile: Bluetooth service connected
,11-28 18:58:24.001  5843  5843 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-28 18:58:24.002  5843  5843 D ObexServerSockets0: prepareForNewConnect()
,11-28 18:58:24.004  5843  5887 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:58:24.014  5843  5891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-28 18:58:24.017  5843  5891 I BtOppRfcommListener: Accept thread started.
,11-28 18:58:24.047  5632  5879 D BluetoothHeadset: Proxy object connected
11-28 18:58:24.047   929   929 D BluetoothHeadset: Proxy object connected
11-28 18:58:24.048  3730  3752 D BluetoothHeadset: Proxy object connected
,11-28 18:58:24.048   929   929 D BluetoothHeadset: Proxy object connected
,11-28 18:58:24.048  3061  3081 D BluetoothHeadset: Proxy object connected
,11-28 18:58:24.048   929   929 D BluetoothHeadset: Proxy object connected
11-28 18:58:24.048  3061  3061 D HeadsetProfile: Bluetooth service connected
11-28 18:58:24.049  5632  5632 D HeadsetProfile: Bluetooth service connected
,11-28 18:58:24.058   929   946 D BluetoothHeadset: Proxy object connected
,11-28 18:58:24.060  3730  3747 D BluetoothHeadset: Proxy object connected
,11-28 18:58:24.067   929   946 D BluetoothHeadset: Proxy object connected
,11-28 18:58:24.070   929   946 D BluetoothHeadset: Proxy object connected
,11-28 18:58:24.072  5632  5645 D BluetoothHeadset: Proxy object connected
,11-28 18:58:24.073  5632  5632 D HeadsetProfile: Bluetooth service connected
,11-28 18:58:27.415  4031  4408 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,11-28 18:58:27.774  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:58:27.774  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:58:27.774  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:58:27.774  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-28 18:58:27.774  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:58:27.774  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-28 18:58:27.774  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-28 18:58:27.774  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-28 18:58:27.774  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-28 18:58:27.780  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-28 18:58:27.781  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:58:27.781  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95bcb60 removed from the list
11-28 18:58:27.782  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:58:27.784  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:27.784  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d0819 added. We now have 4 listener(s)
11-28 18:58:27.785  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 18:58:27.790   929  3574 D WifiService: setWifiEnabled: false pid=5573, uid=10077
,11-28 18:58:27.790   929  3574 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:58:32.802  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-28 18:58:32.803   929  3574 D WifiService: setWifiEnabled: true pid=5573, uid=10077
11-28 18:58:32.804   929  3574 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-28 18:58:32.811   508   924 D SoftapController: Softap fwReload - Ok
,11-28 18:58:32.818   508   924 D CommandListener: Setting iface cfg
,11-28 18:58:32.818   508   924 D CommandListener: Trying to bring down wlan0
,11-28 18:58:32.820   508   924 D CommandListener: Clearing all IP addresses on wlan0
,11-28 18:58:32.826   929  2913 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-28 18:58:33.511   929  2913 D wifi    : set interface wlan0 flags (UP)
,11-28 18:58:33.517   929  2913 I WifiHAL : Initializing wifi
,11-28 18:58:33.517   929  2913 I WifiHAL : Creating socket
,11-28 18:58:33.522   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-28 18:58:33.525   929  2913 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-28 18:58:33.525   929  2913 D wifi    : Did set static halHandle = 0x7f67703540
11-28 18:58:33.525   929  2913 D wifi    : halHandle = 0x7f67703540, mVM = 0x7f83d0d140, mCls = 0x1926
11-28 18:58:33.525   929  2913 D wifi    : array field set
,11-28 18:58:33.525   929  2913 I WifiNative-HAL: interface[0] = wlan0
11-28 18:58:33.528   929  5896 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547196253504
11-28 18:58:33.528   929  5896 D wifi    : waitForHalEvents called, vm = 0x7f83d0d140, obj = 0x1926, env = 0x7f68d8cb40
,11-28 18:58:33.585  5897  5897 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-28 18:58:33.630   929  2913 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-28 18:58:33.658  5897  5897 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 18:58:33.692  5897  5897 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-28 18:58:33.692  5897  5897 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-28 18:58:33.707   929  2913 D WifiConfigStore: Loading config and enabling all networks 
,11-28 18:58:33.728   929  2913 D WifiConfigStore: loaded 0 passpoint configs
,11-28 18:58:33.729   929  2913 W WifiConfigStore: Upgrading network 4 to android.uid.system:1000
11-28 18:58:33.729   929  2913 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-28 18:58:33.730   929  2913 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-28 18:58:33.730   929  2913 W WifiConfigStore: Upgrading network 3 to android.uid.system:1000
,11-28 18:58:33.731   929  2913 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,11-28 18:58:33.731   929  2913 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-28 18:58:33.732   929  2913 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 5
11-28 18:58:33.732   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "AndroidAP"WPA_PSK
11-28 18:58:33.732   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "AndroidHotspot2346"WPA_PSK
,11-28 18:58:33.732   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-28 18:58:33.732   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "Thali_internal"WPA_PSK
11-28 18:58:33.732   929  2913 E WifiConfigStore: found sortedWifiConfigurations : "MC"WPA_PSK
,11-28 18:58:33.734   929  2913 D WifiNative-HAL: Setting external_sim to 1
,11-28 18:58:33.734   929  2913 D wifi    : setting dfs flag to true, 0x7f6c1a6980
,11-28 18:58:33.734  4942  4942 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-28 18:58:33.735   929  2913 D WifiStateMachine: Setting OUI to DA-A1-19
11-28 18:58:33.735   929  2913 D wifi    : setting scan oui 0x7f6c1a6980
11-28 18:58:33.735   929  2913 D WifiHAL : Sending mac address OUI
,11-28 18:58:33.738   929  2913 E native  : do suspend false
,11-28 18:58:33.752   929  2913 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-28 18:58:33.753   508   924 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-28 18:58:33.753   929   929 D RttService: SCAN_AVAILABLE : 3
11-28 18:58:33.753   929  3021 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-28 18:58:33.754   508   924 D CommandListener: Setting iface cfg
,11-28 18:58:33.758   929  2912 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '158 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 158 Failed to set address (No such device)'
,11-28 18:58:33.759   929  2912 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-28 18:58:33.770   929  2912 D WifiNative-HAL: p2pGetDeviceAddress
,11-28 18:58:33.770   929  2912 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:70
,11-28 18:58:33.775   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163776 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,11-28 18:58:34.259   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:35.260   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:36.262   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:36.934  5897  5897 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 18:58:36.943  5897  5897 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 18:58:36.979   929  2913 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-28 18:58:36.980   929  2913 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-28 18:58:36.980   929  2913 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 18:58:36.990   929  2913 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-28 18:58:37.023   929  2913 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-28 18:58:37.030  5897  5897 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-28 18:58:37.263   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:37.451  5897  5897 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-28 18:58:37.483  5897  5897 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-28 18:58:37.484  5897  5897 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-28 18:58:37.491   929  2913 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-28 18:58:37.491   929  2913 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 18:58:37.491   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-28 18:58:37.526   929  2913 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-28 18:58:37.536   508   924 D CommandListener: Setting iface cfg
,11-28 18:58:37.540   929  2913 D WifiStateMachine: Start Dhcp Watchdog 3
,11-28 18:58:37.544   929  5902 D DhcpClient: Receive thread started
,11-28 18:58:37.548   929  2915 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-28 18:58:37.548   929  2913 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-28 18:58:37.548   929  2915 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-28 18:58:37.628   929  2913 E native  : do suspend false
,11-28 18:58:37.641   929  5901 D DhcpClient: Broadcasting DHCPDISCOVER
,11-28 18:58:37.656   929  5902 D DhcpClient: Received packet: 60:83:34:25:d7:70 OFFER, ip /192.168.1.109, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-28 18:58:37.656   929  5901 D DhcpClient: Got pending lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-28 18:58:37.659   929  5901 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.109 serverid=192.168.1.1
,11-28 18:58:37.672   929  5902 D DhcpClient: Received packet: 60:83:34:25:d7:70 ACK: your new IP /192.168.1.109, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-28 18:58:37.673   929  5901 D DhcpClient: Confirmed lease: IP address 192.168.1.109/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-28 18:58:37.677   508   924 D CommandListener: Setting iface cfg
,11-28 18:58:37.682   929  2913 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-28 18:58:37.684   929  5901 D DhcpClient: Scheduling renewal in 86399s
,11-28 18:58:37.692   929  2913 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-28 18:58:37.692   929  2913 D WifiConfigStore: No blacklist allowed without epno enabled
11-28 18:58:37.693   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-28 18:58:37.695   929  2913 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-28 18:58:37.701   929  2915 D ConnectivityService: Adding iface wlan0 to network 102
,11-28 18:58:37.747   929  2915 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-28 18:58:37.747   929  2915 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-28 18:58:37.750   929  2915 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-28 18:58:37.752   929  2915 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-28 18:58:37.754   929  2915 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-28 18:58:37.763   929  2915 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-28 18:58:37.768   929  2915 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-28 18:58:37.768   929  2915 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-28 18:58:37.768   929  2915 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-28 18:58:37.768   929  2913 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-28 18:58:37.768   929  2915 D ConnectivityService:    accepting network in place of null
11-28 18:58:37.768   929  2913 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-28 18:58:37.770   929  2915 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-28 18:58:37.783   929  5900 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-28 18:58:37.799   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-28 18:58:37.816  5573  5620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-28 18:58:37.816  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-28 18:58:37.816  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-28 18:58:37.816  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-28 18:58:37.816  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-28 18:58:37.816  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-28 18:58:37.816  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-28 18:58:37.816  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-28 18:58:37.816  5573  5620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-28 18:58:37.820  5573  5620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-28 18:58:37.820  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:58:37.820  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d0819 removed from the list
,11-28 18:58:37.820  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:58:37.825  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-28 18:58:37.825  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-28 18:58:37.828  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@d7be41d Bundle[{}]
,11-28 18:58:37.829  5573  5620 I io.jxcore.node.LifeCycleMonitor: start: OK
11-28 18:58:37.829  5573  5620 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-28 18:58:37.830  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-28 18:58:37.830  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-28 18:58:37.831  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-28 18:58:37.831   508   924 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-28 18:58:37.832  5573  5620 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-28 18:58:37.836   929  2915 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-28 18:58:37.836  3697  3829 W QCNEJ   : |CORE| network available: 102
11-28 18:58:37.836   929  2915 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-28 18:58:37.838   929  2915 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-28 18:58:37.839   929   946 D Tethering: MasterInitialState.processMessage what=3
11-28 18:58:37.841  3697  3829 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-28 18:58:37.844  5573  5620 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
11-28 18:58:37.845  5573  5620 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-28 18:58:37.845  5573  5620 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-28 18:58:37.846  3697  3829 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-28 18:58:37.846  3697  3829 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d770/64,192.168.1.109/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-28 18:58:37.848  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:37.848  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59a40de added. We now have 3 listener(s)
,11-28 18:58:37.849  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 18:58:37.850  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:58:37.850  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:58:37.850  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:37.850  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2572bf added. We now have 4 listener(s)
11-28 18:58:37.850  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:37.852  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 18:58:37.852   929  5899 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:81d::200e
11-28 18:58:37.853  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:37.853  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a23d8c added. We now have 4 listener(s)
11-28 18:58:37.854  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:58:37.855  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:58:37.855  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 18:58:37.855  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:37.855  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11d0cd5 added. We now have 5 listener(s)
11-28 18:58:37.855  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:37.855  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:58:37.855  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:58:37.855  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-28 18:58:37.855  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:58:37.855  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:37.855  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:58:37.855  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59a40de removed from the list
11-28 18:58:37.855  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:58:37.856  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2572bf removed from the list
11-28 18:58:37.856  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:58:37.856  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.856  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.858  5002  5026 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-28 18:58:37.858  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.858  5002  5026 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-28 18:58:37.858  5002  5026 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-28 18:58:37.858  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.858  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.858  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:37.858  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:37.858  5002  5026 E SarControlService: no key has been found,reset the power
11-28 18:58:37.858  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:37.858  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2572bf not in the list
11-28 18:58:37.858  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.858  5002  5039 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-28 18:58:37.858  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.858  5002  5039 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-28 18:58:37.858  5002  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-28 18:58:37.859  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-28 18:58:37.859  5027  5027 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-28 18:58:37.860  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.860  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.860  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.860  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:37.860  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:37.860  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:37.860  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11d0cd5 removed from the list
11-28 18:58:37.860  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:58:37.860  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:37.860  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-28 18:58:37.860  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a23d8c removed from the list
11-28 18:58:37.861  5002  5039 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-28 18:58:37.861  5002  5039 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-28 18:58:37.861  5002  5039 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-28 18:58:37.861  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:37.861  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5058cea added. We now have 3 listener(s)
11-28 18:58:37.862  3932  3932 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-28 18:58:37.862  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:58:37.862  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-28 18:58:37.862  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:58:37.863  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:37.863  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b487bdb added. We now have 4 listener(s)
11-28 18:58:37.863  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:37.863  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 18:58:37.863  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-28 18:58:37.863  5027  5027 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-28 18:58:37.864  3805  3805 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-28 18:58:37.864  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:37.864  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9fba678 added. We now have 4 listener(s)
11-28 18:58:37.867  5027  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdc7fa9 HexData = [00000000f003000000000000ffffffff]
11-28 18:58:37.867  5027  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-28 18:58:37.867  5027  5041 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-28 18:58:37.867  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:58:37.867  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:58:37.867  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:58:37.867  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:37.867  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5aea151 added. We now have 5 listener(s)
,11-28 18:58:37.867  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:37.867  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:58:37.867  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 18:58:37.867  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 18:58:37.867  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 18:58:37.867  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:58:37.867  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-28 18:58:37.868  5002  5012 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-28 18:58:37.870  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 18:58:37.870  3805  3805 D SystemUpdateService: onCreate
11-28 18:58:37.871  5027  5041 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdc7fa9 HexData = [00000000f103000000000000ffffffff]
,11-28 18:58:37.871  5027  5041 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-28 18:58:37.871  5027  5041 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-28 18:58:37.872  5027  5027 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-28 18:58:37.872  5002  5013 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-28 18:58:37.873  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 18:58:37.873  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:58:37.873  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 18:58:37.876  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.876  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 18:58:37.875  3805  3805 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-28 18:58:37.877  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:58:37.877  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:58:37.877  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-28 18:58:37.881  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.881  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 18:58:37.881  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 18:58:37.881  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 18:58:37.881  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 18:58:37.881  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.882  5573  5620 D BluetoothAdapter: STATE_ON
,11-28 18:58:37.885  5843  5853 D BtGatt.GattService: registerClient() - UUID=48452e6c-bc24-45b1-99cd-d4ab111ad5e1
,11-28 18:58:37.886  5843  5859 D BtGatt.GattService: onClientRegistered() - UUID=48452e6c-bc24-45b1-99cd-d4ab111ad5e1, clientIf=5
11-28 18:58:37.886  5573  5584 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-28 18:58:37.887  5843  5883 D BtGatt.GattService: start scan with filters
,11-28 18:58:37.890  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-28 18:58:37.890  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.890  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 18:58:37.890  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.890  5843  5862 D BtGatt.ScanManager: handling starting scan
11-28 18:58:37.891  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 18:58:37.891  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:58:37.891  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.891  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 18:58:37.891  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:58:37.891  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.891  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.891  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.891  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-28 18:58:37.892  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:58:37.892  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.892  5843  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7121006
,11-28 18:58:37.894  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.895  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:58:37.895  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.895  3805  3805 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
11-28 18:58:37.895  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.895  5573  5620 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-28 18:58:37.895  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-28 18:58:37.895  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-28 18:58:37.895  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-28 18:58:37.895  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:58:37.895  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:37.895  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-28 18:58:37.895  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 18:58:37.897  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.897  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.897  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.898  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:58:37.898  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:58:37.898  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.898  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:58:37.898  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:58:37.898  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.898  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.898  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.898  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 18:58:37.898  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.899  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:58:37.899  5843  5883 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 18:58:37.899  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:58:37.899  3805  5914 I SystemUpdateService: active receiver: enabled
11-28 18:58:37.900  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:58:37.900  5843  5854 D BtGatt.GattService: stopScan() - queue size =1
11-28 18:58:37.901  5843  5853 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:58:37.901  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:58:37.901  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.901  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 18:58:37.901  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.901  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.901  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.902  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.902  3805  5356 I iu.UploadsManager: num queued entries: 0
,11-28 18:58:37.902  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:58:37.902  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.902  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.902  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.902  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 18:58:37.902  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 18:58:37.902  5843  5859 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 18:58:37.903  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.903  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 18:58:37.903   929  5899 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 28 Nov 2016 17:58:37 GMT], X-Android-Received-Millis=[1480355917902], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480355917877]}
11-28 18:58:37.903  5843  5862 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 18:58:37.903  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.903   929  2915 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-28 18:58:37.904   929  2915 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-28 18:58:37.904   929  2915 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-28 18:58:37.904  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.904  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:58:37.904  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.904  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.905   929  2915 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-28 18:58:37.905  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-28 18:58:37.905  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:58:37.905  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:58:37.905  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.905  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:58:37.905  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 18:58:37.905  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.905  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.905  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.906  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:58:37.906  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.906  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 18:58:37.906  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-28 18:58:37.907  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:58:37.907  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:58:37.907  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:58:37.907  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:37.907  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:58:37.907  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5058cea removed from the list
11-28 18:58:37.907  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:37.907  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b487bdb removed from the list
11-28 18:58:37.907  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:58:37.907  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.907  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.907  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.907  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.907  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-28 18:58:37.908  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.908  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.909  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.909  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:37.909  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:37.909  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:37.909  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b487bdb not in the list
11-28 18:58:37.909  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.909  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.910  3805  3805 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-28 18:58:37.910  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.910  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.910  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.910  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:37.911  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:37.911  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:37.911  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5aea151 removed from the list
11-28 18:58:37.911  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-28 18:58:37.911  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:37.911  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:58:37.911  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9fba678 removed from the list
11-28 18:58:37.911  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 18:58:37.911  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.911  3805  3805 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-28 18:58:37.912  5843  5862 D BtGatt.ScanManager: Starting BLE batch scan
11-28 18:58:37.912  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:37.912  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@496cf42 added. We now have 3 listener(s)
11-28 18:58:37.912  5843  5862 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-28 18:58:37.913  5699  5699 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-28 18:58:37.914  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
,11-28 18:58:37.914  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:58:37.914  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:58:37.914  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:37.914  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6688b53 added. We now have 4 listener(s)
11-28 18:58:37.914  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:37.920  5843  5859 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 18:58:37.920  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.921  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 18:58:37.924  5699  5699 D SprintDMHelper: simOperator: 
11-28 18:58:37.924  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 18:58:37.924  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:37.924  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.924  5699  5699 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-28 18:58:37.924  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9132989 added. We now have 4 listener(s)
,11-28 18:58:37.926  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:58:37.926  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:58:37.926  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:58:37.926  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:37.926  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc69d8e added. We now have 5 listener(s)
11-28 18:58:37.926  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-28 18:58:37.926  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:58:37.927  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:58:37.927  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 18:58:37.927  5843  5862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 18:58:37.927  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 18:58:37.927  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-28 18:58:37.927  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-28 18:58:37.929  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-28 18:58:37.932  5843  5859 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 18:58:37.932  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.933  5843  5859 E BtGatt.ContextMap: Context not found for ID 5
,11-28 18:58:37.934  3805  5356 I iu.UploadsManager: num updated entries: 0
,11-28 18:58:37.935  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 18:58:37.935  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:58:37.935  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-28 18:58:37.934  3805  5914 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-28 18:58:37.937  3805  5356 I iu.SyncManager: NEXT; no task
,11-28 18:58:37.938  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.938  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 18:58:37.940  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:58:37.940  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:58:37.940  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-28 18:58:37.945  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.945  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 18:58:37.945  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 18:58:37.945  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 18:58:37.945  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 18:58:37.945  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.946  5573  5620 D BluetoothAdapter: STATE_ON
,11-28 18:58:37.948  5843  5854 D BtGatt.GattService: registerClient() - UUID=596a67ee-108f-4c90-9c7a-f4fbe1b053e3
11-28 18:58:37.948  5843  5859 D BtGatt.GattService: onClientRegistered() - UUID=596a67ee-108f-4c90-9c7a-f4fbe1b053e3, clientIf=5
11-28 18:58:37.948  5573  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-28 18:58:37.949  5843  5883 D BtGatt.GattService: start scan with filters
11-28 18:58:37.950  3805  5914 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-28 18:58:37.950  3805  5914 I SystemUpdateService: now status is 0 (complete)
11-28 18:58:37.950  3805  5914 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-28 18:58:37.950  3805  5914 I SystemUpdateService: file has been verified
11-28 18:58:37.950  3805  5914 I SystemUpdateService: OTA package size = 21989297
,11-28 18:58:37.952  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-28 18:58:37.952  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.952  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 18:58:37.952  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.952  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 18:58:37.952  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.952  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 18:58:37.952  5843  5862 D BtGatt.ScanManager: stopping BLe Batch
11-28 18:58:37.953  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:58:37.953  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.954  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-28 18:58:37.954  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.954  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 18:58:37.954  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-28 18:58:37.954  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.954  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.954  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.954  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.954  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.955  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.955  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.955  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-28 18:58:37.955  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:58:37.956  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:58:37.956  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:58:37.956  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:58:37.956  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:58:37.956  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:58:37.956  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:58:37.956  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:37.956  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-28 18:58:37.956  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@496cf42 removed from the list
11-28 18:58:37.956  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:37.957  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6688b53 removed from the list
11-28 18:58:37.957  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:58:37.957  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:58:37.957  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:58:37.957  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.957  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-28 18:58:37.957  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.957  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,11-28 18:58:37.957  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:58:37.957  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:58:37.957  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:58:37.957  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.957  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.957  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.957  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:58:37.957  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-28 18:58:37.957  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.957  5843  5862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:58:37.958  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.958  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.958  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.958  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:37.958  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:37.958  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:37.958  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6688b53 not in the list
,11-28 18:58:37.958  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:58:37.958  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.959  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:58:37.959  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:58:37.959  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.959  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.959  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.959  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-28 18:58:37.959  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.960  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:58:37.961  5843  5854 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 18:58:37.961  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:58:37.962  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:58:37.963  5843  5853 D BtGatt.GattService: stopScan() - queue size =0
11-28 18:58:37.963  5843  5859 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 18:58:37.963  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.964  5843  5872 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-28 18:58:37.964  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-28 18:58:37.964  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.964  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 18:58:37.964  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.964  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.964  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.964  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.965  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:58:37.965  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.965  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.965  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.965  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-28 18:58:37.965  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-28 18:58:37.965  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-28 18:58:37.966  5843  5862 D BtGatt.ScanManager: handling starting scan
11-28 18:58:37.967  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.968  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.968  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:58:37.968  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.968  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.969  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:37.969  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:37.969  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:37.969  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc69d8e removed from the list
11-28 18:58:37.969  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:58:37.969  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:58:37.969  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:58:37.969  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:37.969  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:58:37.969  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:58:37.969  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.969  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9132989 removed from the list
,11-28 18:58:37.969  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:58:37.969  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 18:58:37.969  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.969  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.970  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.970  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:58:37.970  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.970  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.970  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:37.970  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59c11cb added. We now have 3 listener(s)
,11-28 18:58:37.972  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:58:37.972  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.972  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:58:37.973  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.973  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-28 18:58:37.973  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:37.973  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:37.973  5843  5859 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 18:58:37.973  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.973  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee19da8 added. We now have 4 listener(s)
11-28 18:58:37.973  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:37.973  5843  5862 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 18:58:37.975  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-28 18:58:37.976  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:37.976  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0980c1 added. We now have 4 listener(s)
11-28 18:58:37.977  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:58:37.978  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:58:37.978  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:58:37.978  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:37.978  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8cd066 added. We now have 5 listener(s)
11-28 18:58:37.978  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:37.978  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:58:37.978  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-28 18:58:37.978  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-28 18:58:37.978  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-28 18:58:37.978  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:D4
11-28 18:58:37.978  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 18:58:37.978  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.978  5843  5862 D BtGatt.ScanManager: Starting BLE batch scan
11-28 18:58:37.979  5843  5862 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 18:58:37.980  3805  5914 I SystemUpdateService: showing system update notification
11-28 18:58:37.981  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-28 18:58:37.984  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-28 18:58:37.984  5573  5620 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-28 18:58:37.984  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-28 18:58:37.987  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:37.987  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-28 18:58:37.988  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-28 18:58:37.988  5843  5859 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-28 18:58:37.988  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-28 18:58:37.988  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.988  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-28 18:58:37.991  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.991  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-28 18:58:37.991  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-28 18:58:37.991  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-28 18:58:37.991  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-28 18:58:37.991  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:37.992  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-28 18:58:37.992  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.992  5573  5620 D BluetoothAdapter: STATE_ON
,11-28 18:58:37.994  5843  5862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 18:58:37.996   929   929 V NotificationService: pkg=com.google.android.gms canInterrupt=false intercept=true
11-28 18:58:37.996  5843  5853 D BtGatt.GattService: registerClient() - UUID=b2e63381-b427-4cc1-99d8-f5a27be5f6e4
11-28 18:58:37.997  5843  5859 D BtGatt.GattService: onClientRegistered() - UUID=b2e63381-b427-4cc1-99d8-f5a27be5f6e4, clientIf=5
11-28 18:58:37.997  5573  5583 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-28 18:58:37.997  5843  5883 D BtGatt.GattService: start scan with filters
11-28 18:58:37.998  3805  3805 D SystemUpdateService: onDestroy
,11-28 18:58:37.998  5843  5859 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 18:58:37.998  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:37.999  3513  5925 I VacuumService: Vacuum at: now=1480355917999 tag=VacuumService
,11-28 18:58:38.001  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-28 18:58:38.001  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:38.001  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-28 18:58:38.001  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.001  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-28 18:58:38.001  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.002  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-28 18:58:38.002  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.002  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-28 18:58:38.002  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,11-28 18:58:38.002  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.002  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.002  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.002  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.003  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-28 18:58:38.003  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.005  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-28 18:58:38.005  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.005  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:38.005  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-28 18:58:38.005  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.005  5843  5862 D BtGatt.ScanManager: stopping BLe Batch
11-28 18:58:38.005  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.005  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.007  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:58:38.007  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:58:38.007  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-28 18:58:38.007  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:58:38.007  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:58:38.007  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-28 18:58:38.008  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:38.008  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:58:38.008  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59c11cb removed from the list
11-28 18:58:38.008  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:58:38.008  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee19da8 removed from the list
11-28 18:58:38.008  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
11-28 18:58:38.008  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:58:38.008  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-28 18:58:38.008  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.008  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-28 18:58:38.008  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-28 18:58:38.008  5573  5620 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-28 18:58:38.008  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-28 18:58:38.008  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.008  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.008  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.009  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.009  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-28 18:58:38.009  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-28 18:58:38.009  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.010  5843  5862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-28 18:58:38.010  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:38.010  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:38.010  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:38.010  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee19da8 not in the list
11-28 18:58:38.010  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.010  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-28 18:58:38.010  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.011  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:58:38.011  5843  5883 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-28 18:58:38.012  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-28 18:58:38.014  5573  5620 D BluetoothAdapter: STATE_ON
11-28 18:58:38.015  5843  5872 D BtGatt.GattService: stopScan() - queue size =0
11-28 18:58:38.015  5843  5883 D BtGatt.GattService: unregisterClient() - clientIf=5
11-28 18:58:38.016  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-28 18:58:38.016  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.016  5843  5859 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 18:58:38.016  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:38.016  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-28 18:58:38.016  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.017  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.017  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.017  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.017  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-28 18:58:38.017  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.017  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.017  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.017  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-28 18:58:38.017  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-28 18:58:38.018  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-28 18:58:38.018  5843  5862 D BtGatt.ScanManager: handling starting scan
11-28 18:58:38.018  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.020  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.020  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:58:38.020  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.020  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.020  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:38.020  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:38.020  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-28 18:58:38.021  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:58:38.021  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b8cd066 removed from the list
11-28 18:58:38.021  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:58:38.021  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-28 18:58:38.021  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:38.021  5573  5573 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-28 18:58:38.021  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:58:38.021  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.021  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0980c1 removed from the list
11-28 18:58:38.021  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-28 18:58:38.021  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-28 18:58:38.021  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.021  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-28 18:58:38.021  5573  5573 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.021  5573  5573 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-28 18:58:38.022  5573  5573 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.022  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:38.022  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.022  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afaef43 added. We now have 3 listener(s)
11-28 18:58:38.023  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.023  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.023  5573  5573 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-28 18:58:38.023  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:58:38.023  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:58:38.023  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:58:38.023  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:38.023  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29079c0 added. We now have 4 listener(s)
11-28 18:58:38.023  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:38.024  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-28 18:58:38.024  5843  5859 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-28 18:58:38.025  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:38.025  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-28 18:58:38.025  5843  5862 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-28 18:58:38.025  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71c86f9 added. We now have 4 listener(s)
,11-28 18:58:38.026  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:D4"
11-28 18:58:38.026  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-28 18:58:38.026  5573  5620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-28 18:58:38.026  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-28 18:58:38.026  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5db863e added. We now have 5 listener(s)
11-28 18:58:38.026  5573  5620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-28 18:58:38.027  5573  5620 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-28 18:58:38.027  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:58:38.027  5573  5620 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-28 18:58:38.027  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:58:38.027  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:38.027  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:58:38.027  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afaef43 removed from the list
11-28 18:58:38.027  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:38.027  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29079c0 removed from the list
11-28 18:58:38.027  5573  5620 D io.jxcore.node.ConnectivityMonitor: stop
,11-28 18:58:38.027  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.027  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-28 18:58:38.029  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.029  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.029  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.029  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:38.029  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:38.029  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:38.029  5573  5620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29079c0 not in the list
11-28 18:58:38.029  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.029  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.030  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-28 18:58:38.030  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:38.030  5843  5862 D BtGatt.ScanManager: Starting BLE batch scan
,11-28 18:58:38.030  5843  5862 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-28 18:58:38.030  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.030  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.030  5573  5620 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-28 18:58:38.030  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-28 18:58:38.030  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-28 18:58:38.030  5573  5620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-28 18:58:38.030  5573  5620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5db863e removed from the list
11-28 18:58:38.030  5573  5620 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-28 18:58:38.031  5573  5620 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-28 18:58:38.031  5573  5620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-28 18:58:38.031  5573  5620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71c86f9 removed from the list
11-28 18:58:38.031  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,11-28 18:58:38.031  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-28 18:58:38.031  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-28 18:58:38.032  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:58:38.032  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-28 18:58:38.032  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-28 18:58:38.041  5843  5859 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-28 18:58:38.041  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:58:38.045  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-28 18:58:38.045  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:58:38.046  5843  5862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:58:38.050  5843  5859 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-28 18:58:38.050  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:38.050  5843  5859 E BtGatt.ContextMap: Context not found for ID 5
,11-28 18:58:38.059  5843  5859 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-28 18:58:38.059  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:38.059  5843  5862 D BtGatt.ScanManager: stopping BLe Batch
,11-28 18:58:38.063  3513  5928 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-28 18:58:38.064  5843  5859 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-28 18:58:38.064  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-28 18:58:38.064  5843  5862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-28 18:58:38.069  5843  5859 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-28 18:58:38.069  5843  5859 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-28 18:58:38.070  4942  5921 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-28 18:58:38.093  3513  5926 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-28 18:58:38.096  3513  5926 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-28 18:58:38.117  3513  5926 W Uploader:  no longer exists, so no auth token.
,11-28 18:58:38.123  3513  5928 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-28 18:58:38.263   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:38.382  3513  5932 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-28 18:58:38.406  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 18:58:38.470  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 18:58:38.522  5573  5573 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-28 18:58:38.569  3513  5928 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-28 18:58:38.627  3513  5926 W Uploader:  no longer exists, so no auth token.
,11-28 18:58:38.639  3513  5932 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-28 18:58:38.720  3513  5928 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-28 18:58:39.003  3513  5932 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-28 18:58:39.264   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-28 18:58:40.182  5573  5936 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 18:58:40.182  5573  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:58:40.983  5573  5936 W !!      : call onHalfStreamCopied
,11-28 18:58:40.983  5573  5936 I testCopyDataAndClose: closing input stream
,11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-28 18:58:41.751  5573  5936 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 18:58:45.774   929  2915 D ConnectivityService: handlePromptUnvalidated 102
,11-28 18:58:46.706  5573  5937 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:58:46.706  5573  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:58:48.706  5573  5620 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-28 18:58:48.706  5573  5620 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:58:48.706  5573  5620 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-28 18:58:48.778   929  2913 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-28 18:58:48.835  5573  5937 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-28 18:58:48.835  5573  5937 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:58:48.835  5573  5937 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,11-28 18:58:48.870  5573  5938 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 18:58:48.870  5573  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-28 18:58:50.504  5573  5938 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-28 18:58:55.129  5573  5939 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:58:55.129  5573  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:58:55.129  5573  5939 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:58:55.129  5573  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 18:58:55.130  5573  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-28 18:58:55.130  5573  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-28 18:58:55.130  5573  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-28 18:58:55.130  5573  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-28 18:58:55.130  5573  5939 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-28 18:58:55.130  5573  5939 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-28 18:58:55.130  5573  5939 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-28 18:58:55.130  5573  5939 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:58:55.130  5573  5939 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-28 18:58:55.132  5573  5620 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-28 18:58:55.135  5573  5940 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:58:55.135  5573  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-28 18:58:55.136  5573  5940 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
,11-28 18:58:55.136  5573  5940 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:58:55.136  5573  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-28 18:58:55.136  5573  5940 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-28 18:58:55.136  5573  5940 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-28 18:58:55.136  5573  5940 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-28 18:58:55.141  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-28 18:58:55.141  5573  5620 I jxcore-log: 
11-28 18:58:55.142  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG UnitTest_app: 'Number of passed tests:  81'
11-28 18:58:55.142  5573  5620 I jxcore-log: 
,11-28 18:58:55.142  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG UnitTest_app: 'Number of failed tests:  1'
11-28 18:58:55.142  5573  5620 I jxcore-log: 
,11-28 18:58:55.142  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-28 18:58:55.142  5573  5620 I jxcore-log: 
,11-28 18:58:55.143  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG UnitTest_app: 'Total duration:  92980'
11-28 18:58:55.143  5573  5620 I jxcore-log: 
11-28 18:58:55.144  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG UnitTest_app: 'Failures: 
11-28 18:58:55.144  5573  5620 I jxcore-log:  mCurrentOperation should be null
11-28 18:58:55.144  5573  5620 I jxcore-log: Expected: is null
11-28 18:58:55.144  5573  5620 I jxcore-log:      but: was <Start operation: Should affect listening to advertisements only>
11-28 18:58:55.144  5573  5620 I jxcore-log: '
11-28 18:58:55.144  5573  5620 I jxcore-log: 
,11-28 18:58:55.144  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-28 18:58:55.144  5573  5620 I jxcore-log: 
11-28 18:58:55.145  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-28 18:58:55.145  5573  5620 I jxcore-log: 
,11-28 18:58:55.148  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:58:55.148  5573  5620 I jxcore-log: 
,11-28 18:58:55.149  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:58:55.149  5573  5620 I jxcore-log: 
11-28 18:58:55.149  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-28 18:58:55.149  5573  5620 I jxcore-log: 
11-28 18:58:55.150  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 18:58:55.150  5573  5620 I jxcore-log: 
11-28 18:58:55.150  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:58:55.150  5573  5620 I jxcore-log: 
11-28 18:58:55.150  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 18:58:55.150  5573  5620 I jxcore-log: 
,11-28 18:58:55.150  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:58:55.150  5573  5620 I jxcore-log: 
11-28 18:58:55.151  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:58:55.151  5573  5620 I jxcore-log: 
11-28 18:58:55.151  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:58:55.151  5573  5620 I jxcore-log: 
11-28 18:58:55.151  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-28 18:58:55.151  5573  5620 I jxcore-log: 
11-28 18:58:55.151  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-28 18:58:55.151  5573  5620 I jxcore-log: 
,11-28 18:58:55.152  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:58:55.152  5573  5620 I jxcore-log: 
11-28 18:58:55.152  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 18:58:55.152  5573  5620 I jxcore-log: 
11-28 18:58:55.152  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:58:55.152  5573  5620 I jxcore-log: 
11-28 18:58:55.152  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 18:58:55.152  5573  5620 I jxcore-log: 
11-28 18:58:55.152  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:58:55.152  5573  5620 I jxcore-log: 
,11-28 18:58:55.153  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","ssidName":"<unknown ssid>"}'
11-28 18:58:55.153  5573  5620 I jxcore-log: 
11-28 18:58:55.153  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-28 18:58:55.153  5573  5620 I jxcore-log: 
11-28 18:58:55.153  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:58:55.153  5573  5620 I jxcore-log: 
11-28 18:58:55.153  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-28 18:58:55.153  5573  5620 I jxcore-log: 
,11-28 18:58:55.154  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-28 18:58:55.154  5573  5620 I jxcore-log: 
11-28 18:58:55.154  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:58:55.154  5573  5620 I jxcore-log: 
11-28 18:58:55.155  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-28 18:58:55.155  5573  5620 I jxcore-log: 
11-28 18:58:55.156  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-28 18:58:55.156  5573  5620 I jxcore-log: 
11-28 18:58:55.156  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-28 18:58:55.156  5573  5620 I jxcore-log: 
,11-28 18:58:55.156  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-28 18:58:55.156  5573  5620 I jxcore-log: 
11-28 18:58:55.157  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-28 18:58:55.157  5573  5620 I jxcore-log: 
11-28 18:58:55.157  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-28 18:58:55.157  5573  5620 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-28 18:58:55.157  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:58:55.157  5573  5620 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-28 18:58:55.157  5573  5620 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-28 18:58:55.157  5573  5620 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-28 18:58:55.157  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 18:58:55.157  5573  5620 I jxcore-log: 
11-28 18:58:55.158  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:58:55.158  5573  5620 I jxcore-log: 
,11-28 18:58:55.158  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 18:58:55.158  5573  5620 I jxcore-log: 
11-28 18:58:55.158  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:58:55.158  5573  5620 I jxcore-log: 
11-28 18:58:55.158  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-28 18:58:55.158  5573  5620 I jxcore-log: 
11-28 18:58:55.158  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-28 18:58:55.158  5573  5620 I jxcore-log: 
11-28 18:58:55.161  5573  5573 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-28 18:58:55.161  5573  5573 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-28 18:58:55.164  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-28 18:58:55.164  5573  5620 I jxcore-log: 
,11-28 18:58:55.164  5573  5620 I jxcore-log: 2016-11-28 17:58:55 - WARN testUtils: 'myNameCallback not set!'
11-28 18:58:55.164  5573  5620 I jxcore-log: 
,11-28 18:58:57.188  5573  5620 I jxcore-log: 2016-11-28 17:58:57 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-28 18:58:57.188  5573  5620 I jxcore-log: 
,11-28 18:58:57.190  5573  5620 I jxcore-log: 2016-11-28 17:58:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-28 18:58:57.190  5573  5620 I jxcore-log: 
,11-28 18:58:57.538  5573  5620 I jxcore-log: 2016-11-28 17:58:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-28 18:58:57.538  5573  5620 I jxcore-log: 
,11-28 18:58:57.550  5573  5620 I jxcore-log: 2016-11-28 17:58:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-28 18:58:57.550  5573  5620 I jxcore-log: 
,11-28 18:58:58.659  5573  5620 I jxcore-log: 2016-11-28 17:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-28 18:58:58.659  5573  5620 I jxcore-log: 
,11-28 18:58:58.847  5573  5620 I jxcore-log: 2016-11-28 17:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-28 18:58:58.847  5573  5620 I jxcore-log: 
,11-28 18:58:58.853  5573  5620 I jxcore-log: 2016-11-28 17:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-28 18:58:58.853  5573  5620 I jxcore-log: 
,11-28 18:58:58.858  5573  5620 I jxcore-log: 2016-11-28 17:58:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-28 18:58:58.858  5573  5620 I jxcore-log: 
,11-28 18:58:59.265   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:58:59.340  5573  5620 I jxcore-log: 2016-11-28 17:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-28 18:58:59.340  5573  5620 I jxcore-log: 
,11-28 18:58:59.385  5573  5620 I jxcore-log: 2016-11-28 17:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-28 18:58:59.385  5573  5620 I jxcore-log: 
,11-28 18:58:59.398  5573  5620 I jxcore-log: 2016-11-28 17:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-28 18:58:59.398  5573  5620 I jxcore-log: 
,11-28 18:58:59.402  5573  5620 I jxcore-log: 2016-11-28 17:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-28 18:58:59.402  5573  5620 I jxcore-log: 
,11-28 18:58:59.670  5573  5620 I jxcore-log: 2016-11-28 17:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-28 18:58:59.670  5573  5620 I jxcore-log: 
,11-28 18:58:59.797  5573  5620 I jxcore-log: 2016-11-28 17:58:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-28 18:58:59.797  5573  5620 I jxcore-log: 
,11-28 18:59:00.162  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-28 18:59:00.162  5573  5620 I jxcore-log: 
,11-28 18:59:00.170  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-28 18:59:00.170  5573  5620 I jxcore-log: 
,11-28 18:59:00.174  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-28 18:59:00.174  5573  5620 I jxcore-log: 
,11-28 18:59:00.180  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-28 18:59:00.180  5573  5620 I jxcore-log: 
,11-28 18:59:00.186  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-28 18:59:00.186  5573  5620 I jxcore-log: 
,11-28 18:59:00.215  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-28 18:59:00.215  5573  5620 I jxcore-log: 
,11-28 18:59:00.252  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-28 18:59:00.252  5573  5620 I jxcore-log: 
,11-28 18:59:00.260  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-28 18:59:00.260  5573  5620 I jxcore-log: 
,11-28 18:59:00.265   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:59:00.266  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-28 18:59:00.266  5573  5620 I jxcore-log: 
,11-28 18:59:00.282  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-28 18:59:00.282  5573  5620 I jxcore-log: 
,11-28 18:59:00.297  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-28 18:59:00.297  5573  5620 I jxcore-log: 
,11-28 18:59:00.304  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-28 18:59:00.304  5573  5620 I jxcore-log: 
,11-28 18:59:00.309  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-28 18:59:00.309  5573  5620 I jxcore-log: 
,11-28 18:59:00.322  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-28 18:59:00.322  5573  5620 I jxcore-log: 
,11-28 18:59:00.339  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-28 18:59:00.339  5573  5620 I jxcore-log: 
,11-28 18:59:00.354  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-28 18:59:00.354  5573  5620 I jxcore-log: 
,11-28 18:59:00.364  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-28 18:59:00.364  5573  5620 I jxcore-log: 
,11-28 18:59:00.377  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-28 18:59:00.377  5573  5620 I jxcore-log: 
,11-28 18:59:00.387  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-28 18:59:00.387  5573  5620 I jxcore-log: 
,11-28 18:59:00.400  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-28 18:59:00.400  5573  5620 I jxcore-log: 
,11-28 18:59:00.410  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-28 18:59:00.410  5573  5620 I jxcore-log: 
,11-28 18:59:00.417  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-28 18:59:00.417  5573  5620 I jxcore-log: 
,11-28 18:59:00.439  5573  5620 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-28 18:59:00.440  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO testUtils: 'BLE multiple advertisement supported'
11-28 18:59:00.440  5573  5620 I jxcore-log: 
,11-28 18:59:00.474  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-28 18:59:00.474  5573  5620 I jxcore-log: 
,11-28 18:59:00.806  5573  5620 I jxcore-log: 2016-11-28 17:59:00 - DEBUG CoordinatedClient: 'connected to the test server'
11-28 18:59:00.806  5573  5620 I jxcore-log: 
,11-28 18:59:01.113  5573  5620 I jxcore-log: 2016-11-28 17:59:01 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-28 18:59:01.113  5573  5620 I jxcore-log: 
,11-28 18:59:01.115  5573  5620 I jxcore-log: 2016-11-28 17:59:01 - DEBUG CoordinatedClient: 'test client failed'
11-28 18:59:01.115  5573  5620 I jxcore-log: 
,11-28 18:59:01.120  5573  5620 I jxcore-log: 2016-11-28 17:59:01 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-28 18:59:01.120  5573  5620 I jxcore-log: 
,11-28 18:59:01.127  5573  5620 I jxcore-log: 2016-11-28 17:59:01 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:226:22
11-28 18:59:01.127  5573  5620 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-28 18:59:01.127  5573  5620 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-28 18:59:01.127  5573  5620 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-28 18:59:01.127  5573  5620 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-28 18:59:01.127  5573  5620 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-28 18:59:01.127  5573  5620 I jxcore-log: 
,11-28 18:59:01.128  5573  5620 I jxcore-log: 2016-11-28 17:59:01 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-28 18:59:01.128  5573  5620 I jxcore-log: 
,11-28 18:59:01.266   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:59:01.560  5897  5897 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-28 18:59:01.573  5949  5949 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-28 18:59:01.581  5949  5949 D AndroidRuntime: CheckJNI is OFF
,11-28 18:59:01.604  5949  5949 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-28 18:59:01.630  5949  5949 I Radio-JNI: register_android_hardware_Radio DONE
,11-28 18:59:01.646  5949  5949 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-28 18:59:01.652   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-28 18:59:01.652   929   942 I ActivityManager: Killing 5573:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-28 18:59:01.693   929  2904 W InputDispatcher: channel 'ab5aa46 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-28 18:59:01.693   929  2904 E InputDispatcher: channel 'ab5aa46 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
11-28 18:59:01.697   929  3574 I WindowState: WIN DEATH: Window{ab5aa46 u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-28 18:59:01.697   929  3774 D GraphicsStats: Buffer count: 2
11-28 18:59:01.698   929  3574 W InputDispatcher: Attempted to unregister already unregistered input channel 'ab5aa46 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,11-28 18:59:01.698   929  2914 D WifiService: Client connection lost with reason: 4
,11-28 18:59:01.713   929   942 W ActivityManager: Force removing ActivityRecord{81fe0e u0 com.test.thalitest/.MainActivity t70}: app died, no saved state
,11-28 18:59:01.775   929   952 I art     : Starting a blocking GC Explicit
,11-28 18:59:01.782   929  3107 W ActivityManager: Spurious death for ProcessRecord{d61a569 0:com.test.thalitest/u0a77}, curProc for 5573: null
,11-28 18:59:01.819   929  3774 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 5573 uid 10077
,11-28 18:59:01.818  3774  3774 W Binder_B: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[25534]" dev="sockfs" ino=25534 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-28 18:59:01.818  3774  3774 W Binder_B: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[25534]" dev="sockfs" ino=25534 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-28 18:59:01.826  3623  3623 I Keyboard.Facilitator: onFinishInput()
,11-28 18:59:01.867   929   952 I art     : Explicit concurrent mark sweep GC freed 59774(3MB) AllocSpace objects, 15(512KB) LOS objects, 33% free, 29MB/43MB, paused 1.970ms total 90.585ms
,11-28 18:59:01.888   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-28 18:59:01.891  5949  5949 I art     : System.exit called, status: 0
11-28 18:59:01.891  5949  5949 I AndroidRuntime: VM exiting with result code 0.
,11-28 18:59:01.897   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-28 18:59:01.904  3932  5965 I MicroRecognitionRnrImpl: Starting detection.
,11-28 18:59:01.905  3932  5966 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@87d5ca6
,11-28 18:59:01.906   513  5968 I AudioFlinger: AudioFlinger's thread 0xf1cc0000 ready to run
,11-28 18:59:01.908   929  2905 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-28 18:59:01.910  5843  5843 D BluetoothMapAppObserver: onReceive
,11-28 18:59:01.910  5843  5843 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-28 18:59:01.914   513  2961 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 18:59:01.915  3932  5966 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@87d5ca6
11-28 18:59:01.916  3623  3623 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-28 18:59:01.918  4031  4119 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-28 18:59:01.919  3623  5969 I Keyboard.Facilitator.DecoderInitializer: run()
,11-28 18:59:01.925   513  5968 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
11-28 18:59:01.925   513  5968 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
11-28 18:59:01.926   513  5968 I ACDB-LOADER: ACDB AFE returned = -19
,11-28 18:59:01.926   513  5968 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
11-28 18:59:01.926   513  5968 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
11-28 18:59:01.926   513  5968 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,11-28 18:59:01.931  3623  5969 I Decoder : createOrResetDecoder
,11-28 18:59:01.938   513  5968 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-28 18:59:01.986  3356  5972 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-28 18:59:01.986   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-28 18:59:01.992  3513  3513 I ConfigService: onCreate
,11-28 18:59:01.993  3730  3730 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-28 18:59:02.009  3623  5969 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-28 18:59:02.017  3932  3932 I HotwordWorkerImpl: onReady
,11-28 18:59:02.023  3513  3513 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-28 18:59:02.023  3513  3513 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-28 18:59:02.032    27    27 W kworker/1:1: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 18:59:02.038  3805  5977 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-28 18:59:02.039  3805  5977 D AccountUtils: Clearing selected account for com.test.thalitest
,11-28 18:59:02.045    27    27 W kworker/1:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 18:59:02.051  3805  5977 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-28 18:59:02.059  3805  3805 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-28 18:59:02.059  3805  3805 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-28 18:59:02.061  3623  5969 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
11-28 18:59:02.064  3623  5969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-28 18:59:02.065  3623  5969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
11-28 18:59:02.068  3623  5969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
11-28 18:59:02.065    27    27 W kworker/1:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-28 18:59:02.068  3623  5969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
11-28 18:59:02.069  3623  5969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-28 18:59:02.069  3623  5969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,11-28 18:59:02.070  3623  5969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-28 18:59:02.070  3623  5969 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-28 18:59:02.070  3623  5969 I Keyboard.Facilitator.Delight2FileSweeper: run()
,11-28 18:59:02.070  3623  5969 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-28 18:59:02.070  3623  5969 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-28 18:59:02.070  3623  5969 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
11-28 18:59:02.073   929  3767 I ActivityManager: Start proc 5985:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-28 18:59:02.073  3762  3882 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-28 18:59:02.073  3762  3882 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3762
11-28 18:59:02.073  3762  3882 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:59:02.073  3762  3882 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-28 18:59:02.084  3805  5983 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
,11-28 18:59:02.083  3805  3805 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-28 18:59:02.084   929  3573 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-28 18:59:02.084  3805  3805 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-28 18:59:02.084  3805  5983 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
11-28 18:59:02.085  3805  5983 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
11-28 18:59:02.085  3805  5983 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
11-28 18:59:02.086  3932  4232 W SearchService: Abort, client detached.
,11-28 18:59:02.089   929  5994 E DropBoxManagerService: Can't write: system_app_crash
11-28 18:59:02.089   929  5994 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-28 18:59:02.089   929  5994 E DropBoxManagerService: 	... 8 more
,11-28 18:59:02.094  3805  5983 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/help_responses.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
11-28 18:59:02.094  3805  5983 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 1
11-28 18:59:02.094  3805  5983 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 2
11-28 18:59:02.095  3805  5983 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 1
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db'.
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.a(SourceFile:42)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:102)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:59:02.098  3805  5983 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: Couldn't open auto_complete_suggestions.db for writing (will try read-only):
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-28 18:,59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.a(SourceFile:42)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:102)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:59:02.099  3805  5983 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 18:59:02.099  3356  5972 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-28 18:59:02.100  3805  5983 W SQLiteOpenHelper: Opened auto_complete_suggestions.db in read-only mode
11-28 18:59:02.100  3805  5983 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
11-28 18:59:02.100  3805  5983 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-28 18:59:02.101  3805  5983 E SQLiteLog: (8) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
11-28 18:59:02.101  3356  5972 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
11-28 18:59:02.101  3356  5972 E AndroidRuntime: Process: android.process.acore, PID: 3356
11-28 18:59:02.101  3356  5972 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForC,hangedRowCount(SQLiteSession.java:754)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:59:02.101  3356  5972 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 18:59:02.102  3805  5983 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 1
11-28 18:59:02.102  3805  5983 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-28 18:59:02.102  3805  5983 E AndroidRuntime: Process: com.google.android.gms, PID: 3805
11-28 18:59:02.102  3805  5983 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at com.google.android.gms.googlehelp.search.b.e(SourceFile:105)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:53)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-28 18:59:02.102  3805  5983 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-28 18:59:02.103   929  6000 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-28 18:59:02.098   739   739 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[26559]" dev="sockfs" ino=26559 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:59:02.098   739   739 W Binder_4: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[26559]" dev="sockfs" ino=26559 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:59:02.102   404   404 W Binder_2: type=1400 audit(0.0:126): avc: denied { ioctl } for path="socket:[34960]" dev="sockfs" ino=34960 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:59:02.102   404   404 W Binder_2: type=1400 audit(0.0:127): avc: denied { ioctl } for path="socket:[34960]" dev="sockfs" ino=34960 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-28 18:59:02.113   929  6003 E DropBoxManagerService: Can't write: system_app_crash
11-28 18:59:02.113   929  6003 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 18:59:02.113   929  6003 E DropBoxManagerService: 	... 5 more
11-28 18:59:02.113   929  6002 E DropBoxManagerService: Can't write: system_app_crash
11-28 18:59:02.113   929  6002 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-28 18:59:02.113   929  6002 E DropBoxManagerService: 	... 5 more
11-28 18:59:02.141  3932  3932 I HotwordDetector: Closing mic
,11-28 18:59:02.143  3932  4133 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@87d5ca6
11-28 18:59:02.143  3932  5966 E AudioRecord-JNI: Error -4 during AudioRecord native read
11-28 18:59:02.152  3805  5996 W BaseAppContext: Using Auth Proxy for data requests.
11-28 18:59:02.164  3805  5996 W BaseAppContext: Using Auth Proxy for data requests.
11-28 18:59:02.184   929   939 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-28 18:59:02.202  3932  6005 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-28 18:59:02.212   513  5968 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-28 18:59:02.213   513  5968 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,11-28 18:59:02.214  3805  5977 E GMPM-SVC: Scheduler not initialized or shutdown. Not logging error/warn.
,11-28 18:59:02.216   513  5968 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
11-28 18:59:02.216   513  5968 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
11-28 18:59:02.217   513  2961 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
11-28 18:59:02.219  3932  5965 I MicroRecognitionRnrImpl: Detection finished
,11-28 18:59:02.220  3932  4139 I MicroRecognitionRnrImpl: Stopping hotword detection.
,11-28 18:59:02.234  3805  3805 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-28 18:59:02.235  3805  4869 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/user/0/com.google.android.gms/shared_prefs/config_removals.xml.bak
,11-28 18:59:02.247  3805  3805 I ConfigFetchService: service connected
,11-28 18:59:02.264  3805  6007 I GMPM-SVC: App measurement is starting up
,11-28 18:59:02.267   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-28 18:59:02.268  3805  6007 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-28 18:59:02.269  3805  6007 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-28 18:59:02.294  3805  4158 I Icing   : doRemovePackageData com.test.thalitest
,11-28 18:59:02.302  3805  6010 I PeopleContactsSync: CP2 sync disabled
,11-28 18:59:02.346   929   942 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{6ee921e u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{41eeaa0 3805 com.google.android.gms/10012/u0 remote:bab17a3}: process crashing
,11-28 18:59:02.354   929  3774 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3805 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-28 18:59:02.432   381   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
